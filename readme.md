Fleurs Roussel — Site Vitrine & E-commerce Artisanal

Intégration web responsive (mobile-first) réalisée à partir d'une maquette Figma pour l'artisan fleuriste Fleurs Roussel à Blois.

Aperçu du projet

L'objectif de ce projet est de concevoir une interface moderne, accessible et fidèle au design system fourni, s'adaptant de manière fluide du format mobile (390 px) au format ordinateur (1440 px).

Points clés de l'intégration

Approche Mobile-First : Architecture pensée d'abord pour les petits écrans, avec adaptation progressive via les breakpoints Tailwind (sm:, md:, lg:).

Design System sur mesure : Configuration des couleurs de marque et des typographies via le bloc @theme de Tailwind CSS v4.

Accessibilité & Interactions : Gestion soignée des états de survol (hover) et des contours de navigation au clavier (focus-visible / ring-2).

Performance : Compilation et minification du CSS de production pour un chargement ultra-rapide.

Stack technique

HTML5 sémantique (<header>, <section>, <article>, <footer>)

Tailwind CSS v4 (CLI & @theme)

Google Fonts (Playfair Display & Inter)

Node.js / NPM pour l'automatisation du build

Installation et lancement

Cloner le dépôt ou télécharger les fichiers du projet.

Installer les dépendances :

npm install


Lancer le mode développement (compilation en direct) :

npm run dev


Compiler pour la production (fichier CSS minifié) :

npm run build


Structure du projet

mme.roussel/
├── dist/
│   └── output.css      # CSS compilé et minifié (production)
├── images/             # Illustrations SVG et icônes
├── src/
│   └── input.css       # Fichier source Tailwind et variables @theme
├── index.html          # Page principale
├── package.json        # Dépendances et scripts NPM
└── README.md           # Documentation du proje