# Coach HDV

Une appli web (en français) pour progresser plus vite à Clash of Clans.

**Ouvrir l'appli : https://harry3-cmyk.github.io/coach-hdv/**

## Ce qu'elle fait

- **Mon plan** : un score « prêt à monter » sur 100 et un verdict clair (« Reste à l'HDV 16 », « Presque prêt », « Monte en HDV 17 »), ce qui te bloque, tes 3 prochaines actions.
- **Mes screens** : envoie des captures de ton village (Hall des héros, village dézoomé, laboratoire). Claude lit ton HDV, tes héros, ton labo et tes défenses, te dit si tu peux monter d'HDV et remplit ton village en un clic.
- **Mon village** : le questionnaire (HDV, objectif, héros, labo, bâtiments d'attaque, défenses, pièges, murs), avec import possible depuis l'export du jeu.
- **Améliorations** : l'ordre complet de ce qu'il faut améliorer, ce que fait chaque ouvrier, la recherche du labo, et un plan spécial Hammer Jam.
- **Compos & stratégies** : 23 armées de l'HDV7 à l'HDV18, avec l'armée, les sorts, les héros, le plan d'attaque étape par étape et les étoiles que tu peux viser selon ton niveau.
- **Événements** : le calendrier de novembre 2026 (Hammer Jam, LDC, Chasse au trésor, Jeux de clan, HDV19 attendu).

## Analyse de screens

Sur cette version GitHub, l'analyse passe par l'API d'Anthropic avec **ta propre clé API** :

1. Crée un compte sur [console.anthropic.com](https://console.anthropic.com) et ajoute un peu de crédit.
2. Crée une clé dans « API keys ».
3. Colle-la dans l'onglet « Mes screens ».

Compte environ 5 à 15 centimes par analyse. La clé reste dans ton navigateur et n'est envoyée qu'à l'API d'Anthropic.

## Tes données

Tout est enregistré dans ton navigateur (localStorage) : rien n'est envoyé ailleurs, sauf les captures que tu choisis d'analyser.

## Mettre à jour

Tout tient dans `index.html` : HTML, CSS et JavaScript, sans étape de build. Les niveaux max, les compos et les dates d'événements sont en haut du script (`CAPS`, `TH`, `COMPOS`, `EVENTS`).

---

Application non officielle, sans lien avec Supercell. Infos à jour au 3 novembre 2026.
