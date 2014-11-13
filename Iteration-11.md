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
* Implement Help Modal
* Allow QuickView to open from other routes. (Refactor Modal routing)
* Listings Management View for AppsMall Stewards.
* Implement Draft listings.
* How do we handle logout?
* Unit Testing/Documentation.

**Backend -**
* Implement Org Steward approval workflow
* Roles for Steward
* Investigate the Security Solution for the Implementation

**Webtop -**
* Address multiple webtop instances issue ([#328](https://github.com/ozone-development/ozp-webtop/issues/328))
* Bug fixes and enhancements to Desktop layout
* Enable OZP Bootstrap fork
* App toolbar enhancements (e.g. [#311](https://github.com/ozone-development/ozp-webtop/issues/311))
* Handle Launch Application intent ([#187](https://github.com/ozone-development/ozp-webtop/issues/187))
* Work with Rob on the test plan
* Standard testing and bug fixes

**IWC -**
* Technical Debt
* Review public interface
  * Mock data
  * Content types
* Integration guide
* Bug fixes
* Add Grunt release
* IWC v0.1.0
* Scope legacy widget adapter

**Metrics -**
* Open up public endpoint to Piwik interface
* Roll metrics changes into center-ui branches

**UI/UX -**
* Clean up OZP Bootstrap repo
* Refactor OZP toolbar HTML to work with OZP Bootstrap repo

***

**Roadblocks:**
* VM's for metrics
* Mock Govport services
* Integration of Common Toolbar across platform

***