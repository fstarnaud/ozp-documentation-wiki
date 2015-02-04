## Iteration 16 (21 Jan 2015 - 04 Feb 2015)

***

### Next Milestones:
OWF7 Adapter
26 Feb 2015 - TRR
26 March 2015 - ATO
2 April 2015 - ORR
16 April 2015 - IOB

Minimal delivered set of features
* PKI Login
* Application data migration script from 7.16 store
* Deployment package for OZP
* IOB Features for Center/HUD, Webtop, Backend, IWC, Metrics
* Working Backend
* OWF 7 Adapter


***

### Iteration Goals:
**Center/HUD -**
* ~~Complete Reviews Tab for the Detail View [Filter by star rating, allow org stewards to manage reviews, testing, developer doc]~~
* ~~Add image upload for the Intents~~
* ~~Add Recent Activity page for AML Steward~~ (Dev work complete)
* ~~Remove Enable/Disable option from listing menu (no need for duplicate functionality)~~
* ~~Display Organization Short name on listings~~
* ~~Create external configuration file(s)~~
* ~~Added Global Nav Bar into the Center~~ (Brought into iteration mid-sprint)
* Profile page (Brought into iteration mid-sprint) - In progress 

**Backend -**
* Implement the Notification Service
* ~~Create external configuration file~~
* ~~Sorting listings Alphabetically for the Listing Management pages~~ (Brought into iteration mid-sprint)

**Webtop -**
* Remove hardcoded dummy usernames [#381](https://github.com/ozone-development/ozp-webtop/issues/381)
* Resolve issue of hardcoded URLs to HUD, Center, and Webtop [#372](https://github.com/ozone-development/ozp-webtop/issues/372)
* Extensive testing in preparation for real deployment [#382](https://github.com/ozone-development/ozp-webtop/issues/382)
* Add right click directive [#383](https://github.com/ozone-development/ozp-webtop/issues/383)
* ~~Allow applications inside of webtop to get their IWC peer url from the query parameters [#388](https://github.com/ozone-development/ozp-webtop/issues/388)~~
* ~~Set draggable area to be entire chrome bar [#387](https://github.com/ozone-development/ozp-webtop/issues/387)~~

**IWC -**
* Continue ABAC Implementation & Review.
* Investigate slow performance in Internet Explorer.
* BUG: IWC improperly concatenates urls in some situations.
* BUG: IWC needlessly fetches `_linked` resources that are also `_embedded`.


**Legacy Widget Adapter -**
* Translate OWF 7 pubsub to broadcast intents.
* Translate the OWF 7 "launch" API.
* Investigate LOE for translating the OWF 7 Drag & Drop API.

* ~~OWF.Eventing, OWF.Launcher, documentation and approach for Drag & Drop~~
* ~~Preferences, findWidgets, and a number of other calls work on the OWF 7-based OZP backend.  Since they rely on the server to respond to a window.name transport request, other backends will not work without additional work.~~

**Metrics -**
* ~~Implement reporting for submitted apps, approved apps, app reviews submitted, app reviews viewed~~
* ~~Update search metric to report after slight delay~~
* ~~Investigate use of govport groups to give metrics user permissions~~


**UI/UX -**
*  Waiting on research
*  Waiting on global toolbar / webtop toolbar integration
*  ~~Reviewing development and adding bugs in~~
*  ~~Redo of OWFGOSS site and move to gh-page~~

***

**Roadblocks:**
* UX Research Survey
* ~~Need artifacts from ADG~~


***