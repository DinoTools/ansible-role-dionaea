dionaea honeypot
================

Use ansible to install and/or update your dionaea honeypot.

Requirements
------------

none

Role Variables
--------------

Available variables are listed below, along with default values:

    dionaea_dest_base_path: /opt/dionaea
    dionaea_repo_dir: dionaea_dest_base_path + git
    dionaea_repo_url: https://github.com/DinoTools/dionaea.git 
    dionaea_user: dionaea
    dionaea_version: master
    dionaea_version_file: dionaea_dest_base_path + installed_version

Dependencies
------------

- ansible >= 2.0

Example Playbook
----------------

    - hosts: servers
      roles:
      - dinotools.dionaea

License
-------

MIT
