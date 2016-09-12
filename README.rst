===================
ansible-role-bindep
===================

Ansible role to manage Bindep

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-bindep.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-bindep
* Bugs: https://bugs.launchpad.net/ansible-role-bindep

Description
-----------

Bindep is a tool for checking the presence of binary packages needed to use an
application / library.

Requirements
------------

See `bindep.txt` for role dependencies.

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install bindep
      hosts: nodepool
      roles:
        - ansible-role-bindep
