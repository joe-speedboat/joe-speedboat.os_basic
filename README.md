
OS Basic Setup with Ansible
===========================

This Ansible Role configure and update a Linux server. The following tasks will be configured:
* `Basic Package installation`
* `OS Update (Full Update / Security Update)`
* `EPEL-Repository`
* `Network Settings`
* `FirewallD / iptables`
* `SELinux`
* `Rsyslog`
* `SNMP`

Requirements
------------

* Currently only tested with CentOS 8
* Ansible 2.9 or higher is required for this Ansible Role

Role Variables
--------------
Please look into tests folder

Dependencies
------------

This Ansilbe Role has no dependencies to other Ansilbe Roles

Example Playbook
----------------

Example playbooks for this role are located in the ´test´ folder.


License
-------
https://opensource.org/licenses/LGPL-3.0    
Copyright (c) Chris Ruettimann<chris@bitbull.ch>
