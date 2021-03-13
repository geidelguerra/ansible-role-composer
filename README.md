ansible-role-composer
=========

Installs Composer

Requirements
------------

None

Role Variables
--------------

composer_install_path: /urs/bin/composer

Dependencies
------------

None

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: geidelguerra.ansible-role-composer, composer_install_path: '/usr/bin/composer' }

License
-------

MIT

Author Information
------------------

Geidel Guerra
