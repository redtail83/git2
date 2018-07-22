Ansible Role: Git2
=========

Install Git2 for CentOS and Ubuntu linux machine.
When your machine is installed only Git version 1 by default, you can install Git version 2 by using this Ansible role.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Both CentOS 7 and Ubuntu 16.04:

    - hosts: servers
      roles:
         - { role: redtail83.git2 }

License
-------

MIT
