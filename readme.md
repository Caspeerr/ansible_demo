# Ansible Automated Deployment

Deploys a static website to a local Ubuntu VM using Ansible + Vagrant.

## Prerequisites
- VirtualBox
- Vagrant
- Ansible (sudo apt install ansible)

## Setup
vagrant up
ansible-playbook -i inventory deploy.yml

Visit http://192.168.56.10 to see the deployed site.

## Project structure
- deploy.yml — Ansible playbook (installs Apache, deploys site)
- inventory — target server configuration
- index.html — static website
