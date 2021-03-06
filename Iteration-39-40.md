# Iteration 39 & 40(9 Dec - 06 Jan)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* ~~Dec 2015 - backend alpha in staging~~

## Iteration Goals:
* ~~Continue new backend testing with center, hud, webtop, and iwc~~

### Front End (Center, HUD, Webtop)

* Center:
  * Open Search
  * Help Tour Integration
  * New backend: implement private listings [#447](https://github.com/ozone-development/ozp-center/issues/447)
  * New backend: Add security marking to listings and associated image files [#448](https://github.com/ozone-development/ozp-center/issues/448)


* Help Tour:
 * Close help modal on tour start
 * Fix tourstops inside modals
 * Separate global tour from each individual tour - chain tours together depending where user started
 * Set tour to open welcome tourstop on first visit to Ozone

* Webtop
 * ~~Investigate ability to display a message when apps can not be displayed in the webtop  [#649](https://github.com/ozone-development/ozp-webtop/issues/649)~~

### Backend:
* ~~run database migration script on production data~~
* ~~begin setting up staging/production infrastructure for new backend~~
* vagrant box with production-esque setup (not priority) (in progress)

### 508 
* Improve accessibility for (Center, HUD, Webtop)
* List of specific 508 compliance items currently working on
   * ~~Center - Fix all the empty links and empty button text links within each app on the front page~~
   * Center - Fix the top two carousel 
* ~~Process and configuration for 508 VM and Branches~~ 
* Review 508 wiki with compliance office

### IWC
* Documentation
    * ~~Tutorials: Intent invoking. Intent responses.~~
    * Tutorials: Location Lister end to end tutorial.
    * ~~Examples: Intent application example.~~
* General Code maintenance:
    * ~~Review IWC Client method signatures, determine if there is a more intuitive function signature we could utilize. [#362](https://github.com/ozone-development/ozp-iwc/issues/362) [#361](https://github.com/ozone-development/ozp-iwc/issues/361). **Does not impact performance, just future vision for syntax of IWC.**~~ **In Review.**
    * ~~Intents: an intent invocation should return a result to the invoker if possible (remote function call & return) [#368](https://github.com/ozone-development/ozp-iwc/issues/368)~~

### Metrics
* Investigate ability to change metrics search results from case sensitive to not case sensitive. Currently "map" and "MAP" and "Map" are logged as different search terms

### UI/UX
* ~~General support for development/bugs/decisions~~
* ~~Structure diagram graphic~~
* ~~Make help articles/images more generic for use in AML~~
* ~~Fix help article bugs, switch images to icons wherever possible~~
* ~~Styling/content support for help tour~~
* ~~Styling support for bootstrap-classify~~
* ~~Discussion regarding filtering search for people who don't want Code Libraries~~ 

## Roadblocks
* ~~availability of Bootstrap classify~~
* ~~discussion on adding IWC to allow webtop/hud/center to talk (tour)~~