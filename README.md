Role Name
=========

This role is to install My SQL

Requirements
------------

Role Variables
--------------
db_name: employee_db
db_user
db_password

Dependencies
------------

Example Playbook
----------------

- name: Deploy MySQL server
  hosts: dbserver1,dbserver2
  roles:
     - mysql_db	
License
-------

BSD

Author Information
------------------
Adeel Shafqat www.zaynsolutions.com
