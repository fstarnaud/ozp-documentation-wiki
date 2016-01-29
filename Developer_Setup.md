
## Build and install an instance of OZP

**Pre-requisite**
 * Latest Version of VirtualBox
 * Latest Version of Vagrant
 * MacOS or Ubuntu (This has not been testing for windows)

**Build and install OZP**  

1.  All files needed are in the ozp-ansible repo
  * `git clone https://github.com/ozone-development/ozp-ansible.git`
2. rename the vault file
  * `mv group_vars/all/vault_unencrypted.yml group_vars/all/vault.yml`
3.`vagrant up`
  * the first time you run this it will take about 30 min depending on your internet connection
4. Download and install test certificates into your browser
  * https://github.com/ozone-development/ozp-ansible/blob/master/roles/ssl_certs/files/wsmith.p12 
5. Test Center, HUD, the API, and the API Docs
  * Center - https://localhost:4433/center/
  * HUD - https://localhost:4433/hud/
  * API - https://localhost:4433/api/
  * API Docs - https://localhost:4433/docs/
6. If these all work you have a full copy of the Ozone Platform running on a VirtualBox on your machine. Now we can setup a development environment.If you don't plan to develop code and only want to test OZP you can stop here.

## Setup your development environment
Pre-requisite
* a text editor such as Atom - https://atom.io/
* latest version of node
* latest version of npm

1.