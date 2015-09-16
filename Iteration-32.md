# Iteration 32 (2 Sept 2015 - 16 Sept)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* Interactive Help
* Shared folders in HUD

## Iteration Goals:
* Finish all Center and HUD endpoints for new backend, cleanup docs and tests
* Demonstration and feedback on interactive help
* Review pull request for table listing view

### NC
* Continue supporting testing efforts
* ~~Java 8 Support for OWF~~ - Only Testing and Release remain
* Convert the sample Log Widget to use IWC
* ~~Look into implementing contact modal~~ - Pull Request Submitted for HUD/Center/Webtop/ozp-react-commons
* ~~Automated IWC documentation to create PDFs~~
* ~~Updated Documentation with new features~~ - Pull Requests Submitted

### Center / Interactive Help
* Continue Interactive Help
* Begin integration of Help

### Backend (new)
* ~~Listing Management endpoints [#30](https://github.com/ozone-development/ozp-backend/issues/30)~~
* ~~Allow user to change org when creating a listing [#56](https://github.com/ozone-development/ozp-backend/issues/56)~~
* ~~Add an image endpoint [#54](https://github.com/ozone-development/ozp-backend/issues/54)~~
* ~~Add listing counts [#49](https://github.com/ozone-development/ozp-backend/issues/49)~~
* ~~Add profile search endpoint [#55](https://github.com/ozone-development/ozp-backend/issues/55)~~
* ~~Change ItemComment to Review [#47](https://github.com/ozone-development/ozp-backend/issues/47)~~
* ~~Update documentation [#50](https://github.com/ozone-development/ozp-backend/issues/50)~~
* ~~Anything else that Blaine tells me I need to fix~~


### Webtop / HUD
* ~~Work on 'share a folder' functionality where HUD can open a folder of apps in a new dashboard in webtop~~ 
* ~~When library reloaded on launchFolder, push bookmarked apps in to available apps [webtop #631](https://github.com/ozone-development/ozp-webtop/issues/631)~~
* Implement Share Folder modal [hud #123](https://github.com/ozone-development/ozp-hud/issues/123)

### 508
* Improve accessibility for (Center, HUD, Webtop)
  * List of specific 508 compliance items currently working on
    * Center - The form shall allow people using assistive technology (ie. JAWS) to access the information, field elements, and functionality required for completion and submission of the form. [#371] (https://github.com/ozone-development/ozp-center/issues/371)
    * Center - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#370] (https://github.com/ozone-development/ozp-center/issues/370)

  * List of specific 508 compliance items that have been completed

  * List of potential 508 compliance challenges
    * Center - Not so much of a challenge but something to think about we a new app is created with images, what would be the best way to add alternatives tags to the new images (in form).


### IWC/Legacy Adapter
* Documentation
   * Debugger use
* Legacy Adapter support to users
* Legacy Backend endpoints (widget listing endpoints & /metrics)

### Metrics
* ~~Meet to discuss automation of specific reports~~

### UI/UX
* Support on-going development
  * ~~Support Help implementation / responsiveness~~
  * ~~Update icon repo to add contact/help icons~~
  * ~~Fix style/display bugs reported on staging~~
  * Set up docker for LESS>SASS conversion
  * Provide support for responsive merge issues on new Listings Management Table View PR / HUD PR
* Future features
  * ~~Support implementation of Contact modal [#348] (https://github.com/ozone-development/ozp-center/issues/348)~~
  
## Roadblocks