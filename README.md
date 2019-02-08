Role Name
=========

This role install helm command on a linux distribution.
It configures also bash completion.

Requirements
------------

For the moment, only ubuntu > 16.04 is supported

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Minimal playbook:

    - name: install helm
      hosts: localhost
      roles:
        - helm-cli

Using the example playbook
--------------------------

    cd ..
    ansible-playbook -K -i localhost helm-cli/playbook-example.yml

License
-------

BSD

Author Information
------------------

Mouhamed Fall