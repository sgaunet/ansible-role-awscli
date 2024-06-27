
# Ansible Role: awscli

[![CI](https://github.com/sgaunet/ansible-role-awscli/workflows/CI/badge.svg?event=push)](https://github.com/sgaunet/ansible-role-awscli/actions?query=workflow%3ACI)

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
