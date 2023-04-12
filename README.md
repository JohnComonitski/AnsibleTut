# Ansible Playground

## Ping Devices
ansible all --key-file ~/.ssh/ansible -i inventory -m ping

## Ping Shorten with config
ansible all -m ping

## Get Host
ansible all --list-hosts

## Current status/config of servers
ansible all -m gather_facts

## Current status/config of a specific server
ansible all --list-hosts --limit 0.000.000
