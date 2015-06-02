# Creating an OZP release
The following repos require releasing:
* ozp-center
* ozp-hud
* ozp-webtop
* ozp-rest
* ozp-react-commons
* ozp-iwc(*)
* ozp-iwc-owf7-widget-adapter(*)

(*) these repos are currently managed by Kevin, so the only action is to update the latest tag used for the master builds of these two projects in Jenkins (iwc does not currently use the Gitflow model with both `develop` and `master` branches)

The process typically goes like this:

1. Clone all of the above repos on your machine, say in `~/ozp-repos`
2. Clone `dev-tools` as well and run `release-preview.sh`. This script pulls the latest for `develop` and `master` in each of the non-iwc repos and reports two things: a) commits on `master` that are not on `develop` (this is generally bad, so hopefully nothing shows up here), and b) commits on `develop` that are not yet on `master`. Other than pulling down the latest code, this is just a nice sanity check
3. For each repo that has changes:
 * `git checkout master; git merge develop --no-ff;`. For the merge comment, using something like "Merging develop into master for weekly release".  
 * bump the version number (usually just the patch version) in both `package.json` and `bower.json` (or `application.settings` in `ozp-rest`)
 * generate the changelog via `gulp changelog` (center, hud, react-commons) or `grunt changelog` (webtop) or `npm run changelog` (ozp-rest)
* `git commit -am "release-vX.Y.Z"`