ansible-role-fah
=========

Installing Folding@home via ansible

Requirements
------------

A linux box running debian like OS.
Debian, Ubuntu or other flavors. Even Raspberry Pi 

Role Variables
--------------

Before run! Please edit vars/main.yml to information about account-token and what release do want to use (alpha, beta or stable)

Dependencies
------------

None specific dependencies needed more then ansible-core

Example Playbook
----------------

```yml
- hosts: fah-client
  gather_facts: true
  become: true
  remote_user: CHANGEME
  roles:
     - role: ansible-role-fah
```
