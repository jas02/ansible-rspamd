rspamd
=========

Install and configure Rspamd

Requirements
------------
For supported systems see https://rspamd.com/downloads.html. This role will only support debian and unbuntu.

Role Variables
--------------

please take a look to defaults/main.yml

Dependencies
------------
This role needs a installed and configured redis. (I suggest geerlingguy.redis)

Example Playbook
----------------
To install role, add following line to **ansible-galaxy** requirements file

```
- name: geerlingguy.redis
  version: 1.7.0
- name: jas02.rspamd
```

```
- hosts: servers
  roles:
    - jas02.rspamd
```

License
-------

BSD

Author Information
------------------

- Lumir Jasiok (lumir.jasiok@alfawolf.eu)
