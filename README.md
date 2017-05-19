Ansible role: Elasticsearch
=========

Installs and configures [Elasticsearch](https://www.elastic.co/products/elasticsearch).

Requirements
------------

None.

Role Variables
--------------

    elasticsearch_port: 9200
    elasticsearch_host: 0.0.0.0

Dependencies
------------

- shomatan.java

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.elasticsearch }

License
-------

MIT

Author Information
------------------

Shoma Nishitateno