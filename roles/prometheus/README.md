Présentation du rôle prometheus
=========

Ce rôle a pour objectif d'installer prometheus sur un hôte distant. 
[Prometheus](https://prometheus.io/) est un logiciel libre de surveillance informatique et générateur d'alertes. Il enregistre des métriques en temps réel dans une base de données de séries temporelles en se basant sur le contenu de point d'entrée exposé à l'aide du protocole HTTP. Ici, il se basera sur le contenu du ou des node_exporter.

Requirements
------------
Prometheus peut être installé sur les systèmes UNIX (Linux, OpenBSD, FreeBSD, etc), Windows, ainsi que divers autres systèmes d'exploitations.

La configuration minimale requise est la suivante :
  - Minimum 2 CPU
  - Au moins 4 Go de mémoire
  - 20 Go d'espace disque libre

Variables du rôle
--------------

Voici les variables principales utilisées par ce rôle : 

| Variable  | Description |
| --- | --- |
| prometheus_retentionTime | Durée de rétention des métriques collectés |
| prometheus_scrapeInterval  | Fréquence de collecte des métriques  |
| prometheus_node_exporter_group  | Groupe de node_exporter sur lesquels réaliser la collecte |
| prometheus_dirConf  | Chemin du répertoire de configuration de prometheus |

