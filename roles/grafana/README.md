Présentation du rôle grafana
=========

Ce rôle a pour objectif d'installer grafana sur un hôte distant. [Grafana](https://grafana.com/) est un logiciel libre qui permet la visualisation de données. Il permet de réaliser des tableaux de bord et des graphiques à partir de multiples sources dont des bases de données temporelles.

Prérequis
------------

Grafana est supporté sur les systèmes d'exploitation suivants : 
  - Debian / Ubuntu
  - RPM-based Linux (CentOS, Fedora, OpenSuse, RedHat)
  - macOS
  - Windows

Au niveau Hardware, Grafana utilise peu de ressources mémoire et CPU :
  - Mémoire minimum recommandée : 255 MB
  - Quantité minimum de CPU recocommandé : 1

Néanmoins, certaines fonctionnalités nécessitent davantage de ressources.

Variables du rôle
--------------

Voici les différentes variables qui sont utilisées dans ce rôle : 

| Variable  | Description |
| --- | --- |
| grafana_adminUser  | Nom d'utilisateur utilisé pour l'accès à l'interface d'administration Grafana (GUI)  |
| grafana_adminPassword  | Mot de passe utilisé pour l'accès à l'interface d'administration Grafana (GUI)  |
