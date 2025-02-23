Install Factorio server
=========

Install Factorio server

Role Variables
--------------

```factorio_save_name``` should be used to set the save name for the factorio world

The user running factorio can be set with ```factorio_user``` and ```factorio_group```

```factorio_install_location``` can be set to the install location for factorio

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: tychobrouwer.factorio
      
    - role: tychobrouwer.factorio
      factorio_save_name: factory
      factorio_install_location: /opt
      factorio_user: factorio
      factorio_group: factorio
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
