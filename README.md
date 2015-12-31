ansible-role-hp-spp
=========

Install HP SPP repo and install some software from it.

Defaults to:
 - hpssacli
 - hp-health

A foundation for making this work on Debian based system is also
included. It is however missing:
 - testing
 - an hpspp.list template

PRs are welcome

Requirements
------------

Internet

Role Variables
--------------

see defaults/main.yml

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-hp-spp }

License
-------

MIT

Author Information
------------------
