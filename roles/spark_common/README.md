Spark Common
=========

Common task for setup spark cluster

Requirements
------------

Role Variables
--------------

spark_download_url:
spark_version:
spark_root:

Dependencies
------------
- malk.ansible-java8-oracle

Example Playbook
----------------

- hosts: servers
  roles:
    - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
