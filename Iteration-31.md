# Iteration 31 (19 Aug 2015 - 2 Sept 2015)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* Interactive Help
* Shared folders in HUD

## Iteration Goals:
* Continue progress on refactored backend
* Focus on legacy adapter
* Test responsiveness changes for Center

### NC
* Continue supporting testing efforts
* Java 8 Pull Request for legacy - Evaluating
* Legacy bugs

### Center / Interactive Help
* Continue Interactive Help
* Begin Interactive Help Integration 
* Submit PR Request for Table View on All Listings and Org Listing pages

### Backend (new)
* Update Quickview to use new backend [#21] (https://github.com/ozone-development/ozp-backend/issues/21) [#35] (https://github.com/ozone-development/ozp-backend/issues/35)
* Add support for menu-profile modal in HUD [#20] (https://github.com/ozone-development/ozp-backend/issues/20) 
* Endpoint for creating and editing a new listing [#32](https://github.com/ozone-development/ozp-backend/issues/32)

### HUD
* Work on 'share a folder' functionality where HUD can open a folder of apps in a new dashboard in webtop 
  * Get help from UI/UX to implement a temporary way to share dashboard url’s

### Webtop
* Improve accessibility
  * List of specific 508 compliance items that have been completed
  * List of potential 508 compliance challenges
* 'Share a folder' functionality where HUD can open a folder of apps in a new dashboard in webtop
  * finish Bookmark apps so a user does not already have bookmarked so they can be added to the new dashboard

### Legacy Adapter + Backend
* Frontend:
    * Chrome API (widget chrome)
* Backend:
    * Ensure functionality of all preference endpoints.
    * Address remaining legacy endpoints:
        * /metrics
        * /access

### IWC
* Documentation

### Metrics
* Setup high side deploy for HUD and webtop metrics

### UI/UX
* Support on-going development
  * ~~Provide temp UI to share HUD folders via URL~~
  * ~~Provide styling and content structuring support for Help Center~~
  * Provide support for responsive merge issues on new Listings Management Table View PR / HUD PR
* Future features
  * ~~Further test and support Center responsiveness~~
  * ~~Mockup screenshots of Contact modal (separate submit feedback/bugs), discussion with customer~~
  * ~~Mockup screenshots of Help modal with videos~~
  * Support implementation of Contact modal [#348] (https://github.com/ozone-development/ozp-center/issues/348)

## Roadblocks