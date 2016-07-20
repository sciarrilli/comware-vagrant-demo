# comware-vagrant-demo
# Prerequisites 

This demo requires vagrant, virtualbox and ansible are installed on the same box.

This demo will run on Mac OS X or Linux

# VSR box setup
Download the VSR vagrant box from:
https://hpenterprise.sharepoint.com/teams/ams-dc-cse/Shared%20Documents/vagrant_vsr/vsr.box

vagrant box add /path/to/vsr.box --name vsr

# git clone
git clone https://github.com/sciarrilli/comware-vagrant-demo.git
cd comware-vagrant-demo
vagrant up workbench
vagrant up
vagrant ssh workbench
