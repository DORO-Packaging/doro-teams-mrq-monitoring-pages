# doro-teams-mrq-monitoring-pages

## Pourquoi ce dépôt existe

DORO a développé une application Microsoft Teams interne, **DORO Teams MRQ Monitoring**. Elle aide à faire respecter une règle simple dans les équipes `MRQ-*` : les documents sont déposés dans l’onglet **Fichiers / Documents** du canal, puis partagés sous forme de lien dans les publications, au lieu d’être joints directement aux messages.

Pour être installée dans Teams, une application doit déclarer dans son manifeste trois adresses web publiques :

- une page de présentation (`websiteUrl`) ;
- une politique de confidentialité (`privacyUrl`) ;
- des conditions d’utilisation (`termsOfUseUrl`).

Microsoft exige que ces pages soient accessibles en HTTPS, sans authentification. Ce dépôt sert uniquement à les héberger, gratuitement et simplement, grâce à GitHub Pages.

## Ce qu’il contient

- `index.md` : présentation de l’application ;
- `privacy.md` : politique de confidentialité ;
- `terms.md` : conditions d’utilisation ;
- `_config.yml`, `_layouts/`, `assets/` : mise en page aux couleurs de la charte graphique DORO.

Il ne contient ni le code de l’application, ni secret, ni donnée personnelle.
