# Iteration 41( 6 Jan - 20 Jan)

*** 
### Next Milestones:
* Production deployment of new backend

## Iteration Goals:
* Continue new backend testing with center, hud, webtop, and iwc
* Rebuild ci-prototype (new-backend deployment on di2e) using Ansible
* Automate infrastructure provisioning including:
  * Vagrant (dev/demo setups)
  * CI boxes (ci-jenkins, ci-prototype)
  * HS python test VM
  * HS staging/production infrastructure. 
* Ansible scripts should also be used for Jenkins build and/or deployment jobs (as opposed to the `deploy_backend` and `deploy_frontend` bash scripts)

### Front End (Center, HUD, Webtop)

* Center:
  * Open Search
  * Help Tour Integration
  * Complete integration of bootstrap-classify
  * Search not searching [#473](https://github.com/ozone-development/ozp-center/issues/473)

* Help Tour:
 * Finish up help tour for Center

* Tech Debt

### Backend:
* Run database migration script on new production dump - check for issues
* bug fixes/doc updates

### 508 
* Improve accessibility for (Center, HUD, Webtop)
* List of specific 508 compliance items currently working on
   * Center - Fix the top two carousel
   * Center - Fix the notification button   
* Review 508 wiki with compliance office and in (Gitbook) 

### IWC
* Documentation
    * Tutorials: Update tutorials with new simplified api calls of [#362](https://github.com/ozone-development/ozp-iwc/issues/362) [#361](https://github.com/ozone-development/ozp-iwc/issues/361)

    * Gitbook: Add docs on new simplified api calls of [#362](https://github.com/ozone-development/ozp-iwc/issues/362) [#361](https://github.com/ozone-development/ozp-iwc/issues/361)

    * Tutorials: Location Lister end to end tutorial.
    * Video Tutorials: determine/script what will be covered in first video.
* General Code maintenance:
    * Review client api function signature enhancements [#362](https://github.com/ozone-development/ozp-iwc/issues/362) [#361](https://github.com/ozone-development/ozp-iwc/issues/361)

### Metrics
* Investigate ability to change metrics search results from case sensitive to not case sensitive. Currently "map" and "MAP" and "Map" are logged as different search terms

### UI/UX
* Add layout to profile modal [#39](https://github.com/ozone-development/ozp-react-commons/pull/39) [#659](https://github.com/ozone-development/ozp-webtop/pull/659), update icons

## Roadblocks
