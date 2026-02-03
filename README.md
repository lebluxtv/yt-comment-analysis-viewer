# yt-comment-analysis-viewer

Visualiseur web statique pour fichiers JSON générés localement.

Ce projet ne réalise aucune analyse.
Il permet uniquement de visualiser des cartes thématiques
à partir de fichiers `.json` exportés par un outil externe.

## Utilisation

1. Télécharger le fichier `index.html`
2. L’ouvrir dans un navigateur moderne
3. Charger un fichier `.json` via le bouton "JSON"

Aucune installation requise.
Aucune donnée envoyée sur Internet.

## Format attendu

Le fichier JSON doit contenir :
- video metadata
- map.nodes
- map.edges
- timeline.x1 / x2 frames
