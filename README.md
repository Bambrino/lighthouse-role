Role Name
=========

Simple role for lighthouse installation on CentOS7. Included: unzip and nginx

Requirements
------------

CentOS7

Role Variables
--------------

There is no option for install, except nginx port. Default port set 80.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: lighthouse-role
          vars:
            nginx_port: 8080

License
-------

BSD

Author Information
------------------

Bambrino
