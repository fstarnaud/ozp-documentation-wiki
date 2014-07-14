### Overview
The first milestone for OZP is producing a working prototype to demonstrate to the community.  With any effort of this size, a prototype is not only a good idea, it's a necessity - it's how we stir up excitement, discussion, and criticism for what we do.  The hope is that this email will give you all plenty to think about and a target to work towards.

### Expectations
The purpose of a prototype is to demonstrate how OZP will work & what that will look like to the user.  It will take place on an open environment and will show, from start to finish, how both users and developers will use OZP for their mission.  Precisely how the demo will be conducted is still up in the air (no script has been written yet), but we know the pieces needed for it, the approximate time it will occur, and the basic idea of an outline.  We don't expect all the bells & whistles - development will be continuing in the background - but do I think we have enough in place to make something happen.

### The Pieces
The prototype, at a minimum, must include the following:
* Marketplace (MP) - the search & discovery application of OZP.  This is currently in GitHub under 'ozp-center', and is the most complete component we have.
* HUD - 'Heads Up Display' - the user-facing front page for favoriting apps and receiving notifications.  This component requires some refactoring & renaming before proceeding.
* Webtop - the renderer of applications.  Work is already underway on this.
* IWC - Inter-Widget Communications - a network bus w/in the browser.  Work is already underway, and it will be crucial in the coming development cycles.
* Basic back-end services.  Simple, nothing crazy, just enough to make everything else above work.  We've identified three controllers that are a must for the prototype:
** Dashboard Controller - for the webtop, based on GRIDSTER. 
** Marketplace Controller - according to what's in GitHub, this is mostly done, but we'll need to tie it into IWC and ensure it can work for the demo.
** Security Controller - at a minimum, describe the process in detail, possibly show something in the Marketplace and/or HUD to provide the audience an idea.
(Please let us know if anything more would be needed for demonstration purposes only)

### Timeline
* 25JUN-30SEP - Research/Prototype Phase 
* 15SEP - Prototype demo-ready - in order to iron out any bugs & rehearse.
* 30SEP (tentative) - Prototype Demonstration - NOT a hard date.  Expect some movement left or right. 
* 1OCT-4MAR - Development Phase 
* 5MAR - Initial Operating Capacity (IOC) 

### Basic Outline
The workflow of the demo should show a start-to-finish concept, as well as a basic 'day in the life' of a user & a developer.  This is a rough outline only and WILL change, but something will be hammered out later this month.  At a minimum, I hope it gives you the right frame of mind.

1. Open OZONE Platform
2. Navigate the HUD
3. Open Marketplace
4. Search for apps
5. Favorite an app
6. Launch an app from the MP
7. Launch an app from the HUD
8. Show IWC in action with sample applications

More to follow.  Remember, this is a rough outline of just the workflow.  A script is in the works.  If you have any suggestions to add, please send them our way.

## Integration
Integration of the various components will be a hurdle, the obvious of which being we are geographically separated and this is quite a large effort.  As the various components come to fruition, we will have to start merging things together in order to demo, making communication key between all of us.  This is not an insurmountable challenge by any stretch (37Signals developed Basecamp with 17 employees on 4 continents), and we think that if the following are at a mature stage for the demonstration, it will help our overall development effort leading into FY2015:
* Test environments - an effort is already underway to secure a test environment, but assistance is needed in ensuring all test environments are available.  The prototype will be demonstrated on this test environment.
* Documentation
* Deployment Strategy - this will be the responsibility of the leadership, but input will be sought after throughout development.
* Hosted Servers - OZONE must be hosted on a public URL for the demo.
(Integration will continue to be a major effort both during & after the Research/Prototype Phase, obviously)