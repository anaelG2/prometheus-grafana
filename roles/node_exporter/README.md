Présentation du rôle node_exporter
=========

Ce rôle a pour objectif d'installer node_exporter sur un hôte distant. 
node_exporter est un service qui permet d'exposer les métriques du système et des applications supervisées afin de permettre à Prometheus de les collecter.

Prérequis
------------

Node Exporter est un logiciel qui peut être installé sur les systèmes UNIX (Linux, OpenBSD, FreeBSD, etc). Pour les systèmes Windows, il existe [windows_exporter](https://github.com/prometheus-community/windows_exporter).

En termes de consommation de ressources et d'espace disque, node_exporter est reste relativement léger. 


Variables du rôle
--------------

Voici les différentes variables qui sont utilisées dans ce rôle : 

| Variable  | Description |
| --- | --- |
| node_exporter_serviceName  | Nom du service créé pour exécuter node_exporter |
| node_exporter_userName  | Nom de l'utilisateur créé pour exécuter node_exporter  |
| node_exporter_groupName  | Mot de passe de l'utilisateur créé pour exécuter node_exporter |
| node_exporter_version  | Version de node_exporter à installer |
| node_exporter_binPath  | Chemin dans lequel sera créé et exécuté `{{node_exporter_serviceName}}.service` |
| node_exporter_dirConf  | Chemin du répertoire de configuration de node_exporter |
