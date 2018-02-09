# Ansible Role: Docker CE
[![Travis branch](https://img.shields.io/marthydavid/docker-ce-compose-role/master.svg)](https://travis-ci.org/marthydavid/docker-ce-compose-role) [![Ansible Role](https://img.shields.io/ansible/role/23631.svg)](https://galaxy.ansible.com/marthydavid/docker-ce-compose)

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



