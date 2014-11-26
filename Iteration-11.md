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
* ~Implement Help Modal~
* ~Allow QuickView to open from other routes. (Refactor Modal routing)~
* Listings Management View for AppsMall Admins.
* ~Implement Draft listings.~
* ~How do we handle logout?~
* ~Setup Unit Testing/Documentation.~

**Backend -**
* Implement Org Steward approval workflow
* Roles for Steward
* Investigate the Security Solution for the Implementation

**Webtop -**
* ~~Address multiple webtop instances issue ([#328](https://github.com/ozone-development/ozp-webtop/issues/328))~~ (keeping ticket around, but will delay official support for multiple webtop instances until a later time)
* Bug fixes and enhancements to Desktop layout (carrying over to next iteration)
* ~~Enable OZP Bootstrap fork~~
* ~~App toolbar enhancements (e.g. [#311](https://github.com/ozone-development/ozp-webtop/issues/311))~~
* Handle Launch Application intent ([#187](https://github.com/ozone-development/ozp-webtop/issues/187)) (this work was sidelined in favor of [#133](https://github.com/ozone-development/ozp-webtop/issues/133)
* Work with Rob on the test plan (carrying over to next iteration)
* ~~Standard testing and bug fixes~~

**IWC -**
* Technical Debt
* Review public interface
  * Mock data
  * Content types
* Integration guide
* Bug fixes
* ~~Add Grunt release~~
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