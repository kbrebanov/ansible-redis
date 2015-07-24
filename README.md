redis
=====

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-kbrebanov.redis-660198.svg)](https://galaxy.ansible.com/list#/roles/3957)

Installs and configures Redis

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name            | Default                                                          | Description                   |
|-----------------|------------------------------------------------------------------|-------------------------------|
| redis_version   | 3.0.3                                                            | Version of Redis to install   |
| redis_sha256sum | 1d08fa665b16d0950274dfbd47fbbcf3485e43e901021338640a0334666e9da5 | SHA 256 checksum of package   |

Dependencies
------------

None

Example Playbook
----------------

Install Redis
```
- hosts: all
  roles:
    - { role: kbrebanov.redis }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
