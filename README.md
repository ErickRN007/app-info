# Pages légales pour l’écran de consentement OAuth

Ce dépôt contient les pages minimales attendues par Google pour configurer l’écran de consentement OAuth pendant la phase de test.

## Fichiers
- `index.html` : page d’accueil simple avec liens.
- `privacy.html` : règles de confidentialité.
- `terms.html` : conditions d’utilisation.

## Déploiement sur GitHub Pages
1. Créez un dépôt public (par ex. `mon-app-info`) et uploadez ces fichiers à la racine.
2. Dans **Settings → Pages** :
   - **Source** : branche `main`
   - **Folder** : `/ (root)`
3. Ouvrez ensuite :
   - `https://<votre-user>.github.io/<nom-du-depot>/privacy.html`
   - `https://<votre-user>.github.io/<nom-du-depot>/terms.html`

## À personnaliser
- Remplacez `contact@example.com` par votre adresse de contact.
- Remplacez “Mon Application” par le nom de votre application.
