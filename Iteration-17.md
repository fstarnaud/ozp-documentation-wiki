# Iteration 17 (4 Feb 2015 - 18 Feb 2015)

***

### Next Milestones:
OWF7 Adapter
<br>26 Feb 2015 - TRR
<br>26 March 2015 - ATO
<br>2 April 2015 - ORR
<br>16 April 2015 - IOB

Minimal delivered set of features
* PKI Login
* Application data migration script from 7.16 store
* Deployment package for OZP
* IOB Features for Center/HUD, Webtop, Backend, IWC, Metrics
* Working Backend
* OWF 7 Adapter


***

## Iteration Goals:
### Center/HUD
* Profile information will be shown when clicking on the Owner of the listing
* Frontend- As an Admin, I want to be able to create system wide notifications
* As a Org Steward I want the ability to see all of the listing activity in my Organization
* As a Owner I want the ability to see all of the listing activity for my listings
* Launch a Widget into a Webtop from the HUD
* Launch a widget into Webtop - Webtop
* Launch App using account default method
* Remove Log out
* The Metrics link in the HUD and Center User drop downs should not be accessible to users
* Changes for HUD UI 

### Backend
* Implement the back end for the Notification Service

### Webtop
* Re-add ability to open a new widget in webtop via a URL as per [#394](https://github.com/ozone-development/ozp-webtop/issues/394) **note limitations of this approach!**
* Remove hardcoded dummy usernames [#381](https://github.com/ozone-development/ozp-webtop/issues/381)
* Resolve issue of hardcoded URLs to HUD, Center, and Webtop [#372](https://github.com/ozone-development/ozp-webtop/issues/372)
* Extensive testing in preparation for real deployment [#382](https://github.com/ozone-development/ozp-webtop/issues/382)
* Finish right click directive [#383](https://github.com/ozone-development/ozp-webtop/issues/383)

### IWC
Iteration 16 performance testing indicates that IE 9 falls apart at more than 6 localStorage events per second on our configuration.  The latencies quickly skyrocket as it gets further and further behind.  Firefox seems to handle hundreds without difficulty.  
* [Issue 188](https://github.com/ozone-development/ozp-iwc/issues/188): Measure performance of IE 10 and IE 11 to determine the scope of the problem. Investigate the viability of different approaches to making IE work better:
  * [Issue 202](https://github.com/ozone-development/ozp-iwc/issues/202): OPTION: [Nagle's Algorithm](http://en.wikipedia.org/wiki/Nagle's_algorithm) for the KeyBasedLocalStorageLink.  This would also require a "noDelay" flag for packets that are time sensitive (i.e. leadership election).
  * [Issue 201](https://github.com/ozone-development/ozp-iwc/issues/201): OPTION: "BulkGet" action for APIs to get all values who have keys that match a pattern.  The N+1 antipattern of "list" N items and N "get"s on those items exists in the IWC and would reduce a lot of traffic for applications starting up.  e.g. the debugger lists all keys and does individual gets on them, causing a flood of 500+ packets within a second or two at startup.
  * [Issue 200](https://github.com/ozone-development/ozp-iwc/issues/200): OPTION: Have each RouterWatchdog aggregate the heartbeat packets for a peer into one, instead of each peer sending 7+ "set" packets to names.api every 10 seconds.
  * [Issue 199](https://github.com/ozone-development/ozp-iwc/issues/199): OPTION: Investigate other link options that work on IE 9 (e.g. Flash or ActiveX shims)
* Peer review the security implementation.
  * [Issue 192](https://github.com/ozone-development/ozp-iwc/issues/192): Continue to implement the PEPs.
  * [Issue 198](https://github.com/ozone-development/ozp-iwc/issues/198): Document the OZP-specific security attributes and policies.
* Refactor how the APIs load data from the server
  * [Issue 197](https://github.com/ozone-development/ozp-iwc/issues/197): Treat the endpoints as a flat list instead of the head of a tree.  This eliminates the recursive crawl and the fragile counting that sometimes prevents the data.api from knowing that it's ready to start work.
  * [Issue 193](https://github.com/ozone-development/ozp-iwc/issues/193): Remove the attempts to manually resolve relative links.  It's a remnant from before we understood that HAL requires absolute links (or at least root-relative) that triggers at odd times.
  * [Issue 194](https://github.com/ozone-development/ozp-iwc/issues/194): Don't fetch a _link if the resource is also _embedded.
  * Update app & backend integration guides


### Legacy Widget Adapter
* Drag and Drop support (think that we can get complete compatibility!)


### Metrics
* Deploy Govport groups updates
* Change to allow users to view metrics based on membership in a govport group


### UI/UX
* Refine content of Ozone marketing website

***

## Roadblocks
* UX Research Survey


***