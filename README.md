[![Build Status](https://travis-ci.org/opspluslove/ansible-docker-compose.svg?branch=master)](https://travis-ci.org/opspluslove/ansible-docker-compose)

docker-compose
======

In your [requirements file](https://galaxy.ansible.com/intro):

```
- src: opspluslove.docker-compose
  version: v1.5.1
```

----

Ansible role to install docker-compose

Requirements
------------

- Python 2.6+

Role Variables
--------------

```
# Defaults
docker_py_version: 1.9.0
dockercompose_py_version: 1.8.0
dockercompose_version: 1.8.0
dockercompose_platform: Linux-x86_64
dockercompose_url: https://github.com/docker/compose/releases/download/{{ dockercompose_version }}/docker-compose-{{ dockercompose_platform }}
dockercompose_install_dir: /usr/local/bin/docker-compose
```

Example Playbook
----------------

_TODO_
