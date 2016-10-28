[![Build Status](https://travis-ci.org/opspluslove/ansible-docker-compose.svg?branch=master)](https://travis-ci.org/opspluslove/ansible-docker-compose)

docker-compose
======

Ansible role to install docker-compose

Role Variables
--------------

```
# Defaults
dockercompose_py_version: 1.9.0rc1
dockercompose_version: 1.9.0-rc1
dockercompose_platform: Linux-x86_64
dockercompose_url: https://github.com/docker/compose/releases/download/{{ dockercompose_version }}/docker-compose-{{ dockercompose_platform }}
dockercompose_install_dir: /usr/local/bin/docker-compose
```

Example Playbook
----------------

_TODO_
