redis
=====

Installs and configures Redis

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name            | Default                                                          | Description                 |
|-----------------|------------------------------------------------------------------|-----------------------------|
| redis_version   | 3.0.1                                                            | Version of Redis to install |
| redis_sha256sum | 0e21be5d7c5e6ab6adcbed257619897db59be9e1ded7ef6fd1582d0cdb5e5bb7 | SHA 256 checksum of package |

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
