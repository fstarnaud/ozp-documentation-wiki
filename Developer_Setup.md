
## Build and install an instance of OZP

**Pre-requisite**
 * Latest Version of VirtualBox ( At this time 5.0.14)
 * Latest Version of Vagrant (At this time 1.8.1)
 * MacOS or Ubuntu (This has not been tested on Windows)

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
**Pre-requisite**
 * a text editor such as Atom - https://atom.io/
 * latest version of node (at the time of writing this 5.5.0)
 * latest version of npm (at the time of writing this 3.3.12)
   * `npm install -g npm@3.3.12`

These are the same steps for Center, HUD, Webtop and IWC. Just change the director for the different products

1. Fork the ozp-center repo
 * Fork the ozp-center repo at https://github.com/ozone-development/ozp-center
 * You should now have a clone of the ozp-center repo in your profile directory that you have full commit access to
2. clone your fork of ozp-center
 * `git clone https://github.com/<username>/ozp-center`
3. from the ozp-center directory run the following commands
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
