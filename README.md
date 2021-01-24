andrewrothstein.node_exporter
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-node_exporter.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-node_exporter)

Installs and configures the Prometheus node_exporter

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
    - andrewrothstein.node_exporter
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
