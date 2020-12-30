# sbog/syslog

[![Build Status](https://travis-ci.com/sorrowless/ansible_syslog.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_syslog)
[![Ansible Role](https://img.shields.io/ansible/role/52550)](https://galaxy.ansible.com/sorrowless/syslog)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/52550)](https://galaxy.ansible.com/sorrowless/syslog)
[![Ansible Role](https://img.shields.io/ansible/role/d/52550)](https://galaxy.ansible.com/sorrowless/syslog)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_syslog)](https://github.com/sorrowless/ansible_syslog/blob/master/LICENSE)

An Ansible role which installs and configures [syslog](https://www.syslog-ng.com) on Linux

## Requirements

Ansible 2.7+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure syslog
  hosts: syslogs

  roles:
    - syslog
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
