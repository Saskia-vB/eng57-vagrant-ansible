# Ansible

## Why Ansible?
- operation side of DevOps
- maintaining structure of servers
- increase number of servers it increases complexity
- ansible, is a system solution
- with ansible, a code is written once for the installation and deployed multiple times - one script

## What is Ansible?
- create and control 3 key areas:
  - IT automation
  - Configuration management
  - Automatic deployment


## Ansible - push configuration tool
- push configuration where there master server pushes configuration to the nodes
- pushing out the service and the structure of the server to remote hardware and putting on the remote hardware irrelevant of the structure out there
- advantage: no over head weight of client server installed having to constantly communicate back to master environment

#### Pull configuration tool
- key server that has all the instructions on and on each server that is connected to the master server you would have a piece of software that would communicate to the master server known as client, periodically change or update the client
- i.e. Chef, Puppet


## Ansible architecture
- local machine you create a module known as a playbook
- creates to each node through ssh
- playbook: instructions to configure the nodes, written in YAML

## Ansible Inventory
- maintain the structure of our network environment
- creating to different nodes, webserver and database

## Working Ansible
