# CV Paul Leali - Site Web Statique

## Déploiement rapide (gratuit)

### Option 1 : GitHub Pages (Recommandé)
1. Créer un repo GitHub (ex: `paulleali.github.io` ou `cv`)
2. Uploader `index.html`
3. Settings → Pages → Source: main branch
4. Ton CV sera en ligne sur `https://pleali.github.io/cv`

### Option 2 : Netlify (Drag & Drop)
1. Va sur [netlify.com](https://netlify.com)
2. Drag & drop le dossier `cv-site`
3. Netlify génère automatiquement une URL

### Option 3 : Vercel
1. Va sur [vercel.com](https://vercel.com)
2. Import depuis GitHub ou upload direct
3. Déploiement automatique

### Option 4 : Intégration RapidoCloud
Tu peux aussi l'héberger sur rapidocloud.net en le plaçant dans le dossier web de ton serveur.

## Personnalisation

### Ajouter ta photo
Remplace la ligne `<img src="photo-placeholder.jpg"...>` par le chemin de ta photo, ou encode-la en base64.

### Modifier les couleurs
Les variables CSS sont en haut du fichier :
```css
:root {
    --accent: #00d4aa;        /* Couleur accent principale */
    --accent-secondary: #7c3aed;  /* Couleur secondaire */
}
```

### Ajouter une section
Copie une `<section>` existante et modifie le contenu.

## Structure
```
cv-site/
└── index.html    # Tout est dans un seul fichier (CSS inclus)
```

## SEO & ATS
- Meta description optimisée avec mots-clés
- Structure sémantique HTML5
- Responsive mobile
- Print-friendly pour export PDF

---
Créé avec Claude • Décembre 2025
