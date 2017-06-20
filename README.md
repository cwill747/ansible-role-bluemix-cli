cwill747.bluemix-cli
=========
[![Travis](https://img.shields.io/travis/cwill747/ansible-role-bluemix-cli.svg)]()

This ansible role installs the Bluemix CLI on a remote Linux machine

Requirements
------------

There are no requirements for this role

Role Variables
--------------

You can choose a specific version of the Bluemix CLI using the provided role variables.

```
bx_version: latest
bx_arch: amd64
```

You can set this to something like `0.5.4` to specify a specific version. If you want a different arch (i386 or amd64),
pass that as the `bx_arch` variable. For whatever change, you can include the sha256 for verification as the `bx_sha256`
variable.

Dependencies
------------

No depencencies for this role.

Example Playbook
----------------


```yaml
    - hosts: localhost
      roles:
        - { role: cwill747.bluemix-cli }
```

License
-------

MIT
