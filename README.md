andrewrothstein.orientdb-cluster
=========

Configures an [OrientDB](http://orientdb.com/)

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

See [test.yml](test.yml) and [inventory.ini](inventory.ini) for a single pseudo cluster

```yml
- hosts: servers
  roles:
    - username.rolename
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
