In general, the process for creating a release for any of the OZP applications is as follows (for repos following the [gitflow convention](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow/):

Prep:

1. `git pull` on both `master` and `develop`
2. make sure there are no commits on master that are not also on develop: `git log origin/develop..origin/master`
3. If there are, `git checkout develop; git merge master --no-ff; git push;`
4. Review the commits to be added to master: `git log origin/master..origin/develop`

Release:

1. merge develop into master `git checkout master; git merge develop;`
2. bump the version number in `package.json` and `bower.json` (or `application.properties` in `ozp-rest`). Be sure to append `-rc` (release candidate) to the end of the version number. i.e. `1.2.3-rc`. The `rc` will be removed after full testing has been completed
3. generate the changelog (usually `grunt changelog` or `gulp changelog`)
4. commit the release `git commit -am "release-v1.2.3-rc"`
5. tag the release `git tag -a v1.2.3-rc -m "v1.2.3-rc"`
6. `git push --follow-tags`
7. update gh-pages (maybe)

For repos not following gitflow (just using tags on the master branch), the basic ideas are the same as above, except that we're interested in the differences between `master` and the latest tag.
