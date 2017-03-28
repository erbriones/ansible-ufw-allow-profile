ansible-ufw-allow-profile
-------------------------

[![Build Status](https://travis-ci.org/erbriones/ansible-ufw-allow-profile.svg?branch=master)](https://travis-ci.org/erbriones/ansible-ufw-allow-profile)

Creates and allows custom ufw application.d profiles

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: erbriones.ufw-allow-profile, ufw_name: nginx, ufw_ports: 80/tcp, ufw_description: Web server}

License
-------

The MIT License. See the [LICENSE file](https://github.com/erbriones/ansible-ufw-allow-profile/blob/master/LICENSE).
