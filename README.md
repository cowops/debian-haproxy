Debian-Haproxy
==============

The Reliable, High Performance TCP/HTTP Load Balancer

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

debian:
    version: wheezy

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-haproxy, debian.version: wheezy }

Tasks
-----

  - Install [HAProxy](http://www.haproxy.org/)

License
-------

BSD