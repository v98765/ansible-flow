Ansible Role: Netflow, Sflow collector
=========

Deploy and configure nfdump, nfdump-sflow for ubuntu.

Requirements
------------

Ansible

Role Variables
--------------

All variables which can be overridden are stored in defaults/main.yml

Example Playbook
----------------

```text
---
- hosts: flow
  connection: ssh
  become: yes
  roles: 
    - ansible-flow
```

License
-------

BSD
