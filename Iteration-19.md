# Iteration 19 (4 March 2015 - 18 March 2015)

*** 
TRR Feedback:

* Icons don't load in IE (52 reports) - by far the biggest issue. Not a development problem - Ozone needs to be added to a whitelist so font downloads are permitted
* Webtop doesn't work in IE (26 reports) - Should be largely fixed now. Removed massive number of IWC calls (and thus HTTP requests) that were crippling IE9
* No error message on admin page (9 reports) - Fixed but not yet deployed highside
* Save a Listing results in 'death spiral' (7 reports) - Maybe fixed? Difficult to reproduce
* Webtop loads too slowly in IE (7 reports) - Same fix as previous IE web issue - eliminated almost all IWC calls/HTTP requests. Should be mostly fixed now
* Bouncing Balls doesn't work in IE (6 reports) - true story
* Webtop changes not persisted in IE (4 reports) - Also fixed by previous webtop modifications for IE
* Pressing enter in search box - behavior differs by browser (3 reports) - still outstanding issue?
* Listing Management display issues in Firefox (3 reports) - ?
* Webtop has update issues when using multiple webtop tabs - yup, and that's not likely to change anytime soon
* Save a Listing page, choose owner fails in IE (2 reports) - only one tester was able to reproduce this
* IE9 compatibility view (2 reports) - I think this means the page is loading in the "IE9 Compatibility View" mode. Probably could be prevented by setting HTTP headers on the server (not currently being done highside). Not a development issue beyond what we've already addressed
* Listing Management issues (2 reports) - believe this is fixed now
* Toolbars are inconsistent (1 report) - when switching between Center, HUD, and Webtop, the top toolbar shifts/icons in slightly different locations
* IE Search text missing (1 report) - maybe fixed?
* Focus in IE webtop modal hover (1 report) - unclear what that means
* Webtop phantom widgets appearing (1 report) - blank iframes will appear if a user unbookmarks an app that in on their dashboard. It is believed that is what happened here, and this is a known issue
* IE not sending correct certs - no exact number of reports, but apparently it happened a lot

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
* Add more unit tests
* Cleanup with some bug fixes

### Backend
* Complete performance improvements for the loading of the Search and Discovery page (limiting unnecessary calls)
* Separate cereteEdut/index.jsx into separate files
* Legacy REST Calls

### Webtop
* TODO

### IWC
* TODO

### Legacy Widget Adapter
* TODO

### Metrics
* TODO

### UI/UX
* TODO

## Roadblocks
* User Research Survey

***