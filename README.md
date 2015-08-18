Ansible OpenSSH Role
=====================
[![Build Status](https://semaphoreci.com/api/v1/projects/2d3a0067-6709-4238-86e4-0025b4530141/461765/badge.svg)](https://semaphoreci.com/michaelrigart/ansible-role-openssh)

An ansible role for installing and configuring OpenSSH

Role Variables
--------------

```yaml
openssh_config_path: path to openssh config
openssh_client_settings: dict containing openssh client settings
openssh_server_settings: dict containing openssh server settings
```

View the default vars - defaults/main.yml - for a more detailed example.

Example Playbook
-------------------------

```yaml
- hosts: servers
  roles:
     - { role: MichaelRigart.openssh, sudo: Yes }
```

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>
