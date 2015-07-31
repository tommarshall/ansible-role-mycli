Ansible Role: mycli
=========

[![Build Status](https://travis-ci.org/tommarshall/ansible-role-mycli.svg?branch=master)](https://travis-ci.org/tommarshall/ansible-role-mycli)

Installs [mycli](http://mycli.net/) on RHEL/CentOS or Debian/Ubuntu servers.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Although it's worth mentioning that this role only installs mycli, not MySQL itself. If you want a role for installing MySQL I'd recommend Jeff Geerling's excellent [MySQL role](https://github.com/geerlingguy/ansible-role-mysql).

Example Playbook
----------------

    - hosts: db-servers
      roles:
         - { role: tommarshall.mycli }

License
-------

MIT / BSD
