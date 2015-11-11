# Iteration 36 (28 Oct -  11 Nov)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* ~~Help Articles~~

## Iteration Goals:
* ~~IWC working with new backend~~
* ~~Lowside PKI infrastructure for new backend~~
* ~~Continue new backend testing with center, hud, webtop, and iwc~~

### Center / Help Articles
* Center:
  * Integrate Help Tour
  * Eliminate warnings to improve reliability/stability and to prepare for updating React to latest version [#423](https://github.com/ozone-development/ozp-center/issues/423)
* ~~Help Articles:~~
 * ~~Integration Styling~~
* Help Tour:
 * Investigate further functionality for launching modals, dropdowns, etc. 
 * Testing and exploring options for Help Tour
 * Clean up tour links/paths to bake in react actions
 * Set tour to open on first visit to Ozone

### Backend (new):
* Django
  * ~~Add PKI support~~
  * ~~Add authorization service support~~
* Center

### Webtop / HUD
* change widget app-toolbar clicking behavior [webtop #596](https://github.com/ozone-development/ozp-webtop/issues/596)
* add max dashboard error when launching folder from hud [webtop #642](https://github.com/ozone-development/ozp-webtop/issues/642)
* various webtop bugs/issues [webtop #621](https://github.com/ozone-development/ozp-webtop/issues/621), [webtop #644](https://github.com/ozone-development/ozp-webtop/issues/644)
* configure publicly accessible webtop / hud demos in openshift accessing new backend

### 508 
* Improve accessibility for (Center, HUD, Webtop)
* List of specific 508 compliance items currently working on
    * ~~Center - The form shall allow people using assistive technology (ie. JAWS) to access the information, field elements, and functionality required for completion and submission of the form. [#371] (https://github.com/ozone-development/ozp-center/issues/371)~~
   * Center - Fix the Bookmark this app button if its not bookmark

* HUD - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#127] (https://github.com/ozone-development/ozp-hud/issues/127)


### IWC/Legacy Adapter
* New Backend
    * Intents.api endpoint support
    * Code Review & Testing against both Current & New Backend
* Performance evaluations
    * Investigate utilization of a shared IWC bus for multiple IWC clients in one browser window chain #328
    * Investigate additional Transport Links (other than localStorage) to broaden browser support.
* Documentation
    * Additional OWF7 to IWC migration guides for application developers.
    * Add metrics (document) on performance gains of web worker to docs.


### Metrics
* Decision on whats next for CSV export of metrics data

### UI/UX
* ~~Support help tour development~~
* ~~Provide mockups for settings modal solution [#356](https://github.com/ozone-development/ozp-center/issues/356)~~
* ~~Support ongoing development / bugs / etc~~


### NC
* ~~Continue supporting testing efforts~~
* Java 8 Support for OMP
* ~~Fix Grails issue with OWF 7.17.0~~
* Continue update of documentation with new features
  
## Roadblocks
* transition of OWF support