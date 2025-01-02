ansible-role-fah
=========

Installing Folding@home via ansible

Requirements
------------

A linux box running debian like OS.
Debian, Ubuntu or other flavors

Role Variables
--------------

Before run! Please edit vars/main.yml to information about account-token and what release do want to use (alpha, beta or stable)

Dependencies
------------

None specific dependencies needed more then ansible-core

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: fah-client
  gather_facts: true
  become: true
  remote_user: CHANGEME
  roles:
     - role: ansible-role-fah
