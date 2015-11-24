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
  * Integrate roles across all applications.
  * Create config file for videos.

* Help Tour:
 * Investigate further functionality for launching modals, dropdowns, etc. 
 * Testing and exploring options for Help Tour
 * Clean up tour links/paths to bake in react actions
 * Set tour to open on first visit to Ozone

### Backend (new):

* Release Management
  * Establish and configure Staging env (PostgreSQL, Nginx)
  * Begin to work data migration script (moving existing data to new backend)
  * Test process for database migrations (for when new backend is in place)
  * Begin to update puppet scripts
  * Performance testing


### 508 
* Improve accessibility for (Center, HUD, Webtop)
* List of specific 508 compliance items currently working on

   * Center - Fix the Bookmark this app button if its not bookmark [#396] (https://github.com/ozone-development/ozp-center/issues/396)
   * ~~Center - Fix the Listing Type and Organizations dropdown on home page [#436] (https://github.com/ozone-development/ozp-center/issues/436)~~
* Process and configuration for 508 VM and Branches 

* HUD - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#127] (https://github.com/ozone-development/ozp-hud/issues/127)
  
### IWC
* Code Maintenance
    * ~~Restructure of IWC classes for easier developer onboarding.~~
* Documentation
    * Additional OWF7 to IWC migration guides for application developers.
    * Add metrics (document) on performance gains of web worker to docs.
    * ~~gh-pages~~
        * ~~tutorials: create tutorial(s) for step-by-step walkthrough of example widget creation.~~
        * examples: create an examples page(s) to better showcase the IWC capabilities (display example and explanation of functionality used)


### Metrics
* ~~Get feedback from regarding metrics export options~~
 * ~~simple url with data parameters?~~
 * ~~web based data selected and button to export?~~

### UI/UX
* ~~Support ongoing development / bugs / etc~~
* Final help article styling and layout
* Support help tour development
* Digitize structure diagram
* ~~Support implementation of [#287](https://github.com/ozone-development/ozp-center/issues/287) / [#356](https://github.com/ozone-development/ozp-center/issues/356)~~
  * ~~removing the ability to open apps from HUD into Webtop (currently broken)~~
  * ~~removing the setting to change the default launch (currently in the setting modal)~~
  * ~~removing the setting modal on the global menu~~

### NC
* ~~Continue supporting testing efforts~~
* ~~Java 8 Support for OMP~~ Released as BETA
* ~~OWF 7.17.0 was Released~~
* ~~Continue update of documentation with new features~~
  
## Roadblocks
* transition of OWF support