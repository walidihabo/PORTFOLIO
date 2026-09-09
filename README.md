# Portfolio — Walid Ihab Imamouine

Site portfolio one-page (Accueil / À propos / Portfolio / Contact) pour architecte spécialisé en ArchViz &amp; visualisation temps réel.

## Structure

```
├── index.html      → toute la page (une seule page, sections en ancres)
├── style.css        → design (thème "plan technique", animations)
├── script.js        → animations au scroll, menu mobile, formulaire
└── images/
    └── portrait.jpg
```

Le portfolio de projets n'est pas hébergé ici : la section "Portfolio" renvoie directement vers votre profil ArtStation (https://www.artstation.com/wivision), pour rester à jour sans re-déployer le site à chaque nouveau projet.

## Mettre le site en ligne avec GitHub Pages (gratuit)

1. **Créer un dépôt GitHub**
   Sur [github.com](https://github.com), cliquez sur *New repository*. Nommez-le par exemple `portfolio` (le nom n'a pas d'importance). Laissez-le public.

2. **Envoyer les fichiers**
   - Le plus simple : sur la page du dépôt vide, cliquez sur *uploading an existing file*, puis glissez-déposez `index.html`, `style.css`, `script.js` et le dossier `images/` (avec `portrait.jpg` dedans). Cliquez sur *Commit changes*.
   - Ou en ligne de commande :
     ```bash
     git init
     git add .
     git commit -m "Portfolio en ligne"
     git branch -M main
     git remote add origin https://github.com/VOTRE-PSEUDO/portfolio.git
     git push -u origin main
     ```

3. **Activer GitHub Pages**
   Dans le dépôt : *Settings* → *Pages* (menu de gauche) → sous *Branch*, choisissez `main` et le dossier `/ (root)` → *Save*.

4. **Récupérer l'adresse du site**
   Après 1 à 2 minutes, votre site est en ligne à l'adresse :
   `https://VOTRE-PSEUDO.github.io/portfolio/`

## Mettre à jour le site plus tard

Modifiez les fichiers localement, puis :
```bash
git add .
git commit -m "Mise à jour"
git push
```
GitHub Pages republie automatiquement en quelques minutes.
