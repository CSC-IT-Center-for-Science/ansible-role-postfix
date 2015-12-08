ansible-role-postfix
=========

Sets inet_protocols to ipv4

There are many other/better ansible-roles that configures postfix more completely. This role uses the defaults in EL7 and only sets it to ipv4 only.

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-postfix }

License
-------

MIT

Author Information
------------------
