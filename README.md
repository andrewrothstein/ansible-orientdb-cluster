andrewrothstein.orientdb-cluster
=========

Configures an [OrientDB](http://orientdb.com/) cluster

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

See [test.yml](test.yml) and [test-inventory.ini](test-inventory.ini) for an example single node localhost cluster

```yml
- hosts: orientdb
  roles:
    - andrewrothstein.orientdb-cluster
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
