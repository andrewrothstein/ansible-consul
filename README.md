[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-consul.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-consul)
andrewrothstein.consul
======================

installs [Consul](https://www.consul.io/)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------
```yml
- hosts: servers
  roles:
    - andrewrothstein.consul
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
