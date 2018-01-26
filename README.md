MongoDB Ansible Role
=========

This role installs and simple configures MongoDB. This simple role for OTUS DevOps Course Homework № 13 Developing and testing Ansible roles and playbooks.

Test Roles
-----------

Travis-CI testing role with Molecule and Testinfra on Google Cloud Platform

Requirements
------------

This role requires Ansible 2.0 or higher and platform requirements are listed in the metadata file.

Role Variables 
-------------- 
``` 
mongo_port: 27017 
bind_ip: 127.0.0.1

```` 

Dependencies
---------------
 None  

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }


