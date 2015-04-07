In general, the process for creating a release for any of the OZP applications is as follows:

Prep:

1. `git pull` on both `master` and `develop`
2. make sure there are no commits on master that are not also on develop: `git log origin/develop..origin/master
2a. If there are, `git checkout develop; git merge master --no-ff; git push;`
3. Review the commits to be added to master: `git log origin/master..origin/develop`

Release:

1. `git checkout master; git merge develop;`  # merge develop into master
2. bump the version number in `package.json` and `bower.json` (or `application.properties` in `ozp-rest`). Be sure to append `-rc` (release candidate) to the end of the version number. i.e. `0.7.3-rc`. The `rc` will be removed after full testing has been completed
3. generate the changelog (usually `grunt changelog` or `gulp changelog`)
4. commit the release `git commit -am "release-vX.Y.Z-rc"
5. tag the release `git tag -a vX.Y.Z-rc -m "vX.Y.Z-rc"
6. `git push --follow-tags`
7. update gh-pages (maybe)