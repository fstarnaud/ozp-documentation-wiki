What we are deploying


How we are packaging and deploying


###  IWC Deployment Info

[https://github.com/ozone-development/ozp-iwc/wiki/IWC-App-Integration](https://github.com/ozone-development/ozp-iwc/wiki/IWC-App-Integration)

[https://github.com/ozone-development/ozp-iwc/wiki/IWC-Backend-Integration](https://github.com/ozone-development/ozp-iwc/wiki/IWC-Backend-Integration)

### Webtop
Webtop is purely client-side - to deploy, generate the production files and statically serve them. To generate the production files, clone the `ozp-webtop` repo (npm install, bower install, etc as per the README), run `grunt`, which generates a `bin/` directory containing an `assets` directory and `index.html` file. Serve these files, navigate to the `index.html` file, and you're good to go

Current issues:
 * hard-coded IWC Bus (GitHub demo site)
 * hard-coded URLs for HUD, Center, and Webtop in ozp-common-toolbar (for GitHub demo site)
 * hard-coded image URLs for demo Alerts/Messages dropdown (in ozp-common-toolbar)
