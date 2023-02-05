nginx
=========
this role allows the installation of nginx on the server, taking into account its configuration, with the variables taken into account
------------
variables
--------------

in addition to the hosts variables, some default variables are taken into account in the defaults part of the role

Dependencies
------------
no particular dependencies

Example Playbook
----------------


    - hosts: servers
      become: true
      vars::
       - 
       -
    - tasks:
        - ansible.builtin.import_role:
            name: nginx
            state: started
