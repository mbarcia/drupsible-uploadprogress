drupsible.uploadprogress
========================

Installs and configure the PECL uploadprogress extension. 

Requirements
------------

This role requires PHP5 FPM (Fast Process Manager) to be present. 
This role can be used indepedently and does NOT require Drupsible to run.

Example Playbook
----------------

- name: PECL uploadprogress
  hosts: localhost
  become: True
  roles:
    - role: drupsible.uploadprogress

License
-------

GNU General Public License v3

Author Information
------------------

Mariano Barcia - [https://github.com/mbarcia](https://github.com/mbarcia)
