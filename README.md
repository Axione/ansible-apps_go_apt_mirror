# ansible-apps_go_apt_mirror

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_go_apt_mirror-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_go_apt_mirror)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_go_apt_mirror.svg)](https://github.com/lotusnoir/ansible-apps_go_apt_mirror/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_go_apt_mirror?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_go_apt_mirror)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_go_apt_mirror)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_go_apt_mirror)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Deploy [go-apt-mirror](https://github.com/cybozu-go/aptutil) an apt cacher like acng but in go.
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_go_apt_mirror
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_go_apt_mirror


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
