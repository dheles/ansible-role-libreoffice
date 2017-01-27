Ansible Role: LibreOffice
=========

Installs the LibreOffice Free and Open Source office suite

Requirements
------------

Java

Role Variables
--------------

TBD

Dependencies
------------

My java role (https://github.com/dheles/ansible-role-java), or any other role providing java >= 1.7 (and answering to the name "java")

Example Playbook

    - hosts: servers
      roles:
         - { role: libreoffice }

License
-------

CC0

Author Information
------------------

Drew Heles
