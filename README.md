# BBX

Application de suivi d'entraînement (une seule page HTML, sans serveur).

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur github.com (par exemple `bbx`).
2. Envoie tous les fichiers de ce dossier à la racine du dépôt (bouton « Add file » > « Upload files »).
3. Va dans **Settings > Pages**.
4. Dans « Build and deployment », choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
5. Après une minute, l'adresse apparaît : `https://TON-PSEUDO.github.io/bbx/`.

## Sur iPhone

Ouvre l'adresse dans Safari, puis Partager > **Sur l'écran d'accueil**.

## Contenu

- `index.html` : l'application
- `manifest.webmanifest` : nom et icônes de l'app
- `icons/` : logo BBX (180, 192 et 512 px)
- `.nojekyll` : évite le traitement Jekyll de GitHub Pages
