couchbaselabs.cbas
=========

NoSQL Analytics Service for Couchbase

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

cbas_version
cbas_basedir
cbas_confdir
cbas_logdir
cbas_installdir

Dependencies
------------

Requires: Java, unzip

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache

