Role Name
=========

This role deploys Nemesis.

Requirements
------------

All dependencies are installed in this Ansible role.

Role Variables
--------------

All variables present in the defaults directory must be modified for the own users preference. 

The username variable must be set to the user that will be running Nemesis on the remote server.

The password is the universally used password across the Nemesis environment.

Dependencies
------------

/

Example Playbook
----------------

Role usage:

---
- name: Configure Server
  hosts: localhost
  vars:
    ansible_shell_executable: "/bin/bash"
  roles:
    - nemesis_server


License
-------

BSD

Author Information
------------------

