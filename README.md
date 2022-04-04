## ZT's repository of Ansible scripts for environment setup

This repository contains a whole bunch of Ansible scripts so that the ideal environment can be setup quickly when working on a new server/workspace. For plain convenience sake and to play around with Ansible scripting.

## Setup and installation

To install Ansible on Ubuntu, run the following:
```shell
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```

To run a playbook locally (with sudo privileges)
```shell
$ ansible-playbook <playbook.yml> --ask-become-pass
```

## Scripts
1. Golang setup script (golang_setup.yml)