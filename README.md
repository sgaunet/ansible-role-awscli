[![Tag](https://img.shields.io/github/v/tag/sgaunet/ansible-role-awscli.svg)](https://github.com/sgaunet/ansible-role-awscli/tags)
[![CI](https://github.com/sgaunet/ansible-role-awscli/actions/workflows/ci.yml/badge.svg)](https://github.com/sgaunet/ansible-role-awscli/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/sgaunet/ansible-role-awscli.svg)](LICENSE)

# Ansible Role: awscli

An Ansible Role that installs awscli on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    awscli_version: "2.7.21"
    awscli_os: "linux"
    awscli_arch: "x86_64"

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - sgaunet.awscli
```

## License

MIT
