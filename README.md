hashicorp-Vault
=========

Ansible role for installing hashicorp vault on Ubuntu

Requirements
------------

Linux server with SSH access

Role Variables
--------------
    
    vault_version: 1.5.3
    vault_server_Address: 127.0.0.1
    

    
Example Playbook
----------------
    - hosts: vault
      roles:
         - { role: jobin_james.hashicorp_vault }

License
-------

BSD

Author Information
------------------
Jobin James