## 🌈 ARC-EN-CIEL ANIME EN HTML5 ET CSS3

![Design preview for the project](./img/preview.png)

## 🚀 Le challenge

Un composant web simple, léger et élégant représentant un arc-en-ciel en rotation continue, conçu uniquement avec du HTML5 et du CSS3 (sans JavaScript).

Voici les fonctionnalités du projet :

- **100% CSS** : Aucun script JavaScript requis, performance optimale.
- **Animation fluide** : Rotation continue à 360° grâce aux `@keyframes` CSS.
- **Design moderne** : Utilisation d'un `conic-gradient` pour des transitions de couleurs parfaites.
- **Structure minimaliste** : Seulement deux balises HTML imbriquées.

## 📸 Démonstration

Lien vers le projet : https://aperbet56.github.io/arc-en-ciel/

## 🛠️ Projet développé avec

- Utilisation des balises sémantiques HTML5
- CSS3
- Flexbox
- Animations CSS (@keyframes)
- Page web responsive
- Desktop first
- position absolute et relative
- pseudo-élément after
- Utilisation du normaliseur : le fichier normalize.css
- Commentaires HTML
- Commentaires CSS

## 📂 Structure du projet

```text
arc_en_ciel/
│
├── index.html          # Page principale du site
├── normalize.css       # Fichier normalize.css
├── style.css           # Règles de design et animations
│
├── img/                # favicon et prewiew
│
└── README.md           # Fichier de documentation du projet
```

## ⚙️ Personnalisation

Vous pouvez facilement adapter le rendu visuel en modifiant quelques valeurs dans le fichier `style.css` :

- **Vitesse de rotation** : Modifiez `4s` dans la propriété `animation` de la classe `.rainbow` (ex: `2s` pour aller plus vite, `8s` pour aller plus lentement).
- **Épaisseur de l'arc** : Ajustez la valeur de `top`, `left`, `right`, `bottom` dans le pseudo-élément `.rainbow::after` (ex: `40px` pour un arc plus épais).
- **Couleur de fond** : Si vous changez le `background-color` du `body`, n'oubliez pas d'appliquer la **même couleur** sur le `.rainbow::after` pour que le masque central reste invisible.

## 📝 Licence

Ce projet est libre de droits. Vous pouvez l'utiliser, le modifier et le distribuer comme bon vous semble.
