## Iteration 11 (12 Nov 2014 -  26 Nov 2014)

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
* ~~Implement Help Modal~~
* ~~Allow QuickView to open from other routes. (Refactor Modal routing)~~
* Listings Management View for AppsMall Admins.
* ~~Implement Draft listings.~~
* ~~How do we handle logout?~~
* ~~Setup Unit Testing/Documentation.~~

**Backend -**
* ~~Implement Org Steward approval workflow~~
* ~~Roles for Steward~~
* ~~Investigate the Security Solution for the Implementation~~ (Investigation complete - actual development in progress)

**Webtop -**
* ~~Address multiple webtop instances issue ([#328](https://github.com/ozone-development/ozp-webtop/issues/328))~~ (keeping ticket around, but will delay official support for multiple webtop instances until a later time)
* Bug fixes and enhancements to Desktop layout (carrying over to next iteration)
* ~~Enable OZP Bootstrap fork~~
* ~~App toolbar enhancements (e.g. [#311](https://github.com/ozone-development/ozp-webtop/issues/311))~~
* Handle Launch Application intent ([#187](https://github.com/ozone-development/ozp-webtop/issues/187)) (this work was sidelined in favor of [#133](https://github.com/ozone-development/ozp-webtop/issues/133)
* Work with Rob on the test plan (carrying over to next iteration)
* ~~Standard testing and bug fixes~~

**IWC -**
* ~~Technical Debt ([integration](https://github.com/ozone-development/ozp-iwc/wiki/IWC-Backend-Integration) [application](https://github.com/ozone-development/ozp-iwc/wiki/IWC-App-Integration) [#146](https://github.com/ozone-development/ozp-iwc/pull/146) [#151](https://github.com/ozone-development/ozp-iwc/pull/151) [#156](https://github.com/ozone-development/ozp-iwc/pull/156))~~(ongoing)
* ~~Review public interface~~
  * ~~Mock data([built simple CRUD data.api backend for testing/example](https://github.com/ozone-development/ozp-iwc-integrationDemo))~~
  * ~~Content types ([#150](https://github.com/ozone-development/ozp-iwc/pull/150))~~
* ~~Integration guide~~ ([v1](https://github.com/ozone-development/ozp-iwc/wiki/IWC-Backend-Integration))
* ~~Bug fixes ([#153](https://github.com/ozone-development/ozp-iwc/issues/153))~~ (ongoing)
* ~~Add Grunt release ([#147](https://github.com/ozone-development/ozp-iwc/issues/147))~~
* IWC v0.1.0
* Scope legacy widget adapter
* Talking points for why IWC is different the standard HTML5

**Metrics -**
* Open up public endpoint to Piwik interface
* Roll metrics changes into center-ui branches

**UI/UX -**
* ~~Clean up OZP Bootstrap repo~~
* ~~Refactor OZP toolbar HTML to work with OZP Bootstrap repo~~

***

**Roadblocks:**
* VM's for metrics
* Mock Govport services
* Integration of Common Toolbar across platform
* How to handle multiple tabs/windows in IWC-enabled applications (multiple webtop windows, logout functionality, etc)
* IWC and Firefox issue

***