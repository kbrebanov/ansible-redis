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
| redis_version   | 3.0.5                                                            | Version of Redis to install  |
| redis_sha256sum | 4c176826eee909fbdc63db1c15adc22aab42d758043829e556f4331e6a5bd480 | SHA 256 checksum of package  |
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
