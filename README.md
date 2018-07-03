Role Name
=========

Role to mount FileSystem.

Requirements
------------

None.

Role Variables
--------------

lagoon\_fs\_dev: device to mount
lagoon\_fs\_mount: filesystem 

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lagoon.filesystem, lagoon_fs_dev: 'xvdf', lagoon_fs_mount: '/data1' }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
