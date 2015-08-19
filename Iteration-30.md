# Iteration 30 (05 Aug 2015 - 19 Aug 2015)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* Interactive Help

## Iteration Goals:
* Continue progress on refactored backend
* Continue progress shared folders in HUD
* Menu Counts for Organizations ~~and Categories~~

### NC
* Continue supporting testing efforts
* Java 8 Pull Request for legacy - TBD
* Legacy bugs

### Center / Interactive Help
* Continue Interactive Help
* ~~Counts for organizations~~ and categories - [342](https://github.com/ozone-development/ozp-center/issues/342)
* Submit PR for Table View (NC)  - Will be submitted the next sprint
* ~~Agency should be reported with metadata sent to metrics [#330](https://github.com/ozone-development/ozp-center/issues/330)~~

### Backend (new)
* ~~Update Listing Management to use new backend [#38](https://github.com/ozone-development/ozp-backend/issues/38)~~
* ~~Update Profile Modal to use new backend [#19](https://github.com/ozone-development/ozp-backend/issues/19), [#20](https://github.com/ozone-development/ozp-backend/issues/20)~~

### HUD
* Work on 'share a folder' functionality where HUD can open a folder of apps in a new dashboard in webtop
  * ~~Create custom URL in hud with the folder name, and UUID/ID's of widgets to launch in HUD~~
  * Implement way for user to share URL with other users 

### Webtop
* Improve accessibility
  * List of specific 508 compliance items that have been completed
  * List of potential 508 compliance challenges
* Streamline behavior of clicking an app icon in the webtop toolbar between both grid and desktop views [#596](http://github.com/ozone-development/ozp-webtop/issues/596)
* 'Share a folder' functionality where HUD can open a folder of apps in a new dashboard in webtop
  * ~~Create new endpoint for launch-folder URL and parameters~~
  * ~~Create and change in to new dashboard based on launch-folder name~~
  * Bookmark apps that a user does not already have bookmarked so they can be added to the new dashboard
* ~~Alphabetize listings in the bookmarks modal correctly - make it case insensitive [#620](http://github.com/ozone-development/ozp-webtop/issues/620)~~
* ~~Fix dropdown menu bugs [#618](http://github.com/ozone-development/ozp-webtop/issues/618) [#619](http://github.com/ozone-development/ozp-webtop/issues/619)~~
* ~~Minor bug / branding / style fixes~~
* ~~Webtop now uses IWC except for data~~

### IWC
* Documentation
  * How to use the debugger
* ~~IE11 local storage bug prevents iwc use outside of webtop. This bug also breaks intents as intent chooser opens outside of webtop. Only IE11 (will discuss when back in office after meeting) [#301](
https://github.com/ozone-development/ozp-iwc/issues/301)~~
* ~~iwc-angular-adapter merge~~
* ~~Remove timeout dependencies on IWC initialization~~


### Metrics
* ~~Investigate adding metrics to webtop and HUD~~
* ~~Added metrics capability to webtop~~
* ~~Added metrics capability to HUD~~
* ~~Make piwik keys variables in configuration file for Center HUD and Webtop~~

### UI/UX
* ~~Support on-going development~~
  * ~~Give recommendation for help desk link additions~~
  * ~~Provide styling and content structuring support for Help Center~~
* ~~Future features:~~
  * ~~Responsiveness (investigate future complete responsiveness, choose a bootstrap breakpoint for now and implement across platform)~~

## Roadblocks