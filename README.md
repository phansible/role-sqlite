# Phansible Role: SQLite

[![CI](https://github.com/phansible/role-sqlite/actions/workflows/ci.yml/badge.svg)](https://github.com/phansible/role-sqlite/actions/workflows/ci.yml)

An Ansible Role that installs the [SQLite](https://www.sqlite.org/) command line shell (`sqlite3`) from the distribution packages on Ubuntu and Debian, created with [Phansible](http://phansible.com/) in mind.

## Requirements

- Ubuntu 22.04, 24.04, 26.04 or Debian 12, 13 (x86_64)
- Ansible >= 2.15
- Root access or `become` on the target

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - role-sqlite
```

## License

This role is released under the terms of the license specified in the repository or if not specified, under the [MIT license](https://raw.githubusercontent.com/phansible/role-sqlite/master/LICENSE).

## Author Information

This role was created in 2015 by [The Phansible Team & Contributors](https://github.com/phansible/role-sqlite/graphs/contributors), credits go also to [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/) and source of inspiration.
