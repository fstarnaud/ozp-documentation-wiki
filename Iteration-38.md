# Iteration 38 (25 Nov - 9 Dec)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* Dec 2015 - backend alpha in staging  
* Help Articles deployed to production

## Iteration Goals:
* Continue new backend testing with center, hud, webtop, and iwc
* Single staging VM running with production data

### Front End (Center, HUD, Webtop)
* Center:
  * Open Search
* Help Tour:
 * Investigate further functionality for launching modals, dropdowns, etc. 
 * Testing and exploring options for Help Tour
 * Clean up tour links/paths to bake in react actions
 * Set tour to open on first visit to Ozone
* Webtop
 * Investigate ability to display a message when apps can not be displayed in the webtop  [#649](https://github.com/ozone-development/ozp-webtop/issues/649)

### Backend:
* init.d scripts for nginx, postgresql, gunicorn
* integration with real authorization service and PKI
* vagrant box with production-esque setup
* run database migration script on production data
* begin setting up staging/production infrastructure for new backend

### 508 
* List of specific 508 compliance items 
 * 
 *
* Process and configuration for 508 VM and Branches 

### IWC
* Documentation
    * Tutorials: advanced functionality (pattern filtering, intents)
    * Tutorials: Location Lister end to end tutorial.
    * Gitbook: Metrics on supported browser performance.
    * Examples: layout and fill the examples page of the iwc gh-pages to show source/example side by side.
* Review IWC Client method signatures, determine if there is a more intuitive function signature we could utilize. (ex. a data api set looks like `client.data().set(resource,{entity: .... })`).

### Metrics
* Continue work on automated export of metrics data

### UI/UX
* Implement light-themed modals throughout the entire platform (Webtop/HUD)
* Clean up PRs for help/documentation updates supporting upcoming features
* Support help tour development
* Support graphic needs for structure diagram
* Support ongoing development / bugs / etc

### NC
* Transition - See roadblocks
* If Community responds in time we will release OMP
  
## Roadblocks
* transition of OWF/OMP support 