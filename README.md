redis
=====

[![Build Status](https://travis-ci.org/kbrebanov/ansible-redis.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-redis)

Installs and configures Redis

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name            | Default                                                          | Description                  |
|:----------------|:-----------------------------------------------------------------|:-----------------------------|
| redis_version   | 3.2.4                                                            | Version of Redis to install  |
| redis_sha256sum | 2ad042c5a6c508223adeb9c91c6b1ae091394b4026f73997281e28914c9369f1 | SHA 256 checksum of package  |
| redis_port      | 6379                                                             | Port that Redis will bind to |


Dependencies
------------

None

Example Playbook
----------------

Install Redis
```yaml
- hosts: all
  roles:
    - kbrebanov.redis
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
