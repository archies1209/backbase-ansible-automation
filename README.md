# Pre Requisite: To be installed on the machine
Ansible
Vagrant
Virtual Box

# To run vagrant file
Go to ansible folder and run Vagrant up

Vm box = Centos/7
Provider = Virtual box
Provisioning = Ansible
Playbook = configure-ci-server.yml
Inventory file = hosts

# Tasks and other dependencies and yml files related to Redhat are present in the roles folder

Roles = git installation
        java installation
		Jenkins installation
		
 # Jenkins would be running on localhost:8085

