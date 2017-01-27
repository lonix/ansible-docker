Role Name
=========

This role will install latest docker from docker.io's offical repo.

Requirements
------------

- none

Role Variables
--------------

- update_docker_package : Will update to latest if not already up-to-date
                          false\no will only install not update.

Dependencies
------------

- none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
   passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lonix.docker, update_docker_package: true }

License
-------

MIT
