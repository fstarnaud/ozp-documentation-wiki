## Iteration 12 (26 Nov 2014 -  10 Dec 2014)

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
* 

**Webtop -**
* Cleanup and integrate [#133](https://github.com/ozone-development/ozp-webtop/issues/133), which prevents the DOM from being torn down when switching layout views or dashboards (for dashboards marked as 'sticky')
* Desktop layout enhancements from previous iteration (bugs and features required to support #133)
* Upgrade to latest ozp-bootstrap (currently working off a version ~2 weeks old)
* Time permitting, work [#187](https://github.com/ozone-development/ozp-webtop/issues/187) (handle IWC Intents to launch applications into Webtop)

**IWC -**
* Bug fixes
    * [Firefox api loading throws restricted URI](https://github.com/ozone-development/ozp-iwc/issues/144)
    * [Create/Delete localstorage key on Firefox 17 (potentially other browsers) doesn't generate an event](https://github.com/ozone-development/ozp-iwc/issues/123)
    
* Technical Debt
    * [Restructure IWC state unloading](https://github.com/ozone-development/ozp-iwc/issues/155)
    * [Data.api child persistence](https://github.com/ozone-development/ozp-iwc/issues/158)
    * [Move client IWC to use promises for connection](https://github.com/ozone-development/ozp-iwc/issues/157)
    * Endpoint loading algorithm evaluation/update
* Guides
    * Integration Guide v2
    * Application Guide v1
* IWC v0.1.0
* Scope legacy widget adapter
* Talking points for why IWC is different the standard HTML5

**Metrics -**
* 

**UI/UX -**
* Waiting on research 
* Waiting on global toolbar integration 
* Waiting on webtop toolbar integration 
* Continue refining Bootstrap as it is integrated

***

**Roadblocks:**
* VM's for metrics
* Mock Govport services
* Integration of Common Toolbar across platform

***