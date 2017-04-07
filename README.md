Java
====

Ansible Role to install OpenJDK.

Requirements
------------

No requirements.

Role Variables
--------------

Enable JDK installation, default is to only install JRE.

```
java_install_jdk: false
```

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: rvalente.java }

License
-------

See `LICENSE`

Author Information
------------------

Ronald Valente
