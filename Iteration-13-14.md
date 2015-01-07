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
* ~~Add unit tests for All AML Listings page~~
* ~~Add Required links and options to Marketplace Drop-Down~~

**Backend -**
* *Note: Ross' availability over next few sprints is uncertain*
* ~~Finish Image Server~~
* ~~Add simple no-cache headers to fix IE problems~~
* ~~Document Listing JSON representations~~
* Implementation Security Plugin
 * ~~Get new code to implementation network~~
 * ~~Initial merge of implementation-specific code with new code~~

**Webtop -**
* ~~Update 'sticky' dashboard logic as per [#353](https://huboard.com/ozone-development/ozp-webtop#/issues/51341875)~~
* Update to latest ozp-bootstrap and global toolbar markup
* Numerous issues such as:
  * ~~[#355](https://github.com/ozone-development/ozp-webtop/issues/355)~~
  * ~~[#354](https://github.com/ozone-development/ozp-webtop/issues/354)~~
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
* ~~Complete PKI login to metrics interface~~
* ~~Deploy metrics UI enhancements~~

**UI/UX -**
* ~~Develop a Piwik Theme for AML Metrics~~
* ~~Continue refining Bootstrap as it is integrated~~
* ~~Meet to determine IWC UI needs~~
* ~~Provide documentation for AML icon font~~
* ~~Meet with ADG to review UX/UI recommendations~~
* ~~Provide select mockups to visualize recommendations~~
* Roadblocks:
  * Waiting on research 
  * Waiting on global toolbar integration 
  * Waiting on webtop toolbar integration 

***

**Roadblocks:**
* Remove hard coded links in all products that are being deployed
* ~~IWC and Firefox issue~~
* Integration of Common Toolbar across platform
* Need SA to attend Iteration Planning
* Metrics on standards port
* Additional VM's
* ~~Expiring domain names~~

***