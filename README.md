ansible-role-hp-spp
=========

Install HP SPP and STK repo and install some software from it.

Defaults to:
 - hpssacli
 - hp-health
 - hponcfg
 - conrep
 - hp-scripting-toolkit

A foundation for making this work on Debian based system is also
included. It is however missing:
 - testing
 - an hpspp.list template

PRs are welcome

Debian currently systems don't have the SPP (so no firmwares). Instead there is the
MCP (Management Component Pack). More details in: 

http://downloads.linux.hpe.com/SDR/repo/spp/Debian.ReadMe

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
