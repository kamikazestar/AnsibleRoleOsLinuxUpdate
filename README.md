AnsibleRoleOsLinuxUpdate
=========

This role will update Apt cache on Debian based operating systems, and perform also safe upgrade.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

Below ther's example playbook which can be used:

    - hosts: servers
      roles:
         - { role: kamikazestar.AnsibleRoleOsLinuxUpdate }

License
-------

MIT

Author Information
------------------

[Marcin Slabonski](https://github.com/kamikazestar)
