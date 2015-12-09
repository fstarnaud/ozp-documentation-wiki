# Iteration 39 (9 Dec - 23 Dec)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* Dec 2015 - backend alpha in staging  

## Iteration Goals:
* Continue new backend testing with center, hud, webtop, and iwc

### Front End (Center, HUD, Webtop)

* Center:
  * Open Search
  * Help Tour Integration

* Help Tour:
 * Investigate further functionality for launching modals, dropdowns, etc. 
 * Set tour to open on first visit to Ozone

* Webtop
 * Investigate ability to display a message when apps can not be displayed in the webtop  [#649](https://github.com/ozone-development/ozp-webtop/issues/649)

### Backend:
* 

### 508 
* Improve accessibility for (Center, HUD, Webtop)
*  

### IWC
* Documentation
    * Tutorials: Intent invoking. Intent responses.
    * Tutorials: Location Lister end to end tutorial.
    * Examples: Intent application example.
* General Code maintenance:
    * Review IWC Client method signatures, determine if there is a more intuitive function signature we could utilize. [#362](https://github.com/ozone-development/ozp-iwc/issues/362) [#361](https://github.com/ozone-development/ozp-iwc/issues/361). **Does not impact performance, just future vision for syntax of IWC.**
    * Intents: an intent invocation should return a result to the invoker if possible (remote function call & return) [#368](https://github.com/ozone-development/ozp-iwc/issues/368)

### Metrics
* Investigate ability to change metrics search results from case sensitive to not case sensitive. Currently "map" and "MAP" and "Map" are logged as different search terms

### UI/UX
* Provide general support for development/bugs
* Support graphic needs for structure diagram
* Continue styling support as needed for help tour development


## Roadblocks
* 