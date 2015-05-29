Draft listings in HUD would be a benefit to a variety of people.

It would allow
* sharing of dashboards prior to system-moderated sharing of dashboards and/or other listings if they were uploaded to the user's system using a code snippet.
* testing of applications in the production environment to check bugs and ensure full intended functionality and performance prior to initial approval and release.
* users who are constrained in their internet access could receive temporary versions of useful new listings without syncing with the entire store.
* And many, many more use cases...


## Questions
* Could the listing export include the GUID? If it could, could it be matched against the DB?

(Then a published shared listing could be treated like a normal bookmark and not made a draft. In that case, drafts would only be listings created by the user whose account the draft is in.)

Most of the work would occur on the backend but the UI artifacts are mocked up below.

#### Visual Treatment
##### HUD
* The application banner would have an overlay at 30% opacity of a black background and a white "Draft" icon.
* The application's name would be italicized.
* The menu would no longer have the "Get Help" option and would, instead, have a "Submit to Marketplace" link that would take users to the "Submit a Listing" form with all the available information on the listing.

#### Webtop

## Mockups
**Chartcourse is the example draft listing in the following mockups**

### HUD
#### Static Listing
![Draft Listing](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_Bookmarks_Draft_00Static.png)

#### Menu Open
![Draft Listing - Menu](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_Bookmarks_Draft_01Menu.png)