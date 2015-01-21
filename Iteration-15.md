## Iteration 15 (07 Jan 2015 - 21 Jan 2015)

***

### Next Milestone:
21 Jan 2015 - Deploy IOB features to production servers

Minimal delivered set of features
* PKI Login
* Application data migration script from 7.16 store
* Deployment package for OZP
* IOB Features for Center/HUD, Webtop, Backend, IWC, Metrics
* Working Backend
* OWF 7 Adapter
* Basic Metrics 

***

### Iteration Goals:
**Center/HUD -**
* ~~Org Steward Listing Management~~
* Reviews on Detailed View
* ~~Unified Toolbar (HUD)~~
* ~~Image Server Uploads for Listings~~
* ~~Add temporary banners to center~~

**Backend -**
* ~~Notifications design spike~~
* ~~Security Plugin Development~~
* ~~Create Public URI configuration~~

**Webtop -**
* ~~Make the IWC bus configurable [#371](https://github.com/ozone-development/ozp-webtop/issues/371)~~
* Set the URLs for HUD, Center, and Webtop correctly in the ozp-common-toolbar (or use Intents) [#372](https://github.com/ozone-development/ozp-webtop/issues/372) - TBD: Do we treat Center, HUD, Webtop as POLOs (Plain Old Listing Objects) or not?
* ~~Make BasicAuth credentials configurable [#373](https://github.com/ozone-development/ozp-webtop/issues/373)~~
* Update to latest ozp-bootstrap [#366](https://github.com/ozone-development/ozp-webtop/issues/366)
* ~~Z-index bug in Desktop layout [#341](https://github.com/ozone-development/ozp-webtop/issues/341)~~
~~* Prevent scrolling in desktop layout [#343](https://github.com/ozone-development/ozp-webtop/issues/343)~~
* ~~Disable classification banners in gh pages [#367](https://github.com/ozone-development/ozp-webtop/issues/367)~~

**IWC -**
* Initial implementation of ABAC
* Begin legacy widget adapter

**Metrics -**
* ~~Ensure proper metrics are being collected and reported correctly~~
* ~~Meeting with stakeholders~~ 
* ~~Discussion with Center on how immediate search reacts~~ 

**UI/UX -**
* ~~Continue refining Bootstrap / Piwik as it is integrated~~
* ~~Provide feedback on current page iterations~~
* Roadblocks:
  * Waiting on research 
  * Waiting on global toolbar integration 
  * Waiting on webtop toolbar integration 

***

**Roadblocks:**
* ~~Remove hard coded links in all products that are being deployed~~
* Integration of Common Toolbar across platform for Center ( This will happen after IOB)
* ~~Need SA to attend Iteration Planning~~
* Additional VM's
* ~~SSL configuration Discussion~~
* IWC support for Basic Authentication credentials in the iwcClient
* ~~Tester needed~~


***