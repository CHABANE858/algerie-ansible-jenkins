# Rôle NGINX pour Ansible

Ce rôle installe NGINX et configure le serveur avec un template.

## Variables disponibles

- nginx_port: Port d'écoute (default: 80)
- nginx_root: Répertoire racine (default: /var/www/html)

## Usage

- hosts: webservers
  roles:
    - nginx
