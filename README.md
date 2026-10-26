# Le Bébert — Dictionnaire de l'argot français

Un dictionnaire d'argot français en une seule page : verlan, argot ancien, argot des jeunes, expressions populaires, avec définitions, exemples et origines.

## Fonctionnalités
- Recherche instantanée (insensible aux accents) — raccourci clavier `/`
- Navigation par lettre (A–Z) et par thème
- Mot du jour, mot au hasard
- Lien direct vers chaque mot (`#nom-du-mot`), copié au clic
- Thème clair / sombre

## Mise en ligne (GitHub Pages)
1. Créer un nouveau dépôt (ex. `le-bebert`) et y déposer `index.html` et ce `README.md`.
2. Dans **Settings → Pages**, choisir la branche `main` et le dossier `/ (root)`.
3. Le site sera disponible à `https://<votre-compte>.github.io/le-bebert/`.

## Ajouter un mot
Tout est dans le tableau `D` en haut du script de `index.html`. Une ligne par entrée :

```js
["mot","n.m.","Définition.","Exemple d'emploi.",["thème1","thème2"],"Origine (facultatif)."],
```

Thèmes disponibles : `argent`, `police`, `personnes`, `famille`, `corps`, `nourriture`, `objets`, `logement`, `travail`, `sentiments`, `actions`, `qualificatifs`, `insultes`, `expressions`, `verlan`, `jeunes`, `ancien`, `animaux`, `acronymes`.

---
Le Bébert · 2026
