# Iteration 20 (18 March 2015 - 1 April 2015)

*** 
### Next Milestones:
OWF7 Adapter
<br>   March 2015 - ATO
<br> 12 May 2015 - App Data transistion
<br>27 May 2015 - ORR
<br>11 June 2015 - IOB

Goals:
* Continue to work off Bugs
* Deployment and development packages for OZP with documentation
* OWF 7 Adapter with documentation
* Implement Gitflow (everyone read this: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow/)
* DI2E Build Server (remove dependencies on owfgoss infrastructure)
  * DI2E Jenkins instance
  * DI2E VMs for builds (CentOS)
  * DI2E VMs for deployment (will be behind a VPN)
* Performance test for Backend
***

## Iteration Goals:

### Center/HUD
* Investigate providing app submitters instructions on how to allow OZP collect metrics on their app 
* Merge `temp-master` with `master` to begin switching to GitFlow structure. (after TRR)
* Normalize / Automate generation of Shrinkwrap file. 
* Fix bugs

### Backend
* Work on performance scripts (update gatling scripts used for legacy version)

### Webtop
* Hide metrics link unless user is an app mall steward or content steward
* Lots of dead links in the top toolbar
* Widget resize is flaky at best in both Grid and Desktop layouts (IE9)
* Handle closing IWC widgets (deregister)

### IWC
Current build v0.2.4
* locks.api + enhanced elections
* api refactor (internal modules not user functionality)
* Endpoint loading enhancements to reduce HTTP requests.
* Add karma-runnter to build scripts & Travis CI
* Further Debugger standardizing.
* IWC user guide updates (`/docs`) Current version covers setup, overview, getting started, API overview, and Data api. System, Names, Intents API guides are next

### Legacy Widget Adapter
* Documentation

### Metrics
* Investigate allowing app owners/submitters creating a project in our metrics to allow metrics be collected on their app

### UI/UX
* Remove as much Webtop CSS overrides as possible
* Continue discussions and mockups on future UIs (Help, Profile, Settings, AppBuilder, etc)
* Provide support for platform UI bugs and inconsistencies

## Roadblocks
* Bouncing Balls demo in IE - need some new IWC-enabled demo apps
* User Research Survey

***