# Publication GitHub Pages

## Fichiers à publier

- `index.md`
- `privacy.md`
- `terms.md`
- `_config.yml`

## Procédure

1. Créer un dépôt GitHub nommé `doro-teams-mrq-monitoring-pages` dans l’organisation GitHub DORO.
2. Utiliser un dépôt **public** si l’organisation utilise GitHub Free. GitHub Pages est disponible pour les dépôts privés avec les offres GitHub Pro, Team ou Enterprise Cloud.
3. Ajouter les quatre fichiers à la racine de la branche `main`.
4. Ouvrir **Settings** > **Pages**.
5. Dans **Build and deployment**, choisir **Deploy from a branch**.
6. Sélectionner la branche `main` et le dossier `/ (root)`, puis enregistrer.
7. Attendre la fin du déploiement dans **Actions** ou **Settings** > **Pages**.
8. Ouvrir l’URL affichée par GitHub Pages et contrôler les trois pages.

## URL attendue

Si l’organisation GitHub est `<organisation>` et le dépôt `doro-teams-mrq-monitoring-pages` :

- Accueil : `https://<organisation>.github.io/doro-teams-mrq-monitoring-pages/`
- Confidentialité : `https://<organisation>.github.io/doro-teams-mrq-monitoring-pages/privacy.html`
- Conditions : `https://<organisation>.github.io/doro-teams-mrq-monitoring-pages/terms.html`

## Valeurs à reporter dans le manifeste Teams

```json
"developer": {
  "name": "DORO",
  "websiteUrl": "https://<organisation>.github.io/doro-teams-mrq-monitoring-pages/",
  "privacyUrl": "https://<organisation>.github.io/doro-teams-mrq-monitoring-pages/privacy.html",
  "termsOfUseUrl": "https://<organisation>.github.io/doro-teams-mrq-monitoring-pages/terms.html"
}
```

## Contrôles avant publication Teams

- Les trois URL répondent en HTTPS sans authentification.
- Les pages ne contiennent aucun secret, identifiant technique sensible ou donnée personnelle.
- Le texte a été validé par les responsables internes DORO appropriés.
- Le manifeste Teams utilise les URL exactes publiées.
