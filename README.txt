# Le Grimoire de Kory — prototype PWA

Application web statique en français, pensée pour mobile et iPhone.
Fonctions incluses : tableau de bord lunaire (phase approximative), rubrique astrologie avec données natales fournies, tirage aléatoire des 78 cartes (mots-clés pédagogiques), fiches de départ cristaux/herbes/bougies, Roue de l'année, notes locales et export JSON.

## Hébergement gratuit
Cette archive ne peut pas être installée directement comme une application native. Pour une installation PWA sur iPhone, il faut d'abord héberger les fichiers sur une adresse HTTPS. Une option gratuite est GitHub Pages :
1. Crée un compte GitHub si besoin et un dépôt public nommé `grimoire-de-kory`.
2. Téléverse `index.html`, `manifest.json`, `sw.js` et `icon.svg` à la racine du dépôt.
3. Dans Settings → Pages, choisis le déploiement depuis la branche `main`, dossier `/ (root)`, puis enregistre.
4. Attends la publication de l'adresse HTTPS indiquée par GitHub Pages.
5. Ouvre cette adresse dans Safari sur l'iPhone → bouton Partager → « Sur l'écran d'accueil » → active « Ouvrir comme app » si l'option apparaît → Ajouter.

## Limites actuelles
- La phase de lune est une estimation basée sur un cycle synodique moyen ; les heures astronomiques exactes ne sont pas calculées.
- Les positions astrologiques exactes (Ascendant, Lune, maisons, aspects et transits) ne sont pas encore calculées. Ne pas les inventer.
- Les correspondances sont pédagogiques et symboliques, pas des conseils médicaux ni des promesses d'efficacité.
- Les notes sont stockées dans le navigateur de l'appareil. Utilise « Exporter mes notes » pour en faire une sauvegarde. Effacer les données du navigateur peut les supprimer.
- Pas de compte utilisateur ni de synchronisation cloud.
