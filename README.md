Lighthouse
=========

This role installs and configures the lighthouse.

Role Variables
--------------

_lighthouse_path_ - where to install lighthouse site, default "/opt/lighthouse" </br>

Example Playbook
----------------

You can use this role simple like this:

    - hosts: servers
      roles:
         - { role: lighthouse, lighthouse_path: "/opt/lighthouse" }

License
-------

MIT

Author Information
------------------

Nikolay Mokrov
