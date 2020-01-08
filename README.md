ansible-role-tmux
=========

Installs tmux from source

Requirements
------------

EPEL

Role Variables
--------------

```yaml
tmux_force_install: false
tmux_install_version: "2.9"
```

Dependencies
------------

`geerlingguy.git`

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - { role: username.rolename, x: 42 }
```

License
-------

MIT

Author Information
------------------

Jonathan Scherrer