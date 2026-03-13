# Écho — Instructions de déploiement

## Structure des fichiers

```
echo-app/
├── index.html      ← l'application complète
├── manifest.json   ← configuration PWA
├── sw.js           ← service worker (cache offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Déployer sur GitHub Pages (10 minutes)

### Étape 1 — Créer un dépôt GitHub
1. Allez sur **github.com**
2. Cliquez sur le **+** en haut à droite → **New repository**
3. Nom : `echo` (en minuscules)
4. Laissez tout le reste par défaut
5. Cliquez **Create repository**

### Étape 2 — Uploader les fichiers
1. Sur la page de votre dépôt, cliquez **uploading an existing file**
2. Glissez-déposez **tous les fichiers** du dossier `echo-app` :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - Le dossier `icons/` avec les deux images
3. En bas, cliquez **Commit changes**

### Étape 3 — Activer GitHub Pages
1. Dans votre dépôt, cliquez **Settings** (en haut)
2. Dans le menu gauche, cliquez **Pages**
3. Sous "Source" → sélectionnez **Deploy from a branch**
4. Branch : **main** / dossier : **/ (root)**
5. Cliquez **Save**

### Étape 4 — Votre URL
Après 1-2 minutes, votre Écho sera accessible à :
**https://[votre-nom-github].github.io/echo/**

### Étape 5 — Installer sur iPhone
1. Ouvrez cette URL dans **Safari**
2. Appuyez sur l'icône **Partager** (carré avec flèche)
3. Faites défiler → **Sur l'écran d'accueil**
4. Appuyez **Ajouter**

Écho apparaît maintenant comme une vraie app sur votre téléphone.
