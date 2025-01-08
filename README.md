# What's this?
This is a suite of Ansible playbooks for configuring a system.

I'm breaking out individual sub-systems into their own playbooks (eg. Podman). 

`new-setup.yml` is the current attempt at sequencing several playbooks.

The intent of this project is to allow me to install Ansible onto a computer (Ubuntu based) and install my needed software via playbooks, hopefully making re-paving relatively straightforward.

The playbooks are configured (presently) to run on localhost only.

## Installing Ansible
As the playbooks are intended to run on localhsot only, we need to install Ansible on the local computer.

### Installing with pipx
First, install pipx: `sudo apt install pipx`

Then follow the instructions here:
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-and-upgrading-ansible-with-pipx
