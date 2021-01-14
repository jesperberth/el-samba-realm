el-samba-realm
=========

Install Samba with ad integration

Requirements
------------


Role Variables
--------------

*  ad_server_user - username for admin
*  ad_server_pass - password for admin
*  ad_server_domain - domain name
*  ad_server_domain_short - domain name - short
*  ip_allow - ip network to allow access in samba

´´´bash

---
ad_server_user: Administrator
ad_server_pass: Your Password
ad_server_domain: domain.local
ad_server_domain_short: domain
ip_allow: 192.168.0

´´´´

Dependencies
------------

Needs jesperberth.el_domain_join

Example Playbook
----------------

    - hosts: servers
      roles:
         - jesperberth.el_samba_realm

License
-------

BSD

Author Information
------------------

Jesper Berth
