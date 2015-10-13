# Iteration 34 (30 Sept - 14 Oct)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* Interactive Help

## Iteration Goals:
* ~~Final verification on Table View feature (Center)~~
* Functional Center, HUD, and Webtop in new backend (dev env)
* Updated Help Modal deployed to staging

### Center / Interactive Help
* Center:
  * ~~Merge Table View~~
* Interactive Help:
  * Role based article displays [#39](https://github.com/ozone-development/ozp-help/issues/39)
  * Update deployment scripts/configuration to deploy to staging

### Backend (new):
* system.api and intents.api endpoint support
* Preliminary Center testing
* Bug fixes
* Center Changes:
  * Center Settings:
    * Notifications [#29](https://github.com/ozone-development/ozp-backend/issues/29)
    * Stewards [#28](https://github.com/ozone-development/ozp-backend/issues/28)
    * Intents [#26](https://github.com/ozone-development/ozp-backend/issues/26)

### Webtop / HUD
* change widget app-toolbar clicking behavior [webtop #596](https://github.com/ozone-development/ozp-webtop/issues/596)
* switch webtop from less to sass [webtop #638](https://github.com/ozone-development/ozp-webtop/issues/638)
* various webtop bugs [webtop #621](https://github.com/ozone-development/ozp-webtop/issues/621), [webtop #508](https://github.com/ozone-development/ozp-webtop/issues/508)

### 508
* Improve accessibility for (Center, HUD, Webtop)

  * List of specific 508 compliance items currently working on
    * Center - The form shall allow people using assistive technology (ie. JAWS) to access the information, field elements, and functionality required for completion and submission of the form. [#371] (https://github.com/ozone-development/ozp-center/issues/371)
    * Center - Navigation in center needs to work in (Jaw) ie. Bookmark, launch, Help, and Menu (dropdown)
[#392] (https://github.com/ozone-development/ozp-center/issues/392)

* HUD - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#127] (https://github.com/ozone-development/ozp-hud/issues/127)


### IWC/Legacy Adapter
* Performance evaluations
    * Investigate utilization of a shared IWC bus for multiple IWC clients in one browser window chain [#328](https://github.com/ozone-development/ozp-iwc/issues/328)
    * Investigate using shared webworkers (consensus algorithms would be fallback) [#330](https://github.com/ozone-development/ozp-iwc/issues/330)
    * Investigate using message channels for client-> bus communication (postMessage as fallback) [#333](https://github.com/ozone-development/ozp-iwc/issues/330)
    * Investigate additional Transport Links (other than localStorage) to broaden browser support.
* Documentation
    * Additional OWF7 to IWC migration guides for application developers.

### Metrics
* Clarify exact metric reports that need to be automated

### UI/UX
* ~~Convert LESS to SASS via docker~~
* ~~Initial research/styling/drafting for tour~~
* ~~Discussion/mockups for global Settings modal~~
* ~~Support ongoing development / bugs / etc~~

### NC
* Continue supporting testing efforts
* Java 8 Support for OMP
* Continue update of documentation with new features
  * list of docs that were completed and what is still in progress
  
## Roadblocks
* meeting to discuss new back end infrastructure
* ~~setup meeting with 508 compliance to make sure we are on the right track~~
* SASS vs LESS discussion/decision 