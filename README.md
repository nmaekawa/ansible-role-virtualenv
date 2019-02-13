python virtualenv
=========
Simple ansible role to create a python virtualenv on ubuntu.
It refers to python2|python3 (default python3), so it fails in ubuntu < 16.04.


requirements
------------

Ubuntu 16.04



example playbook
----------------

    - hosts: all
      roles:
         - role: ansible-role-virtualenv
           venv_path: "/path/to/virtualenv/to/be/created"
           venv_user: "owner_of_venv"
           venv_group: "group_of_venv"
           venv_python_version: 2  # default is 3

license
-------

Apache2


