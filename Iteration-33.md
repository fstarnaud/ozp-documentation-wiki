# Iteration 33 (16 Sept 2015 - 30 Sept)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* Interactive Help
* Shared folders in HUD

## Iteration Goals:
* Review pull request for table listing view
* Support IWC in new backend


### NC
* Continue supporting testing efforts
* ~~Java 8 Support for OWF - Testing and Release~~
* Java 8 Support for OMP - potentially based on PMO approval
* Continue update of documentation with new features

### Center / Interactive Help
* Backend changes (See Backend)

### Backend (new)
* Implement HATEOAS endpoints for IWC support (system.api, data.api, and intents.api)
* Hookup Center Listing Management endpoints [#30](https://github.com/ozone-development/ozp-backend/issues/30)
* Hookup Center Create/Edit Listing endpoints [#32](https://github.com/ozone-development/ozp-backend/issues/32)
* Hookup quickview administration endpoints [#23](https://github.com/ozone-development/ozp-backend/issues/23)
* Hookup settings [#24](https://github.com/ozone-development/ozp-backend/issues/24), [#25](https://github.com/ozone-development/ozp-backend/issues/25), [#26](https://github.com/ozone-development/ozp-backend/issues/26), [#27](https://github.com/ozone-development/ozp-backend/issues/27), [#28](https://github.com/ozone-development/ozp-backend/issues/28), [#29](https://github.com/ozone-development/ozp-backend/issues/29)

* Center Changes Changes:
  * Center Settings:
    * ~~Categories [#27](https://github.com/ozone-development/ozp-backend/issues/27)~~
    * ~~Contact Types [#25](https://github.com/ozone-development/ozp-backend/issues/25)~~
    * Stewards [#28](https://github.com/ozone-development/ozp-backend/issues/28)
    * Intents [26](https://github.com/ozone-development/ozp-backend/issues/26)

### Webtop / HUD
* share folder modal [hud #123](https://github.com/ozone-development/ozp-hud/issues/123)
* ie folder bug(s) [hud #125](https://github.com/ozone-development/ozp-hud/issues/125)
* webtop style items
  * ~~update app chrome [webtop #595](https://github.com/ozone-development/ozp-webtop/issues/595)~~
  * ~~update to latest ozp-bootstrap [webtop #632](https://github.com/ozone-development/ozp-webtop/issues/632)~~
  * change widget app-toolbar clicking behavior [webtop #596](https://github.com/ozone-development/ozp-webtop/issues/596)
* next century - add contact modal [webtop #635](https://github.com/ozone-development/ozp-webtop/issues/635), [hud #126](https://github.com/ozone-development/ozp-hud/issues/126)

### 508
* Improve accessibility for (Center, HUD, Webtop)

  * List of specific 508 compliance items currently working on
    * Center - The form shall allow people using assistive technology (ie. JAWS) to access the information, field elements, and functionality required for completion and submission of the form. [#371] (https://github.com/ozone-development/ozp-center/issues/371)
    * Center - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#370] (https://github.com/ozone-development/ozp-center/issues/370)

* HUD - Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as speech. [#127] (https://github.com/ozone-development/ozp-hud/issues/127)

### IWC/Legacy Adapter
* Legacy Adapter support to users
* Debugger documentation
* Modular restructure (move functionality not needed by developers from public to private methods)
* Legacy Backend endpoints (widget listing endpoints & /metrics)

### Metrics
* ~~Investigate automating export of specific report data to csv/excel~~
* ~~Track when app is launched in a new tab or webtop~~

### UI/UX
* ~~Support ongoing development~~
* ~~Set up docker for LESS>SASS conversion~~
* ~~Remove HUD override CSS~~
* ~~Fix responsive merge issues on new Listings Management Table View PR / HUD PR~~
* ~~Support ozp-help styling / bug fixes~~
* ~~Support styling/content updates on ozone marketing website~~
  
## Roadblocks