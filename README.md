# Beatz 🎧

Landing page pour une marque de casques audio haut de gamme, construite avec **React + Vite** et animée avec **GSAP**.

## Aperçu

Beatz est une landing page one-page avec un casque animé qui se déplace, tourne et change de taille au fil du scroll, guidant le visiteur à travers les différentes sections du site.

## Stack technique

- **React 18** — composants UI
- **Vite 6** — bundler et dev server
- **GSAP 3.13** — animations (ScrollTrigger, ScrollSmoother, SplitText)

## Structure du projet

```
Beatz/
├── public/
│   └── images/          # Images et vidéo
├── src/
│   ├── App.jsx          # Composants + animations GSAP
│   ├── index.css        # Styles globaux
│   └── main.jsx         # Point d'entrée React
├── index.html
└── vite.config.js
```

## Lancer le projet

```bash
npm install
npm run dev
```

## Build production

```bash
npm run build
npm run preview
```

## Sections

1. **Modern Harmony** — hero avec animation d'entrée du titre (SplitText)
2. **True Clarity** — présentation avec les 3 fonctionnalités clés
3. **Masterbeat** — vidéo + description immersive
4. **Galerie** — photos lifestyle animées au scroll
5. **Top Picks** — 4 modèles (Beatz Elite, One, Plus, Max Pro)
6. **Pure Escape** — section finale avec appel à l'action

## Palette de couleurs

| Rôle | Couleur |
|---|---|
| Fond | `#E6EAE3` — sage clair |
| Titres / bordures | `#2E4025` — vert armée |
| Accents / boutons | `#B8962E` — laiton doré |
| Texte | `#1A2018` — vert très sombre |
