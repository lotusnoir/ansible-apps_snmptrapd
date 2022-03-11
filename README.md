# ansible-apps_snmptrapd

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_snmptrapd-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_snmptrapd)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_snmptrapd.svg)](https://github.com/lotusnoir/ansible-apps_snmptrapd/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_snmptrapd?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56102)](https://galaxy.ansible.com/lotusnoir/apps_snmptrapd)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56102)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and configure snmptrapd to receive and store traps snmp cfrom network equipments.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_snmptrapd
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_snmptrapd


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

