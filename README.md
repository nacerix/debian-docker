Role Name
=========

nacerix.debian-docker installs the docker and the necessary pre-requisites on debian systems.
Only jessie and wheezy are supported by this role.

Requirements
------------

No particular requirement is needed for this role to be installed.

Role Variables
--------------

This role’s usage is simple and only need one variable, apt_mirror which is the url of the apt mirroring server. By default:

apt_mirror = "http://http.debian.net/debian"

Dependencies
------------

This role has no dependency.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: nacerix_debian-docker, apt_mirror: "http://http.debian.net/debian" }

License
-------

BSD

Author Information
------------------

Nacer Adamou Saidou <adamou.nacer@gmail.com>
