Présentation du rôle node_exporter
=========

Ce rôle a pour objectif d'installer node_exporter sur un hôte distant. 
node_exporter est un service qui permet d'exposer les métriques du système et des applications supervisées afin de permettre à Prometheus de les collecter.

Requirements
------------

Node Exporter est un logiciel que vous pouvez installer sur les systèmes UNIX (Linux, OpenBSD, FreeBSD ou Darwin). Pour les systèmes windows, il existe [windows_exporter](https://github.com/prometheus-community/windows_exporter) pour les utilisateurs Windows.

Variables du rôle
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

