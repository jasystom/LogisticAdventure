# LogisticAdventure

Un logisticien de l'entrepôt de Roissy se réveille dans un monde fantastique. Il ne sait pas se battre, mais il maîtrise les flux : récolte à l'aventure, monte un atelier de tapis et de machines, bats les boss pour automatiser, embauche des préparateurs.

Jeu en un seul fichier HTML, sans dépendance. Les sauvegardes restent dans le navigateur (3 emplacements).

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub (par exemple `logisticadventure`).
2. Envoie tous les fichiers de ce dossier à la racine du dépôt (bouton **Add file → Upload files**).
3. Dans **Settings → Pages**, choisis *Deploy from a branch*, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une minute, le jeu est en ligne sur `https://TON-PSEUDO.github.io/logisticadventure/`.

## Installer sur le téléphone

- **Android (Chrome)** : ouvre l'adresse, menu ⋮ → **Installer l'application** (ou « Ajouter à l'écran d'accueil »).
- **iPhone (Safari)** : ouvre l'adresse, bouton Partager → **Sur l'écran d'accueil**.

Le jeu s'ouvre alors en plein écran avec son icône et fonctionne hors ligne après la première ouverture.

## Mettre à jour le jeu

Remplace `index.html` dans le dépôt, puis change `VERSION` dans `sw.js` (par exemple `la-v2`) pour que les téléphones récupèrent la nouvelle version. Les sauvegardes sont conservées.

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | Le jeu complet |
| `manifest.webmanifest` | Nom, couleurs et icônes de l'application |
| `sw.js` | Fonctionnement hors ligne |
| `icon-*.png`, `apple-touch-icon.png` | Icônes |
