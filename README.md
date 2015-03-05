Ansible OpenSSH Role
=====================

An ansible role for installing and configuring OpenSSH

Role Variables
--------------

- openssh_config_path: path to openssh config
- openssh_client_settings: dict containing openssh client settings
- openssh_server_settings: dict containing openssh server settings

View the default vars - defaults/main.yml - for a more detailed example.


Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: MichaelRigart.openssh }

License
-------

GPLv3

Author Information
------------------

Michaël Rigart <michael@netronix.be>