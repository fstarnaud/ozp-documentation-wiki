## Iteration 13 & 14 (10 Dec 2014 - 07 Jan 2015)

***

### Next Milestone:
21 Jan 2015 - Deploy IOB features to production servers

Minimal delivered set of features
* Deployment package for OZP
* IOB Features for Center/HUD, Webtop, Backend, IWC, Metrics
* PKI Login
* Application data migration script from 7.16 store
* Working Backend
* OWF 7 Adapter

***

### Iteration Goals:
**Center/HUD -**
* 

**Backend -**
* *Note: Ross' availability over next few sprints is uncertain*
* Finish Image Server
* Add simple no-cache headers to fix IE problems
* Document Listing JSON representations
* Implementation Security Plugin
 * Get new code high-side
 * Initial merge of implementation-specific code with new code

**Webtop -**
* Update 'sticky' dashboard logic as per [#353](https://huboard.com/ozone-development/ozp-webtop#/issues/51341875)
* Update to latest ozp-bootstrap and global toolbar markup
* Numerous issues such as:
  * [#355](https://github.com/ozone-development/ozp-webtop/issues/355)
  * [#354](https://github.com/ozone-development/ozp-webtop/issues/354)
  * [#341](https://github.com/ozone-development/ozp-webtop/issues/341)

**IWC -**
* Bug fixes
    * [Create/Delete localstorage key on Firefox 17 (potentially other browsers) doesn't generate an event](https://github.com/ozone-development/ozp-iwc/issues/123) **Blocking v0.1**
    
* Technical Debt **v0.2**
    * Client library cleanup.
    * REST Normalization/Refactor
    * Legacy Widget Adapter
    * IWC ABAC standards
    * IWC in-browser ABAC implementation


* Guides
    * Integration Guide v2
    * Application Guide v2

**Metrics -**
* 

**UI/UX -**
* Develop a Piwik Theme for AML Metrics
* Continue refining Bootstrap as it is integrated
* Waiting on research 
* Waiting on global toolbar integration 
* Waiting on webtop toolbar integration 

***

**Roadblocks:**
* IWC and Firefox issue
* Integration of Common Toolbar across platform

***