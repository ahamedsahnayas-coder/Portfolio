# Portfolio — Nayas AHAMEDSAH

Portfolio personnel développé en HTML5 / CSS3.

---

## À propos du projet

Ce portfolio présente mon parcours, mes compétences et mes projets universitaires réalisés en 1ère année de **BUT Informatique** à l'IUT de Champs-sur-Marne.

Il a été conçu pour être : clair, structuré, responsive.


## Structure du projet

```
portfolio/
│
├── index.html              # Page principale (structure HTML)
├── styles.css              # Feuille de styles (design complet)
│
├── images/
│   ├── photo_nayas.jpg     # Photo de profil
│   ├── projet_unesco.jpg   # Capture projet UNESCO
│   ├── projet_python.jpg   # Capture projet Python
│   ├── projet_BDD.jpg      # Capture projet Base de données
│   └── projet_reseau.jpg   # Capture projet Réseau DHCP
│
└── documents/
    └── CV_Nayas.pdf        # CV téléchargeable
```


## Fonctionnalités

- **Design dark mode** avec palette bleu nuit / teal / violet
- **Navigation fixe** avec scroll fluide et soulignement animé au survol
- **Section Hero** avec photo de profil, badge d'alternance animé et call-to-action
- **Grilles CSS** à deux colonnes (À propos, Compétences, Projets)
- **Badges de compétences** par catégorie (Développement Web, Programmation, BDD, Réseaux, Design)
- **Cartes projets** avec image, description et contributions personnelles
- **Frise chronologique** animée (timeline CSS pure)
- **Boutons de liens professionnels** : CV (PDF), GitHub, LinkedIn
- **Design 100% responsive** (tablette et mobile)
- **Motif de fond** en grille de points (CSS pur)
- **Animations CSS** : hover, pulse, lévitation des cartes

---

## Technologies utilisées

| Technologie | Usage |
|---|---|---|
| HTML5 | Structure sémantique de la page |
| CSS3 | Design, animations, responsive |
| CSS Grid | Mises en page à plusieurs colonnes |
| CSS Flexbox | Alignements et distributions |
| CSS Variables | Palette de couleurs centralisée |
| Google Fonts | Polices DM Sans & DM Mono |
| Font Awesome 6 | Icônes vectorielles |

> Tout est réalisé en **HTML/CSS pur**.


## Concepts CSS clés utilisés

- **`:root` et variables CSS** (`--blue`, `--teal`, `--violet`...) pour une palette centralisée
- **`clamp()`** pour des tailles de police fluides et responsives
- **`display: grid`** avec `repeat(2, 1fr)` pour les grilles à deux colonnes
- **`display: flex`** pour les alignements horizontaux et verticaux
- **Pseudo-éléments `::before` / `::after`** pour le motif de fond, les barres décoratives, le trait de la timeline et les points de frise — sans aucune balise HTML supplémentaire
- **`@keyframes pulse`** pour l'animation du badge d'alternance
- **`backdrop-filter: blur()`** pour l'effet verre dépoli de la navigation
- **`object-fit: cover`** pour les images de projets sans déformation
- **`@media queries`** pour l'adaptation aux écrans ≤ 768px et ≤ 480px
- **`transition`** sur hover pour les animations fluides des cartes et boutons


## Lancer le projet localement

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/ahamedsahnayas-coder/portfolio.git
   ```

2. **Ouvrir le fichier** :
   ```bash
   cd portfolio
   # Ouvre index.html dans le navigateur
   ```

3. **Aucune dépendance à installer** — les polices et icônes sont chargées via CDN.

---

## Déployer sur GitHub Pages

1. Va dans les **Settings** du dépôt GitHub
2. Section **Pages** → Source : `Deploy from a branch`
3. Branche : `main` / Dossier : `/ (root)`
4. Sauvegarde → ton site sera disponible à :
   `https://TON_USERNAME.github.io/portfolio/`


## 📁 Projets présentés

| Projet | Technologies | Rôle |
|---|---|---|
| Site Web UNESCO | HTML5, CSS3, Figma | UI/UX Design & Front-end |
| Jeu "Wall Is You" | Python, Thonny | Interface & Visuelle |
| Base de données | PostgreSQL, MySQL, Looping | Modélisation & Validation |
| Serveur DHCP | Ubuntu, Bash, Netkit | Administration système & Réseau |


## Contact

- **Email** : [ahamedsah.nayas@gmail.com](mailto:ahamedsah.nayas@gmail.com)
- **LinkedIn** : [Nayas Ahamedsah](https://www.linkedin.com/in/nayas-ahamedsah-66061b3a7/)
- **GitHub** : [@AhamedsahNayas](https://github.com/ahamedsahnayas-coder)


## Licence

Ce projet est personnel. Le code est librement consultable à titre pédagogique.  
Merci de ne pas réutiliser les textes, photos ou contenus personnels sans autorisation.


*Réalisé par **Nayas AHAMEDSAH** — Étudiant BUT Informatique, IUT de Champs-sur-Marne — 2026*
