# Iteration 35 (14 Oct - 28 Oct)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* Help Articles

## Iteration Goals:
*  ~~Functional Center, HUD, and Webtop in new backend (dev env)~~ (everything but IWC)
*  ~~Improved CI setup (reduce build times and failures on Jenkins)~~
  * No random build failures since last week (typically they were failing about 30% of the time)
  * Build and Deployment time: reduced from ~30 minutes to ~6 minutes (for Center, our largest project)

### Center / Help Articles
* Center
  * add opensearch capabilities
  * configure publicly accessible demo in openshift accessing new backend
  * refactor listings management pages and table view and add export to excel feature to table view
  * ~~Fix Create/Edit Page - Contact mislabeled after Save [#267](https://github.com/ozone-development/ozp-center/issues/267)~~
* Help Articles:
  * ~~Role based article displays [#39](https://github.com/ozone-development/ozp-help/issues/39)~~
* Help Tour:
  * Testing and exploring options for Help Tour
  * Clean up tour links/paths to bake in react actions
  * Set tour to open on first visit to Ozone

### Backend (new):
* Continued testing
* Center Changes:
  * Center Settings:
    * ~~Stewards [#28](https://github.com/ozone-development/ozp-backend/issues/28)~~
    * ~~Intents [#26](https://github.com/ozone-development/ozp-backend/issues/26)~~
* Webtop Changes:
  * ~~Use new backend API~~

### Webtop / HUD
* change widget app-toolbar clicking behavior [webtop #596](https://github.com/ozone-development/ozp-webtop/issues/596)
* ~~switch webtop from less to sass [webtop #638](https://github.com/ozone-development/ozp-webtop/issues/638) ~~
* add max dashboard error when launching folder from hud [webtop #642](https://github.com/ozone-development/ozp-webtop/issues/642)
* various webtop bugs/issues [webtop #621](https://github.com/ozone-development/ozp-webtop/issues/621), [webtop #644](https://github.com/ozone-development/ozp-webtop/issues/644)
* configure publicly accessible webtop / hud demos in openshift accessing new backend

### 508
* Demo Free 508 Compliance Tools we are using 
* Improve accessibility for (Center, HUD, Webtop)
* List of specific 508 compliance items currently working on
    * Center - The form shall allow people using assistive technology (ie. JAWS) to access the information, field elements, and functionality required for completion and submission of the form. [#371] (https://github.com/ozone-development/ozp-center/issues/371)
    * Center - Navigation in center needs to work in (Jaw) ie. Help, and Menu (dropdown)
[#392] (https://github.com/ozone-development/ozp-center/issues/392)

* HUD - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#127] (https://github.com/ozone-development/ozp-hud/issues/127)

* Attend meeting with 508 compliance to make sure we are on the right track
  
### IWC/Legacy Adapter
* ~~Code review~~
   * ~~Review/Testing of shared web worker IWC Bus.~~
* New Backend endpoint support
   * ~~Data.api endpoint support~~
   * ~~System.api endpoint support~~
   * Intents.api endpoint support
* Debugger
   * ~~Create A Debugger client for wider debugging capabilities and custom debugging tools [#336](https://github.com/ozone-development/ozp-iwc/pull/336)~~
* Legacy Adapter
   * ~~Update to be compliant with IWC 1.1.x [#38](https://github.com/ozone-development/ozp-iwc-owf7-widget-adapter/pull/38)~~
   * ~~Bug causing legacy widgets to break when launching [#40](https://github.com/ozone-development/ozp-iwc-owf7-widget-adapter/pull/40)~~
* Bug fixes
   * ~~Simplified Launch data passing [#334](https://github.com/ozone-development/ozp-iwc/pull/344)~~
   * ~~Shared Worker loader bus gathering URL fix [#339](https://github.com/ozone-development/ozp-iwc/pull/339)~~
   * ~~IE 11 opens prompt on page leave [#347](https://github.com/ozone-development/ozp-iwc/issues/347)~~
* Performance evaluations
   * Investigate utilization of a shared IWC bus for multiple IWC clients in one browser window chain #328
   * Investigate additional Transport Links (other than localStorage) to broaden browser support.
* Documentation
   * Additional OWF7 to IWC migration guides for application developers.

### Metrics
* ~~Output metrics export into table form/CSV~~

### UI/UX
* ~~Provide mockups for settings modal solution [#356](https://github.com/ozone-development/ozp-center/issues/356)~~
* ~~Support ongoing development / bugs / etc~~

### NC
* Continue supporting testing efforts
* Java 8 Support for OMP
* Continue update of documentation with new features
* ~~Finish refactoring table-view to use W2UI~~
* ~~Export to csv for Table View~~
  
## Roadblocks
* meeting to discuss new back end infrastructure
* transition of OWF support to...