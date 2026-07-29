# Captures des projets

Dépose les captures d’écran dans ce dossier, idéalement au format WebP.

Exemple :

```text
public/projects/binsight-dashboard.webp
```

Puis renseigne le chemin dans `src/data/portfolio.js` :

```js
image: "/projects/binsight-dashboard.webp",
imageAlt: "Tableau de bord de l’application BinSight",
```

Si `image` est absent ou vide, l’illustration CSS actuelle reste affichée.
