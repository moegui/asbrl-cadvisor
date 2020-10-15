ASBRL-CADVISOR
=========

Deploy an official CADVISOR.

Requirements
------------

- Need to be Docker engine installed.

Role Variables
--------------

- BUILD: 'latest'
- CADVISOR_PORT: 9080
- CONTAINER_NAME: "cadvisor"
- DOCKER_CPU_PERIOD: 0
- DOCKER_CPU_QUOTA: 0
- DOCKER_MEMORY: 0
- CONTAINER_STATE: 'started'

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
