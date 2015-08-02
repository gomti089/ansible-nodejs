NodeJS
======

Ansible role for installing nodejs from NodeSource RPMs

https://github.com/nodesource/distributions


Requirements
------------

Currently only for CentOS 6 & 7.


Role Variables
--------------

* `nodejs_version: 0.12.7` a supported nodejs version
* `nodejs_global_packages: [ ]` a names of global npm packages to install

Example Playbook
----------------

    - hosts: example
      roles:
      - role: advertine.nodejs
        nodejs_version: "0.10.40"
        nodejs_global_packages:
          - jake
          - clean-css

License
-------

BSD

Author Information
------------------

Rafał Michalski

