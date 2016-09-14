Ansible Role:  selinux
=========
[![Build Status](https://travis-ci.org/biggsean/ansible-role-selinux.svg?branch=master)](https://travis-ci.org/biggsean/ansible-role-selinux)

Simple role to install selinux.

Requirements
------------

None

Role Variables
--------------

All variables are defined in defaults.
### selinux_state
Default *enforcing*
### selinux_policy
Default *targeted*

Dependencies
------------

None

Example Playbook
----------------

```
- hosts: servers
  roles:
    - biggsean.selinux
```

License
-------

MIT

