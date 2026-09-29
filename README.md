# Algeria Tech — moteur d'automatisation

Ce dépôt public ne contient **que les programmes d'automatisation** (GitHub Actions)
du site [algeria-tech.pages.dev](https://algeria-tech.pages.dev). Le code et le contenu du
site sont dans un dépôt **privé** ; chaque automatisation le récupère avec une clé de
déploiement, fait sa mise à jour, puis y renvoie le résultat.

Aucune clé ici : tous les accès sont des **secrets chiffrés** de GitHub, jamais affichés.

| Automatisation | Rôle |
|---|---|
| `rss_update.yml` | flux RSS thématiques (toutes les 4 h) |
| `daily-update.yml` | mise à jour quotidienne (veille, articles) |
| `revue-presse.yml` | revue de presse IA (chaque matin) |
| `social_update.yml`, `apify_facebook.yml` | veille réseaux sociaux |
| `json-backup.yml` | sauvegarde des fichiers de données |
| `barometre_*.yml` | baromètre Algérie Digital (hebdo et mensuel) |
| `express.yml` | « L'info en 30 s » (6 h, 10 h, 15 h) |
| `flash-publier.yml`, `flash-retirer.yml`, `flash-verifier.yml` | vrai flash infos |
