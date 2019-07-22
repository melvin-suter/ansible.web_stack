Web-Stack Setup with Ansible
===========================

This Ansible Role installs, configures a complete web-stack on a linux server.
* `Install and configure MariaDB`
* `Install and configure Apache`
* `Install and configure Node`

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role

Role Variables
--------------

Variables are self speaking or documented in:   
* `defaults/main.yml`

Dependencies
------------

This Ansilbe Role has dependencies to these Ansilbe Roles:
* `uniqconsulting.mariadb`
* `melvin_suter.firewalld`

Example Playbook
----------------

Example playbooks for this role are located in ´test´ folder:
* `tests/playbook_webstack.yml`
