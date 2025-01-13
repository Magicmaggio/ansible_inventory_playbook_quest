# Ansible Deployment: Nginx & MariaDB

## Description
Ce projet Ansible automatise l'installation de :
- **Nginx** sur les serveurs du groupe `web_servers`
- **MariaDB** sur les serveurs du groupe `db_servers`

### Structure
- `inventory.yml` : Inventaire des serveurs (web et base de données)  
- `playbook.yml` : Playbook pour installer et configurer Nginx et MariaDB

### Commande d'exécution
```bash
ansible-playbook -i inventory.yml playbook.yml
```

## Prérequis

 - Ansible installé
 - Accès SSH aux serveurs (clé SSH ou mot de passe configuré)
