# Paideia Ansible

The intention of this repo is to avoid any errors when installing the different paideia services and make the process in general much easier.

## Requirements
- Ansible
- Docker & Docker Compose

## Installation
- git clone this repo to your server
- copy the contents of the inventory folder to your ansible (or add them if you have ansible running already)
- Fill out the files in group_vars and host_vars according to your setup
- use ansible to run the playbooks you want to have running on your server