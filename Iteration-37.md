# Iteration 37 (11 Nov -   25 Nov)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* Dec 2015 - backend alpha in staging  
* Help Articles deployed to production

## Iteration Goals:
* Continue new backend testing with center, hud, webtop, and iwc
* ~~Begin investigation on performance testing of new backend~~
* ~~Database work for new backend~~

### Center
* Center:
  * Open Search

* Help Articles: 
  * ~~Integrate roles across all applications.~~
  * ~~Create config file for videos.~~

* Help Tour:
 * Investigate further functionality for launching modals, dropdowns, etc. 
 * Testing and exploring options for Help Tour
 * Clean up tour links/paths to bake in react actions
 * Set tour to open on first visit to Ozone

### Backend (new):

* Release Management
  * ~~Establish and configure Staging env (PostgreSQL, Nginx)~~
  * ~~Begin to work data migration script (moving existing data to new backend)~~
  * Test process for database migrations (for when new backend is in place)
  * Begin to update puppet scripts
  * Performance testing


### 508 
* Improve accessibility for (Center, HUD, Webtop)
* List of specific 508 compliance items currently working on

   * ~~Center - Fix the Bookmark this app button if its not bookmark [#396] (https://github.com/ozone-development/ozp-center/issues/396)~~
   * ~~Center - Fix the Listing Type and Organizations dropdown on home page [#436] (https://github.com/ozone-development/ozp-center/issues/436)~~
* Process and configuration for 508 VM and Branches 

* HUD - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#127] (https://github.com/ozone-development/ozp-hud/issues/127)
  
### IWC
* Code Maintenance
    * ~~Restructure of IWC classes for easier developer onboarding.~~
* Documentation
    * Additional OWF7 to IWC migration guides for application developers.
    * ~~Add metrics (document) on performance gains of web worker to docs.~~
    * ~~gh-pages~~
        * ~~tutorials: create tutorial(s) for step-by-step walkthrough of example widget creation.~~
        * examples: create an examples page(s) to better showcase the IWC capabilities (display example and explanation of functionality used)


### Metrics
* ~~Get feedback from regarding metrics export options~~
 * ~~simple url with data parameters?~~
 * ~~web based data selected and button to export?~~

### UI/UX
* ~~Support ongoing development / bugs / etc~~
* ~~Final help article styling and layout~~
* ~~Digitize structure diagram~~
* ~~Clean up highlevel backlog to update UX direction based on current team discussions~~
* ~~Create tickets, descriptions, and mockups as needed to support implementation of [#287](https://github.com/ozone-development/ozp-center/issues/287) / [#356](https://github.com/ozone-development/ozp-center/issues/356) decision~~
  * ~~remove the ability to open apps from HUD into Webtop (currently broken) / setting to change default launch / launch options [#143](https://github.com/ozone-development/ozp-hud/issues/143)~~
  * ~~remove Webtop-disabled apps from Webtop [#651](https://github.com/ozone-development/ozp-webtop/issues/651) / implement folder display [#652](https://github.com/ozone-development/ozp-webtop/issues/652)~~
  * ~~remove the setting modal on the global menu [hud #142](https://github.com/ozone-development/ozp-hud/issues/142) / [center #438](https://github.com/ozone-development/ozp-center/issues/438) / [webtop #648](https://github.com/ozone-development/ozp-webtop/issues/648)~~
  * ~~add Webtop-enabled setting to all apps / UI opt-in to submission form [#287](https://github.com/ozone-development/ozp-center/issues/287)~~
  * ~~create a notification when user sends a shared folder / bookmark to a new folder on HUD when the receiving user accepts [#137](https://github.com/ozone-development/ozp-hud/issues/137)~~

### NC
* ~~Continue supporting testing efforts~~
* ~~Java 8 Support for OMP~~ Released as BETA
* ~~OWF 7.17.0 was Released~~
* ~~Continue update of documentation with new features~~
  
## Roadblocks
* transition of OWF support