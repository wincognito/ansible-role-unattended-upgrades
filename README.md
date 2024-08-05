Unattended Upgrades
=========

Configures unattended upgrades on Debian.  
Based on:  
https://wiki.debian.org/UnattendedUpgrades

You can check, what unattended upgrades will do like that:

```
sudo unattended-upgrades --dry-run --debug
```

Requirements
------------

Debian OS.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- name: Unattended Upgrade
  hosts: all
  gather_facts: false
  roles:
  - ansible-role-unattended-upgrades
```

License
-------

MIT

Author Information
------------------

Pawel Idzikowski
Wincognito
