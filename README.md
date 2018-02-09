# Ansible Role: Docker CE
[![Travis branch](https://img.shield.io/travis/marthydavid/docker-ce-machine-role/master.svg)](https://travis-ci.org/marthydavid/docker-ce-machine-role)[![Ansible Role](https://img.shields.io/ansible/role/23633.svg)](https://galaxy.ansible.com/marthydavid/docker-ce-machine)


An Ansible Role that installs Docker CE on RHEL/CentOS, Fedora, Debian/Ubuntu

## Requirements

None.

## Dependencies

None.

## Example Playbook
    - hosts: docker
      roles:
        - { role: marthydavid.docker-ce-machine }

## License

MIT

This role was created in 2018 by David Marthy



