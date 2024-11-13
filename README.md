# Projet Wordpress et Zabbix

## Description
Ce projet permet de déployer Wordpress et Zabbix en utilisant Docker et Docker Compose.

## Installation
1. Cloner le repository : `git clone https://github.com/qmunnz/wordpress-zabbix.git`
2. Lancer le script d'installation de Docker : `./install_docker.sh`
3. Démarrer les services avec Docker Compose : `docker compose up -d`

## Accès aux Services
- Wordpress : `http://192.168.20.x:8080`
- Zabbix : `http://192.168.20.x:8081`

## Configuration
Toutes les configurations sont stockées dans le fichier `docker-compose.yml`.
