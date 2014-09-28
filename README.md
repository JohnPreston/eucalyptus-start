eucalyptus-start
================

Register all the Eucalyptus cloud components all together

** *WARNING !!!* **
*This role has to be used in the deployment of Eucalyptus cloud !*

Requirements
------------

hosts:

- clc | Cloud Controller

- ufs | User Facing Services

- cc | Cluster Controllers

- sc | Storage Controllers

- nc | Node Controllers

- walrus | S3 builtin-backend


Role Variables
--------------

None

Dependencies
------------

- JohnPreston.eucalyptus-register

Example Playbook
----------------

```

- hosts: all
  roles:
  - JohnPreston.eucalyptus-start

```

License
-------

Apache

Author Information
------------------

John Preston [John Mille]

