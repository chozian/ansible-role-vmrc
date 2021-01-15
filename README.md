vmrc
=========

This Ansible role is for installing the VMware Remote Console application on Linux.

Requirements
------------

Download the VMware Remote Console bundle installer for Linux from VMware's site. Then place it in the files directory.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD 3-Clause

Author Information
------------------

Chris Hozian  
Madison, AL, USA
