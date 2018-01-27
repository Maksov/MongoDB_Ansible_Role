MongoDB Ansible Role [![Build Status](https://travis-ci.org/Maksov/mongodb_ansible_role.svg?branch=master)](https://travis-ci.org/Maksov/mongodb_ansible_role)
=========

This role installs and simple configures MongoDB. This simple role for OTUS DevOps Course Homework № 13 Developing and testing Ansible roles and playbooks.

Test Role
-----------

[Travis-CI](https://travis-ci.org/) testing role with [Molecule](http://molecule.readthedocs.io) and [Testinfra](http://testinfra.readthedocs.io) on [Google Cloud Platform](https://cloud.google.com)

Requirements
------------

This role requires Ansible 2.0 or higher and platform requirements are listed in the metadata file.

Role Variables 
-------------- 
``` 
mongo_port: 27017 
bind_ip: 127.0.0.1
env: local
```` 

Dependencies
---------------
 None  

Example Playbook
----------------

    - hosts: all
      roles:
         - mongodb_ansible_role


