# THE TRADING DESK — Ivory Edition

Site personnel de journal de trading, gratuit et sans backend. Version publique **sans données de trades initiales**.

## Déployer gratuitement sur GitHub Pages
1. Créer un dépôt **public** sur GitHub nommé `the-trading-desk` (avec une branche `main`).
2. Ajouter `index.html` et `.nojekyll` à la racine du dépôt.
3. Ouvrir **Settings → Pages → Build and deployment** ; choisir **Deploy from a branch**, branche **main**, dossier **/(root)** puis **Save**.
4. Lorsque GitHub confirme le déploiement, ouvrir l’URL indiquée par GitHub (généralement `https://VOTRE-COMPTE.github.io/the-trading-desk/`).

## Confidentialité et limites
- Aucune donnée de trade personnelle n'est publiée avec les fichiers actuels.
- Les nouveaux trades, bilans, finances et rituels sont enregistrés localement dans le navigateur de l’appareil : **pas de compte ni de synchronisation multi-appareils**.
- Une autre personne sur le même profil de navigateur peut accéder à ces données, et l'effacement du stockage les supprime. Sauvegarder régulièrement les exports JSON.
- Les anciennes données d’une autre version du site ne sont pas reprises automatiquement.
- Les graphiques sont chargés depuis le CDN de Chart.js ; leur chargement nécessite une connexion internet.