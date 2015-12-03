*Currently on-deck as Center Issue [#447](https://github.com/ozone-development/ozp-center/issues/447)*


**Private listings** are only visible to users within the listing's associated organization. They are not visible to users within other organizations.

Private listings will be visible to:
* Users within the associated organization
* Stewards of the associated organization
* Marketplace Stewards


## Implementation


-----
**1)** Org stewards, Center stewards, and those submitting or editing listings should have the ability to toggle whether or not the app is private in the Create/Edit page. This field should include a note that apps set to private must include a justification in the Usage Requirements field.

![center_privatelisting_edit](https://cloud.githubusercontent.com/assets/8047457/11566104/f9e310ce-99ae-11e5-8de6-e6e91aa73c2e.png)
![center_privatelisting_edit_selected](https://cloud.githubusercontent.com/assets/8047457/11566108/ff5cfd76-99ae-11e5-8769-96711795a9ee.png)

-----
**2)** Private listings in the Center should have a lock icon wherever the Org badge is shown (See example for Announcing Clock app below - both tile view and quickview). [**Implementation:** Icon is already in project. Insert icon into *span.company*: `<span class="company"><i class="icon-lock-blue"></i> ORG</span>`]

![center_privatelisting_tile](https://cloud.githubusercontent.com/assets/8047457/11566120/0c91475e-99af-11e5-9c7e-e7f763e1c89c.png)
![center_privatelisting_quickview](https://cloud.githubusercontent.com/assets/8047457/11566122/0ee35768-99af-11e5-9190-0edab6fba31e.png)

-----
**3)** The table view in Listing Management should have a column indicating whether or not the listing is private.

![center_privatelisting_management](https://cloud.githubusercontent.com/assets/8047457/11566135/20675bd8-99af-11e5-882b-482e5f70af85.png)

-----
**4)** The tile view in Listing Management should have an icon indicating if the listing is private. Duplicate to every tab (My Listings, each Org Listings tab, All Center Listings).

![center_privatelisting_management_tile](https://cloud.githubusercontent.com/assets/8047457/11566465/91513214-99b0-11e5-8b34-0fea71515bce.png)

-----
**5)** Any change of Public/Private status should show as a notification in the Recent Activity feed in order to make any change very visible to Admin.

![center_privatelisting_management_activity](https://cloud.githubusercontent.com/assets/8047457/11566696/8a1a0bbe-99b1-11e5-8ec7-50e5ed5a85f3.png)
