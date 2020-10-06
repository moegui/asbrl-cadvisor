ASBRL-CADVISOR
=========

Deploy an official CADVISOR.

Requirements
------------

- Need to be Docker engine installed.

Role Variables
--------------

- BUILD: 'v1.0.0'
- CADVISOR_PORT: "8090"

Dependencies
------------

None

Example Playbook
----------------

    - name: Deploy Node Exporter
      vars:
        CADVISOR_PORT: "8090"
      include_role:
        name: asbrl-cadvisor
      tags:
        - asbrl-cadvisor

License
-------

BSD

Author Information
------------------

Moegui.com
