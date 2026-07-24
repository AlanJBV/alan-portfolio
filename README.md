# Portfolio — Alan Brechotteau

Portfolio en HTML/CSS/JS pur (aucune dépendance, aucun build).

**En ligne :** https://alanjbv.github.io/alan-portfolio/

## Structure
- `index.html` — page unique (tout le CSS/JS est inline)
- `intro.mp4` — vidéo de fond du hero
- `Cv.pdf` — CV téléchargeable
- `assets/` — logos et images (expériences, formations)

## Déploiement (GitHub Pages)
Le site est hébergé sur **GitHub Pages** : gratuit, bande passante généreuse, déploiements illimités.

- Chaque `git push` sur `main` **redéploie automatiquement** le site en ~1 min.
- Aucune configuration de build : GitHub sert directement les fichiers de la racine.

Pour (ré)activer si besoin : repo → **Settings → Pages → Build and deployment → Source : « Deploy from a branch » → branche `main`, dossier `/ (root)`**.

## Nom de domaine (optionnel)
Pour utiliser un domaine perso (ex. `alanbrechotteau.com`) : Settings → Pages → **Custom domain**, puis créer un enregistrement DNS chez le registrar (CNAME vers `alanjbv.github.io`, ou les 4 A records de GitHub pour un domaine apex).
