MySQL
=========

Ansible role for installing jenkins. Tested platforms are:
* Debian 9
* Ubuntu 16

Requirements
------------

Debian 9 (stretch)
Ubuntu 16 (xenial)

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

| Parameter | Required | Default | Choices | Comments |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| default_jenkins_port | yes | 8080 | | Sets Jenkins server port |


Dependencies
------------

None

Example 
----------------
    ---
    - hosts: all
      roles:
         - { role: antonchernik.jenkins }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2018 by [Anton Chernik](https://github.com/antonchernik).
