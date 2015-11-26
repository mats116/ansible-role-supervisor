# README.md
# Ansible Role: mats116.supervisor

An Ansible role that installs Supervisor on **Ubuntu 14.04 LTS**

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

    supervisor_version: "3.0"

    crashmail_address: example@example.com

## Dependencies

none

## Example Playbook

    - hosts: web-server
      roles:
        - role: mats116.supervisor
          crashmail_address: hoge@gmail.com

## License

MIT
