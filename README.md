[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

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
| redis_version   | 3.2.9                                                            | Version of Redis to install  |
| redis_sha256sum | 6eaacfa983b287e440d0839ead20c2231749d5d6b78bbe0e0ffa3a890c59ff26 | SHA 256 checksum of package  |
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
