OULibraries.docker-host
=========

Installs Docker CE from the Docker provided packages.

Requirements
------------

Expects a CentOS 7x target host

Role Variables
--------------

See `defaults/main.yml`. 

No configuration is needed for a simple docker host. 


Dependencies
------------

None, but this role may be used in conjunction with [OULibraries.python3](https://github.com/OULibraries/ansible-role-python3) to install `docker-compose`. 


Example Playbook
----------------

- hosts: all
  roles:
   - OULibraries.docker-host


License
-------

BSD

Author Information
------------------
OU Libraries

