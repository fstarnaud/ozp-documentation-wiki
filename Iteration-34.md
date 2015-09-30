# Iteration 34 (30 Sept - 14 Oct)

*** 
### Next Milestones:
* Re-factored backend removing dependencies on Java 7
* 12/1/2015 - backend alpha in staging  
* Interactive Help

## Iteration Goals:
* Final verification on Table View feature (Center)
* Functional completeness of Center, HUD, and Webtop in new backend (LS dev env)

### NC
* Continue supporting testing efforts
* Java 8 Support for OMP
* Continue update of documentation with new features

### Center / Interactive Help
* Merge Table View 
* Interactive Help:
  * Role based article displays [#39](https://github.com/ozone-development/ozp-help/issues/39)

### Backend (new):
* system.api and intents.api endpoint support
* bug fixes

* Center Changes:
  * Center Settings:
    * Stewards [#28](https://github.com/ozone-development/ozp-backend/issues/28)
    * Intents [26](https://github.com/ozone-development/ozp-backend/issues/26)

### Webtop / HUD

### 508

### IWC/Legacy Adapter
* Performance evaluations
    * Investigate utilization of a shared IWC bus for multiple IWC clients in one browser window chain [#328](https://github.com/ozone-development/ozp-iwc/issues/328)
    * Investigate using shared webworkers (consensus algorithms would be fallback) [#330](https://github.com/ozone-development/ozp-iwc/issues/330)
    * Investigate using message channels for client-> bus communication (postMessage as fallback) [#333](https://github.com/ozone-development/ozp-iwc/issues/330)
    * Investigate additional Transport Links (other than localStorage) to broaden browser support.
* Documentation
    * Additional OWF7 to IWC migration guides for application developers.

### Metrics
* Determine exact metric reports that need to be automated (meeting with Mark)

### UI/UX
* Convert LESS to SASS via docker
* Clean up bootstrap
* Support ongoing development
  
## Roadblocks