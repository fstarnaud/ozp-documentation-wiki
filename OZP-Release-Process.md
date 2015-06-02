# Creating an OZP release
The following repos require releasing:
* ozp-center
* ozp-hud
* ozp-webtop
* ozp-rest
* ozp-react-commons
* ozp-iwc(*)
* ozp-iwc-owf7-widget-adapter(*)

(*) these repos are currently managed by Kevin, so the only action is to update the latest tag used for the master builds of these two projects in Jenkins (iwc does not currently use the Gitflow model with both `develop` and `master` branches. Instead, the master Jenkins jobs for iwc and the iwc-owf7-adapter pull down specific, hard-coded tags)

The process typically goes like this:

0. Since this will trigger lots of Jenkins builds, each of which will trigger a separate deployment (which takes nearly 10 minutes), you may want to disable the `deploy-ci-develop` and `deploy-ci-master` jobs first, then re-enable them after all the builds have finished (and then manually run both deploy jobs)
1. Clone all of the above repos on your machine, say in `~/ozp-repos`
2. Clone `dev-tools` as well and run `release-preview.sh`. This script pulls the latest for `develop` and `master` in each of the non-iwc repos and reports two things: a) commits on `master` that are not on `develop` (this is generally bad, so hopefully nothing shows up here), and b) commits on `develop` that are not yet on `master`. Other than pulling down the latest code, this is just a nice sanity check
3. For each repo that has changes:
 * `git checkout master; git merge develop --no-ff;`. For the merge comment, using something like "Merge branch develop for weekly release".  
 * bump the version number (usually just the patch version) in both `package.json` and `bower.json` (or `package.json` and `application.settings` in `ozp-rest`)
 * generate the changelog via `gulp changelog` (center, hud, react-commons) or `grunt changelog` (webtop) or `npm run changelog` (ozp-rest)
* `git commit -am "release-vX.Y.Z"`
* now tag the release: `git tag -a vX.Y.Z -m "vX.Y.Z"`
* and push the merge and new tag to master: `git push --follow-tags`
* now merge the release back to develop: `git checkout develop; git merge master --no-ff; git push`. For the merge comment, use something like "Merge branch master back into develop after release"

After this is done, wait for Jenkins to finish building everything (if you disabled the deploy jobs prior to making the release, re-enable them now and manually trigger them). After that's finished, sanity check that things look good on both ci-develop and ci-master. Also check the latest build artifacts for the various repos (especially `ozp-rest`) and make sure file sizes and dates look right.

After verifying the release, let someone on ADV know to 'hit the button' to transfer the release over.