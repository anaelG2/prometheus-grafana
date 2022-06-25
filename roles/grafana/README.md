Présentation du rôle grafana
=========

Ce rôle a pour objectif d'installer node_exporter sur un hôte distant. 
node_exporter est un service qui permet d'exposer les métriques du système et des applications supervisées afin de permettre à Prometheus de les collecter.

Requirements
------------

Node Exporter est un logiciel que vous pouvez installer sur les systèmes UNIX (Linux, OpenBSD, FreeBSD ou Darwin). Pour les systèmes windows, il existe [windows_exporter](https://github.com/prometheus-community/windows_exporter) pour les utilisateurs Windows.

Variables du rôle
--------------

Voici les différentes variables qui sont utilisées dans ce rôle : 

| Variable  | Description |
| --- | --- |
| grafana_adminUser  | Nom d'utilisateur utilisé pour l'accès à l'interface d'administration Grafana (GUI)  |
| grafana_adminPassword  | Mot de passe utilisé pour l'accès à l'interface d'administration Grafana (GUI)  |
