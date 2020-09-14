[![Build Status](https://travis-ci.org/sendinblue/ansible-role-hello-world.svg?branch=master)](https://travis-ci.org/sendinblue/ansible-role-hello-world)
[![Ansible Galaxy](https://img.shields.io/badge/role-sendinblue.hello_world-blue.svg)](https://galaxy.ansible.com/sendinblue/hello_world/)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/sendinblue/ansible-role-hello-world)](https://galaxy.ansible.com/sendinblue/hello_world)
[![Ansible Galaxy Quality Score](https://img.shields.io/ansible/quality/49634)](https://galaxy.ansible.com/sendinblue/hello_world/)
[![Ansible Galaxy Downloads](https://img.shields.io/ansible/role/d/48974.svg?color=blue)](https://galaxy.ansible.com/sendinblue/hello_world/)

# Ansible Role: Hello World

A boilerplate Ansible Role with the integration of [Molecule](https://molecule.readthedocs.io/en/latest/) testing framework, [Ansible Galaxy](https://galaxy.ansible.com/) and [Travis CI](https://travis-ci.org/).

## Role Variables

Available variables listed below, along with default values (see `defaults/main.yml`):

    hello_world_message: Hello World!

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - sendinblue.hello_world

## Development

Use [docker-molecule](https://github.com/nl2go/docker-molecule) following the instructions to run [Molecule](https://molecule.readthedocs.io/en/stable/)
or install [Molecule](https://molecule.readthedocs.io/en/stable/) locally (not recommended, version conflicts might appear).

Provide Hetzner Cloud token:

    export HCLOUD_TOKEN=123abc456efg

Use following to run tests:

    molecule test --all

## Maintainers

- [build-failure](https://github.com/build-failure)

## License

See the [LICENSE.md](LICENSE.md) file for details.

## Author Information

This role was created in 2020 by [Sendinblue GmbH](https://www.sendinblue.de/).
