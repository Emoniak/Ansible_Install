# Ansible_Install
Mes différent playbook pour installer mes serveurs et workstation

## Architecture
Le fichier "inventory/hosts" contient la liste des hôtes cibles pour lesquels Ansible doit exécuter les tâches.
Le fichier "playbook.yml" définit les tâches à exécuter sur les hôtes cibles en utilisant les rôles définis dans le dossier "roles/".
Le dossier "roles/common/" contient les tâches, variables, modèles, fichiers et métadonnées associées à ce rôle.
Le fichier "roles/common/tasks/main.yml" définit les tâches à exécuter pour ce rôle.
Le fichier "roles/common/vars/main.yml" définit les variables associées à ce rôle.
Le dossier "roles/common/templates/" contient les modèles Ansible utilisés pour générer des fichiers sur les hôtes cibles.
Le dossier "roles/common/files/" contient les fichiers nécessaires pour le rôle.
Le fichier "roles/common/meta/main.yml" définit les métadonnées associées au rôle, telles que la dépendance d'autres rôles.