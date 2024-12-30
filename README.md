## GitHub Actions Workflow

Ce dépôt contient une configuration de workflow GitHub Actions définie dans le fichier [`.github/workflows/main.yml`](.github/workflows/main.yml).

### Description du Workflow

Le workflow est déclenché par un événement `push` et exécute les étapes suivantes sur un serveur Ubuntu :

1. Affiche un message indiquant que le job a été déclenché par un événement.
2. Affiche un message indiquant que le job s'exécute sur un serveur Ubuntu.
3. Affiche le nom de la branche et du dépôt.
4. Clone le code du dépôt dans le runner.
5. Affiche un message indiquant que le dépôt a été cloné.
6. Affiche un message indiquant que le workflow est prêt à tester le code.
7. Liste les fichiers dans le dépôt.
8. Affiche le statut du job.

Chaque étape utilise des variables GitHub pour afficher des informations dynamiques sur l'événement, le runner, la branche, et le dépôt.
