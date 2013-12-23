raspberry-pi-arch-ansible
=========================

Ansible Playbooks for configuring a raspberry-pi running arch linux

Use
===

1. Run the raspberry-pi-init.yaml playbook as root

	ansible-playbook -k raspberry-pi-init.yaml


2. Run the raspberry-pi.yaml playbook as the keith user

	ansible-playbook -K raspberry-pi.yaml 
