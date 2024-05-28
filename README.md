# TODO- readme file
# Gestionnaire de liste de tâches
Ce script shell permet de gérer une liste de tâches. Il offre des fonctionnalités pour créer, mettre à jour, supprimer et afficher des tâches, ainsi que pour rechercher des tâches par titre et lister les tâches pour une journée donnée

### Stockage des données
Les données des tâches sont stockées dans un fichier texte situé à l'emplacement spécifié par la variable TODO_FILE. Chaque tâche est enregistrée sur une ligne avec des champs séparés par des barres verticales (|). Les champs comprennent l'identifiant de la tâche, le titre, la description, l'emplacement, la date d'échéance, l'heure d'échéance et l'état de complétion

### Organisation du code
Le script est organisé en différentes sections, chacune gérant une fonctionnalité spécifique :
- Les fonctions show_menu et show_help affichent le menu et l'aide
- Les fonctions create_task, update_task, delete_task, show_task, list_tasks, search_task et list_all_tasks implémentent les fonctionnalités principales du gestionnaire de tâches
- La logique principale du script est gérée dans la structure de commutation case.

### Installation
1. Copiez le contenu du script dans un fichier shell (par exempleici nommé `devoirtodo.sh`)
2. Assurez-vous que le fichier est exécutable avec la commande `chmod +x todo.sh`

### Utilisation
- Exécutez le script en utilisant `./devoirtodo.sh <nom de la commande>`.
- Vous pouvez utiliser les commandes suivantes :
    - `create`: Créer une nouvelle tâche.
    - `update`: Mettre à jour une tâche existante.
    - `delete`: Supprimer une tâche.
    - `show`: Afficher les informations d'une tâche.
    - `list`: Lister les tâches pour une journée donnée.
    - `search`: Rechercher une tâche par titre.
    - `listall`: Lister toutes les tâches.
    - `help <commande>`: Afficher l'aide pour une commande spécifique.

## Exemple d'utilisation
1. Pour créer une tâche, exécutez `./devoirtodo.sh create`.
2. Pour mettre à jour une tâche, exécutez `./devoirtodo.sh update`.
3. Pour supprimer une tâche, exécutez `./devoirtodo.sh delete`.
4. Pour afficher les informations d'une tâche, exécutez `./devoirtodo.sh show`.
5. Pour lister les tâches pour une journée donnée, exécutez `./devoirtodo.sh list`.
6. Pour rechercher une tâche par titre, exécutez `./devoirtodo.sh search`.
7. Pour lister toutes les tâches, exécutez `./devoirtodo.sh listall`.
8. Pour obtenir de l'aide sur une commande spécifique, exécutez `./devoirtodo.sh help <commande>`.


