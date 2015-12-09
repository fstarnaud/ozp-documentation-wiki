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
  * Automated regression testing with CasperJS

* Help Articles:
 * ~~Fix IE URL Length Bug~~
 * ~~Add auth to related articles.~~
 * ~~Change related articles to 6 articles~~ 

* Help Tour:
 * Investigate further functionality for launching modals, dropdowns, etc. 
 * ~~Testing and exploring options for Help Tour~~
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
* Improve accessibility for (Center, HUD, Webtop)
* List of specific 508 compliance items currently working on
   * Center - Fix all the empty links and empty button text links within each app on the front page
   * ~~Center - Fix the buttons and tabs in each app popup modal [#450] https://github.com/ozone-development/ozp-center/issues/450~~
* Process and configuration for 508 VM and Branches 

### IWC
* ~~Documentation~~
    * ~~Tutorials: How to structure resource paths~~
    * ~~Tutorials: advanced functionality (pattern filtering~~, intents ~~)~~ **Intents tutorials are near completion. Completed tutorials are on gh-pages**
    * Tutorials: Location Lister end to end tutorial.
    * ~~Examples: layout and fill the examples page of the iwc gh-pages to show source/example side by side.~~
* General Code maintenance:
    * Review IWC Client method signatures, determine if there is a more intuitive function signature we could utilize. [#362](https://github.com/ozone-development/ozp-iwc/issues/362) [#361](https://github.com/ozone-development/ozp-iwc/issues/361). **Does not impact performance, just future vision for syntax of IWC.**
    * ~~IWC initial delay on newer browsers is unneeded [#364](https://github.com/ozone-development/ozp-iwc/issues/364)~~ **Issue remains open for aid on speeding up delay on older browsers (fine tuning).**

### Metrics
* Continue work on automated export of metrics data

### UI/UX
* ~~Implement light-themed modals throughout the entire platform (Webtop/HUD)~~
* ~~Provide mockups and direction for [Private Listings](https://github.com/ozone-development/ozp-center/issues/447)~~
* ~~Discussion of [Security Markings](https://github.com/ozone-development/ozp-center/issues/448)~~
* ~~Provide styling/layout/branding updates for IWC site~~
* ~~Support graphic needs for structure diagram~~
* ~~Support help tour development~~

### NC
* Transition - See roadblocks
* If Community responds in time we will release OMP
  
## Roadblocks
* transition of OWF/OMP support 