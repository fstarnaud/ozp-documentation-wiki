# Iteration 20 (18 March 2015 - 1 April 2015)

*** 
### Next Milestones:
OWF7 Adapter
<br> 12 May 2015 - App Data transistion
<br>27 May 2015 - ORR
<br>11 June 2015 - IOB

Goals:
* Continue to work off Bugs
* Deployment and development packages for OZP with documentation
* OWF 7 Adapter with documentation
* Implement Gitflow (everyone read this: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow/)
* Build Server (remove dependencies on owfgoss infrastructure)
  * Jenkins instance
  * VMs for builds (CentOS)
  * VMs for deployment (will be behind a VPN)
* Performance test for Backend
***

## Iteration Goals:

### Center/HUD
* Investigate providing app submitters instructions on how to allow OZP collect metrics on their app 
* ~~Merge `temp-master` with `master` to begin switching to GitFlow structure. (after TRR)~~ - Now in the Develop Branch
* ~~Normalize / Automate generation of Shrinkwrap file.~~ Shrinkwrap has been removed for the time being
* Fix bugs - This is continuing on to the next iteration

### Backend
* Work on performance scripts (update gatling scripts used for legacy version) - Scripts have been updated to work with the new system but still require fine tuning and need to be run.

### Webtop
* ~~Disappearing words on mouse over [#484](https://github.com/ozone-development/ozp-webtop/issues/484)~~
* Hide metrics link unless user is an app mall admin [#490](https://github.com/ozone-development/ozp-webtop/issues/490)
* Lots of dead links in the top toolbar [#423](https://github.com/ozone-development/ozp-webtop/issues/423)  --Move to after IOB
* Widget resize is flaky at best in both Grid and Desktop layouts (IE9) [#439](https://github.com/ozone-development/ozp-webtop/issues/439)
* Handle closing IWC widgets (deregister) [#497](https://github.com/ozone-development/ozp-webtop/issues/497)  --Waiting to hear from IWC

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
* Implement groups in GP cache

### UI/UX
* ~~Remove as much Webtop CSS overrides as possible~~
* ~~Continue discussions and mockups on future UIs (Help, Profile, Settings, AppBuilder, etc)~~
* ~~Provide support for platform UI bugs and inconsistencies~~

## Roadblocks
* IWC Documentation for Legacy Adapter and Rest Endpoints

***