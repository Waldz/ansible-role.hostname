# ansible-role.hostname

Install
========
```
git submodule add git@github.com:Waldz/ansible-role.hostname.git roles/hostname
```

Example
========
```
- name: Basic configuration to all servers
  hosts: all
  sudo: true
  roles:
    - role: hostname
  vars:
    - hostname: myserver.com
```
