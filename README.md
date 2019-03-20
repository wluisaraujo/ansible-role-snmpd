[![Build Status](https://travis-ci.org/wluisaraujo/iac-snmp-agent.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-snmp-agent)
---
## IaC: with [Ansible](https://www.ansible.com) role to install and configure [(Linux)SNMP Agent](www.net-snmp.org/)
------------

Description
------------

 * Ansible for SNMP Agent

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-snmp-agent
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
