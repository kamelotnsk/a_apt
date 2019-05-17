Apt [stable]
============

Role provides manipulating `apt` packages.

Role Variables
--------------

```
apt_keys_default: []
apt_repos_default: []
apt_packages_default: []

apt_keys: []
apt_repos: []
apt_packages: []
```

Requirements
------------

none

Example Playbook
----------------

```
- hosts: debian
  roles:
    - { role: apt, apt_packages: vim }
```

```
apt_packages_default:
  - name:
    - htop
    - zsh
```

License
-------

Proprietary
