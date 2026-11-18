# Mes listes

Une petite app de listes de choses à faire, pensée pour le smartphone. Un seul fichier, pas de compte, pas de serveur.

👉 **[Ouvrir l'app](https://garcimore69.github.io/mes-listes/)**

## Fonctions

- Listes en cartes colorées sur l'écran d'accueil, avec aperçu et progression.
- Une case à cocher par ligne ; la ligne suivante se crée d'un appui ou avec la touche Entrée.
- Réorganisation des éléments par glisser-déposer (poignée à gauche).
- Palette de couleurs par liste.
- Tout décocher, retirer les éléments cochés, dupliquer, supprimer.
- Partage en texte brut (☐ / ☑) vers WhatsApp, e-mail ou toute autre application.
- Export et import d'un fichier de sauvegarde `.json`.
- Fonctionne hors-ligne une fois ouverte.

## Installation sur le téléphone

Ouvrir le lien dans Chrome, puis menu ⋮ → **Ajouter à l'écran d'accueil**. L'app s'ouvre ensuite en plein écran, comme une application native.

## Où sont mes listes ?

Dans le stockage local du navigateur, sur l'appareil. Rien n'est envoyé nulle part. Effacer les données du site les supprime : l'export de sauvegarde sert à s'en prémunir et à passer d'un appareil à l'autre.

## Développement

Aucune dépendance ni étape de construction. `index.html` contient toute l'app ; `sw.js` gère le mode hors-ligne.
