# Annonces Sequens

Déposer le dossier `News` à la racine du stockage web, à côté de `Frames`, `Stickers` et `Fonts`.

Dans `catalogue.json`, placer l’annonce à afficher en premier. Attribuer un nouvel `id` à chaque nouvelle annonce. Sequens affiche la première annonce valide une seule fois par appareil, au lancement avec une connexion.

- `title` contient le titre (100 caractères maximum).
- `message` contient le corps du message (600 caractères maximum).
- `target` vaut `templates` pour la galerie des modèles ou `stickers` pour les autocollants.
- Utiliser `"announcements": []` pour désactiver l’annonce.

Dans Frame Builder, la date de publication d’un modèle alimente la section **Nouveautés**. Conserver cette date lors des corrections apportées à un modèle déjà publié.
