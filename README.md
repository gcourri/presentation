# Présentation WONKA — Gaspard Courrier

Présentation HTML autonome (30 slides, vidéos incluses). `index.html` est le point d'entrée.

## Mettre en ligne

### Option 1 — Netlify Drop (le plus rapide, ~2 min)
1. Aller sur https://app.netlify.com/drop
2. Glisser le dossier `site` entier dans la page.
3. L'URL publique est générée immédiatement (`https://xxx.netlify.app`). Renommable dans les réglages du site.

Netlify accepte les gros fichiers vidéo sans configuration.

### Option 2 — GitHub Pages
1. Créer un dépôt sur github.com (public).
2. Uploader le contenu de ce dossier à la racine du dépôt (`index.html`, `support.js`, `deck-stage.js`, `assets/`, `uploads/`).
3. Settings → Pages → Source : `Deploy from a branch`, branche `main`, dossier `/ (root)`.
4. L'URL sera `https://<utilisateur>.github.io/<dépôt>/`.

Limites GitHub : 100 Mo par fichier, 1 Go par dépôt. Le dossier passe, mais la lecture des vidéos est plus lente que sur Netlify.

## Navigation
- Flèches ← → ou espace : slide suivante / précédente
- Clic sur une vidéo : activer le son
- `P` : impression / export PDF

## Structure
- `index.html` — la présentation
- `support.js`, `deck-stage.js` — moteur d'affichage (ne pas renommer)
- `uploads/` — vidéos et images
- `assets/posters/` — images d'attente des vidéos
