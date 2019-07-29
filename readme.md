ansible-role-proxmox
=========

Install proxmox on single nodes.

Requirements
------------

Ansible > 2.8

Role Variables
--------------

```
pve_release_key: proxmox-ve-release-5.x.asc
pve_release_key_id: 0D9A1950E2EF0603
```

On earlier tests, I couldn't get pve 5 key working with ansible apt_key mod
so had to use a work around.

Dependencies
------------

None.

License
-------

GPLv3

Author Information
------------------

Richard Skumat

https://github.com/richardskumat