Ansible Role: MeCab
=========

[![Build Status](https://travis-ci.org/pastelInc/ansible-role-mecab.svg?branch=master)](https://travis-ci.org/pastelInc/ansible-role-mecab)

Installs Nginx on RedHat/CentOS servers.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    mecab_yum_repo_enabled: true
    mecab_packages: []

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: pastelInc.mecab }

License
-------

MIT / GPLv2 / GPLv3 / BSD

Author Information
------------------

This role was created in 2017 by [pastelInc](https://github.com/pastelInc).
