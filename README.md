gnome_disable_inital_setup
==========================
[![Ansible Lint](https://github.com/oxivanisher/role-gnome_disable_inital_setup/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-gnome_disable_inital_setup/actions/workflows/ansible-lint.yml)

Disable initial setup stuff on Ubuntu Desktops.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Debian clients
  hosts: debian
  roles:
    - role: oxivanisher.linux_desktop.gnome_disable_inital_setup
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
