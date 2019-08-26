Repo to save ansible scripts to upgrade PAN OS from 8.0 to 8.1

mastery-example/ -> example used to inspire these scripts
paloalto/ -> real scripts

Module repository: https://github.com/PaloAltoNetworks/ansible-pan
Documentation: https://paloaltonetworks.github.io/ansible-pan/

Install required Python libraries: pip3 install pan-python pandevice

Install modules from Ansible Galaxy (builtin with ansible unbuntu 18.04 package): ansible-galaxy install PaloAltoNetworks.paloaltonetworks

Run Script: ansible-playbook softupdate.yaml -i inventory.ini
