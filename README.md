AnsibleRoleOsLinuxUpdate
=========

This role will update Apt or Yum cache on Linux based operating systems.
On Debian based operating systems this role will perform also safe upgrade.

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
