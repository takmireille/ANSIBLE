Role Name: ssh-keygen
=========

This role manages the generation of the ssh key pair on the ssh key pair on the lochost
-------------

Role Variables
--------------
no particular variables for this role.
Dependencies
-------------
no dependency added to this role

Example Playbook
----------------


    - hosts: servers
      become: true
      vars:
        password:
        user:


    - tasks:
        - ansible.builtin.import_role:
            name: ssh-keygen


Author Information
------------------


