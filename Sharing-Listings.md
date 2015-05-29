This is about the process and UI for sharing listings from HUD. First, the items (as currently planned) allowed to be shared for the initial implementation will be dashboards. The policy issues are still being worked out. As those emerge and are decided, the UI will naturally evolve.

**NOTE**  Sharing by file, as currently designed, would require the following to also be implemented:
* [Implement usage of draft listings in HUD](https://github.com/ozone-development/ozp-documentation/wiki/Draft-Listings)

**NOTE** Sharing Dashboards would require the following to also be implemented:
* [Implement Dashboards (as a listing type) in HUD and Marketplace](https://github.com/ozone-development/ozp-documentation/wiki/Adding-Dashboards-Listing-Type)

For the final version of the **Export** modal (eventual preferred file sharing method) and its partner modal, the "Import" modal, please follow this link.

## Questions
* By what identifier should people share listings by user? Email? Username? Display Name? ...
* When sharing by user, should the listing automatically populate into the recipient's bookmarks?
    * Should the recipient need to "accept" the bookmark?
* Should the sender get a notification?
    * Should it be whether the bookmarks was successfully received or if it is "accepted"?

## Webtop Mockups
*Some changes have been made since the original mockups were created, including moving the dashboards menu down to the lower toolbar.*

#### Dashboard Menu
![Dashboard Menu]()
We intend to integrate a share button into the dashboard menu so that a user could share any dashboard.

#### Share Modal in Webtop
![Share Modal]()


## HUD Mockups

#### Step 1 - Visit "My Bookmarks" in HUD
![My Bookmarks](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_ShareListing_00Bookmarks.png)

#### Step 2 - Click on "Share" in the Library options
When the user clicks the "Share" link, the "Share" modal will open, as depicted in the next step.
![My Bookmarks - Share](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_ShareListing_01Bookmarkshover.png)

#### Step 3 - The User Chooses the Listings for Sharing
The list of listings depicted should be automatically generated from the list of sharable items that are in the user's Bookmarks.
![Share Modal - Listings](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_ShareListing_03Modal_MethodUnselected.png)

#### Step 4 - The User Determines the Method of Sharing

##### By File is the Only Available
Initially, sharing by file may be the only one available. This mockup is meant to represent the UI for that functionality.


![Share Modal - By File Only](https://github.com/ozone-development/ozp-documentation/blob/master/mockups/hud/HUD_ShareListing_06Modal_OnlyMethod.png)

##### By File or By User

###### Unselected
![Share Modal - Method - unselected](https://github.com/ozone-development/ozp-documentation/blob/master/mockups/hud/HUD_ShareListing_03Modal_MethodUnselected.png)

###### By File
![Share Modal - Method - By File](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_ShareListing_04Modal_MethodFile.png)

###### By User
![Share Modal - Method - By User](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_ShareListing_05Modal_MethodUser.png)

#### Confirmation Messages

##### Successful
![Share Modal - Successful](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_ShareListing_07Modal_ConfirmationSuccessful.png)

##### Unsuccessful
![Share Modal - Unsuccessful](https://raw.githubusercontent.com/ozone-development/ozp-documentation/master/mockups/hud/HUD_ShareListing_08Modal_ConfirmationFailed.png)
