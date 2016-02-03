
## Build and install an instance of OZP

**Pre-requisites**

 * Latest Version of VirtualBox (At this time 5.0.14)
 * Latest Version of Vagrant (At this time 1.8.1)
 * MacOS or Ubuntu (This has not been tested on Windows)

***Under Windows***

Although not tested extensively, some have reported being successful in following these instructions under Windows. Some caveats:

* For best results, consider installing [Cygwin](https://www.cygwin.com "Cygwin") and running the provided instructions from its Bash shell

* There are known issues with Vagrant 1.8.1 in its handling of paths under Windows. These are to be fixed in the upcoming version [1.8.2](https://github.com/mitchellh/vagrant/issues?utf8=%E2%9C%93&q=milestone%3A1.8.2+ "1.8.2"). However, in the interim, the Ruby files can be patched manually under `C:\HashiCorp\Vagrant\embedded\gems\gems\vagrant-1.8.1\plugins\provisioners\ansible`
 
* Make sure to setup your git configuration not to have EOL converted to CRLF by setting `git config core.autocrlf false` and ensuring that `.gitattributes` has the following entries. Failing to do so may result in false error messages complaining about missing files.
 * `*        text=auto`
 * `*.initd  text eof=lf`
 * `*.sh     text eof=lf`

**Build and install OZP**  

1.  All files needed are in the ozp-ansible repo
  * `git clone https://github.com/ozone-development/ozp-ansible.git`
2. rename the vault file
  * `mv group_vars/all/vault_unencrypted.yml group_vars/all/vault.yml`  
3. `vagrant up`
  * the first time you run this it will take about 30 min depending on your internet connection
4. Download and install test certificates into your browser
  * https://github.com/ozone-development/ozp-ansible/blob/master/roles/ssl_certs/files/wsmith.p12
  * test cert for winston smith password is password
5. Test Center, HUD, the API, and the API Docs
  * Center - [https://localhost:4433/center/](https://localhost:4433/center/)
  * HUD - [https://localhost:4433/hud/](https://localhost:4433/hud/)
  * API - [https://localhost:4433/api/](https://localhost:4433/api/)
  * API Docs - [https://localhost:4433/docs/](https://localhost:4433/docs/)
6. If these all work you have a full copy of the Ozone Platform running on a VirtualBox on your machine. Now we can setup a development environment.If you don't plan to develop code and only want to test OZP you can stop here.

## Setup your development environment
**Pre-requisites**

 * a text editor such as Atom - https://atom.io/
 * latest version of node (at the time of writing this 5.5.0)
 * latest version of npm (at the time of writing this 3.3.12)
   * `npm install -g npm@3.3.12`

These are the same steps for Center, HUD, Webtop and IWC. Just change the director for the different products

1. Fork the ozp-center repo
 * Fork the ozp-center repo at `https://github.com/ozone-development/ozp-center`
 * You should now have a clone of the `ozp-center` repo in your profile directory to which you you have full commit access
2. clone your fork of `ozp-center`
 * `git clone https://github.com/<username>/ozp-center`
3. from the `ozp-center` directory run the following commands
 * `npm install`
 * `node -v` 
 * `npm -v` 
4. If npm install runs without errors, You are now ready to run your local copy of ozp-center using your VirtualBoxes OZP backend
 * `API_URL="https://localhost:4433/" npm start`
5. Test 
 *  VirtualBox OZP API - [https://localhost:4433/api/](https://localhost:4433/api/)
 *  Local Development 
    * OZP Center - [http://localhost:8000/dist/](http://localhost:8000/dist/)
    * OZP HUD - [http://localhost:8088/dist/](http://localhost:8088/dist/)
6. If you have any issue with getting the environment setup please submit a GitHub issue
7. If you have additional notes/steps to add please fork the wiki and submit a pull request
8. Now start contribution to an Open Source project
 * Fix a bug, fix a GitHub issue, create a new feature and submit a pull request. We appreciate any contributions from the community
