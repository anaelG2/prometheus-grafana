Playbook Ansible prometheus-grafana
=========

Playbook Ansible permettant de déployer des services de supervision basés sur prometheus & grafana, ainsi que d'installer le rôle node_exporter sur les différents clients de cette supervision. 



Rôles
------------

  - [grafana](roles/grafana/)
  - [prometheus](roles/prometheus/)
  - [node_exporter](roles/node_exporter/)



Utilisation
--------------

1. Configurer vos serveurs cibles via le fichier inventory.yml

2. Personnaliser le playbook en modifiant les valeures des fichier vars/main.yml des différents rôles

3. Déployer le playbook à l'aide la commande suivante :

    `ansible-playbook -i inventory.yml playbook.yml`

4. Accéder à l'interface d'administration Grafana :

    `http://TARGET_HOST:3000/`
    