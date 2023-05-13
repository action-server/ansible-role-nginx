ansible-role-nginx
=========

Ansible role to install and configure nginx.

Requirements
------------

Host must have python and an ssh key configured.

It also only works with the ufw firewall at the moment, so make sure it's installed and configured

Example Playbook
----------------

    - hosts: servers
      roles:
         - nginx

License
-------

GNU General Public License v3.0
