redis
=====

[![Ansible Role](https://img.shields.io/ansible/role/3957.svg)](https://galaxy.ansible.com/list#/roles/3957)

Installs and configures Redis

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name            | Default                                                          | Description                 |
|:----------------|:-----------------------------------------------------------------|:----------------------------|
| redis_version   | 3.2.0                                                            | Version of Redis to install |
| redis_sha256sum | 989f1af3dc0ac1828fdac48cd6c608f5a32a235046dddf823226f760c0fd8762 | SHA 256 checksum of package |

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
