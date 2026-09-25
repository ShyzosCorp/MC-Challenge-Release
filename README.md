# MC-Challenge-Release

Releases publiques de **MC Challenge Plugin** (Paper).

Ce dépôt ne contient que les `.jar` publiés automatiquement par GitHub Actions. Le code source est privé.

## Installation

1. Télécharger le `.jar` de la [dernière release](https://github.com/ShyzosCorp/MC-Challenge-Release/releases/latest).
2. Le placer dans le dossier `plugins/` du serveur, puis redémarrer.

## Mises à jour

Le plugin vérifie ce dépôt au démarrage et télécharge automatiquement les nouvelles versions dans `plugins/update/`. Elles sont appliquées au redémarrage suivant.

Commandes (OP) : `/update check`, `/update download`.
