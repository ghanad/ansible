Role Name
=========

install cassandra cluster.

Requirements
------------

put apache-cassandra*.tar.gz in `/opt/` on local machine

java

Role Variables
--------------

All variables are in default/main.yml



Example Playbook
----------------

    - hosts: servers
      roles:
         - cassandra
