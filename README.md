# Portfolio — Alan Brechotteau

Portfolio en HTML/CSS/JS pur (aucune dépendance, aucun build).

## Structure
- `index.html` — page unique (tout le CSS/JS est inline)
- `intro.mp4` — vidéo de fond du hero
- `Cv.pdf` — CV téléchargeable (à remplacer par la version finale)

## Déploiement sur Netlify (via GitHub)
1. Pousser ce repo sur GitHub (voir plus bas)
2. Sur [netlify.com](https://netlify.com) → "Add new site" → "Import an existing project" → connecter GitHub → choisir ce repo
3. Build command : (laisser vide)
4. Publish directory : `/` (racine)
5. Déployer — chaque `git push` sur `main` redéploiera automatiquement le site

## Nom de domaine
Une fois le site en ligne sur Netlify, aller dans Site settings → Domain management → Add custom domain, puis modifier les DNS chez OVH pour pointer vers Netlify.
