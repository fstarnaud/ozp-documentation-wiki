# Iteration 18 (18 Feb 2015 - 4 March 2015)

*** 
26 Feb 2015 - TRR

### Next Milestones:
OWF7 Adapter
<br>26 Feb 2015 - TRR
<br>26 March 2015 - ATO
<br>2 April 2015 - ORR
<br>16 April 2015 - IOB

Minimal delivered set of features
* ~~PKI Login~~
* Application data migration script from 7.16 store
* Deployment package for OZP
* ~~IOB Features for Center/HUD, Webtop, Backend, IWC, Metrics~~
* ~~Working Backend~~
* OWF 7 Adapter


***

## Iteration Goals:
### Center/HUD
* QA Notifications front end
* Update Search and Discovery Page for UI enhancements
* Update the Create/Edit Page for UI enhancements
* Update Marketplace Management pages for consistent system icons
* Error modal for the logging in of Center

### Backend
* Add HAL links for Notifications
* Implement profile search call

### Webtop
* Re-add ability to open a new widget in webtop via a URL as per [#394](https://github.com/ozone-development/ozp-webtop/issues/394) **note limitations of this approach!**
* Further testing in preparation for real deployment [#382](https://github.com/ozone-development/ozp-webtop/issues/382)
* Finish right click directive [#383](https://github.com/ozone-development/ozp-webtop/issues/383)
* Finish integrating the Global Toolbar  [#403](https://github.com/ozone-development/ozp-webtop/issues/403)
* Bug/Style fixes

### IWC
Iteration 18 is a user guide update iteration for Kevin. As well as a performance enhancement iteration for the IWC team. Kevin is collaborating with Alan for debugger enhancements, making it a better single page app for developer use.
* Updated users guides
* Debugger enhancements: utility merging.
* Security Code review.
* Performance enhancements:
   * [Issue 197](https://github.com/ozone-development/ozp-iwc/issues/197): Treat the endpoints as a flat list instead of the head of a tree.  This eliminates the recursive crawl and the fragile counting that sometimes prevents the data.api from knowing that it's ready to start work.
   * [Issue 188](https://github.com/ozone-development/ozp-iwc/issues/188): Measure performance of IE 10 and IE 11 to determine the scope of the problem. Investigate the viability of different approaches to making IE work better:

### Legacy Widget Adapter
* Need Updated users guides specifically for the legacy adapter


### Metrics
* Connect HUD App launches to Piwik
* Work with deployment team to get Metrics deployed to production environment
* Add user permissions to HUD piwik site

### UI/UX
* Continue Iterations on Help feature
* Begin discussions on next UIs (Profile, Settings, AppBuilder, etc)
* Redo coloring on OZP website
* ~~Unify page title language (currently "OZP Webtop", "Ozone HUD", and "Center")~~
* Continue modifications of Center and HUD interface styling
* Customize error messages
* Support user documentation development
* ~~Support metrics documentation development~~


## Roadblocks
* User Research Survey
* Launch a Widget into a Webtop from the HUD need feedback from PRoduct Owner

***