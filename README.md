troykinsella.python
===================

An ansible role to install python3, pip, and python packages.

Role Variables
--------------

See `default/main.yml` for defaults.

* `python_apt_packages`: Optional. List of apt packages to install.
* `python_packages`: Optional. List of package names.
* `python_pip_executable`: Optional. Path to the pip executable.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: troykinsella.python

License
-------

MIT
