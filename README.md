Ansible DB-pull role
====================

Sync local PostgreSQL or MySQL database with remote.

Requirements
------------

The following CLI commands need to be installed on your system / Docker image :

- PostgreSQL: `pg_dump` and `pg_restore`
- MySQL: `mysqldump` and `mysql`

Role Variables
--------------

`defaults` vars declared in this module can be found here: [defaults/main.yml](defaults/main.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: db-pull }

License
-------

MIT

Author Information
------------------

* ansible-db-pull, written by Erwan Richard
