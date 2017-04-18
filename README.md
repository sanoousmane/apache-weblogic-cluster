Configuring WLS Web Server Proxy Plug-In for Apache HTTP Server
=========

This role installs and configures WLS Web Server Proxy Plug-In for Apache HTTP Server on oracle linux.

Requirements
------------
This role requires Ansible 1.9 or higher and platform requirements are listed in the metadata file.

Minimum of two oracle linux 7

httpd 2.2 required

Role Variables
--------------

node1: oracle1

node2: oracle2

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: weblogic
      remote_user: root
      roles:
         - { role: apache-weblogic-cluster }

License
-------

BSD

Author Information
------------------

Ousmane Sanogo http://www.sanogo.net
