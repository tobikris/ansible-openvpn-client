OpenVPN Client
=========

Configure multiple instances of OpenVPN clients at the same time.

Requirements
------------

No requirements.

Role Variables
--------------

See `defaults/main.yml`.

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tobikris.openvpn-client }

License
-------

BSD
