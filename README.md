Playbook Ansible prometheus-grafana
=========

Playbook Ansible permettant de déployer des services de supervision basés sur prometheus & grafana, ainsi que d'installer le rôle node_exporter sur les différents clients de cette supervision. 

Rôles
------------
  - grafana
  - prometheus
  - node_exporter

Utilisation
--------------
1. Configurer vos serveurs cibles via le fichier inventory.yml

2. Personnalisez le playbook en modifiant les valeures des fichier vars/main.yml des différents rôles

ansible-playbook -i inventory.yml playbook.yml