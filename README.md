# Ansible Role: apt_mirror

[![Lint](https://github.com/dcjulian29/ansible-role-apt_mirror/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-apt_mirror/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-apt_mirror.svg)](https://github.com/dcjulian29/ansible-role-apt_mirror/issues)

This an Ansible role to set up an APT package mirror

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.apt_mirror
  src: https://github.com/dcjulian29/ansible-role-apt_mirror.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
