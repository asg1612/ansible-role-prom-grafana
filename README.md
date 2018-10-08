Role Prometheus + Graphana
=========

Deploy [Prometheus](https://prometheus.io/) + [Graphana](https://grafana.com/) using docker containers.

The main goal is deploy on Docker Swarm

Requirements
------------
Docker


Role Variables
--------------
volumes:
- **source_data_prom**: Souce path to data prometheus.
- **target_data_prom**: target path to Prometheus.
- **source_data_graf**: Path to store Grafana data.


Dependencies
------------
asg1612.docker (or other role for install docker)

Example Playbook
----------------

    - hosts: servers
      roles:
         - asg1612.docker
         - monitor

License
-------

GNU General Public License v 3.0

Author Information
------------------

Andrés Sánchez García

twitter: @asg1612

e-mail: asg1612@gmail.com

linkedin: https://www.linkedin.com/in/asg1612/

website: http://andressaga.es/
