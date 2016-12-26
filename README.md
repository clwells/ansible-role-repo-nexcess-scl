# Ansible Role: Nexcess SCL Yum Repo

Installs Necxess' SCL repo for RHEL/CentOS.

## Requirements

This role only is needed/runs on RHEL and its derivatives.

## Role Variables

See `defaults/main.yml`.

## Dependencies

None.

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-repo-nexcess-scl.git
      name: nexcess.repo-scl

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.repo-scl

## License

MIT / BSD
