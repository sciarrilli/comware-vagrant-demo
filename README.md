# Comware Vagrant Demo <br>
<br>
# Please follow these steps carefully

# Prerequisites

This demo requires vagrant, virtualbox and ansible are installed on the same box.

This demo will run on Mac OS X or Linux

# VSR box setup
Download the VSR vagrant box from: <br>
https://hpenterprise.sharepoint.com/teams/ams-dc-cse/Shared%20Documents/vagrant_vsr/golden-vsr.box

vagrant box add /path/to/golden-vsr.box --name vsr

# Run the demo
git clone https://github.com/sciarrilli/comware-vagrant-demo.git <br>
cd comware-vagrant-demo <br>
vagrant up workbench <br>
vagrant up <br>
vagrant ssh workbench <br>
cd cw7-ansible <br>
ansible-playbook vsr-ping.yml <br>
ansible-playbook demo.yml <br>
