nextcloud
=========

Install a nextcloud server on bare metal.
Still work in progress. Yet useable. The beauty comes later.

Requirements
------------

only tested on:
Ubuntu 20.04
php 7.4
nginx
mariadb

Root-access

Role Variables
--------------

in progress

Example Playbook
----------------

```yaml
---
- name: Server set up
  hosts: all
  roles:
    - name: nextcloud
      role: nextcloud
```

License
-------

MIT

Author Information
------------------

ra-rau
