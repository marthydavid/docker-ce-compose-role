# Ansible Role: Docker CE
[![Build Status](https://travis-ci.org/marthydavid/docker-ce-compose-role.svg?branch=master)](https://travis-ci.org/marthydavid/docker-ce-compose-role) [![Ansible Role](https://img.shields.io/ansible/role/23631.svg)](https://galaxy.ansible.com/marthydavid/docker-ce-compose)

An Ansible Role that installs Docker CE on RHEL/CentOS, Fedora, Debian/Ubuntu

## Requirements

None.

## Dependencies

None.

## Example Playbook
    - hosts: docker
      roles:
        - { role: marthydavid.docker-ce-compose }

## License

MIT

This role was created in 2018 by David Marthy



