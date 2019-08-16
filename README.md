Repo to save ansible scripts to upgrade PAN OS from 8.0 to 8.1

Scripts have written and tested on PA-VM (VM-100) to upgrade a single node.

mastery-example/ -> example used to inspire these scripts
paloalto/ -> real scripts

Module repository: https://github.com/PaloAltoNetworks/ansible-pan
Documentation: https://paloaltonetworks.github.io/ansible-pan/

Install required Python libraries:
    pip install pan-python pandevice

Install modules from Ansible Galaxy (Ansible Galaxy comes builtin with ansible unbuntu 18.04 package):
    ansible-galaxy install PaloAltoNetworks.paloaltonetworks

Run Script:
   ansible-playbook softupdate.yaml -i inventory.ini
