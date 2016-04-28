troykinsella.python
===================

An ansible role to install python, pip, and python packages.

Role Variables
--------------

* python_packages: (array) List of package names. Default: [].
* python_legacy_support: (bool) Use pip2. Default: no.
* python_pip_download_url: (string) The URL at which the pip installer can be downloaded. Default: https://bootstrap.pypa.io/get-pip.py.
* python_pip_executable: (string) Path to the pip executable.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: troykinsella.python

License
-------

MIT
