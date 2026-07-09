# Atelier — Introduction au Marketing Digital

Page HTML statique prête pour GitHub Pages.

## Déploiement rapide avec GitHub Pages

1. Créez un nouveau dépôt GitHub, par exemple `atelier-marketing-digital`.
2. Ajoutez les fichiers `index.html` et `.nojekyll` à la racine du dépôt.
3. Allez dans **Settings** → **Pages**.
4. Dans **Build and deployment**, choisissez **Deploy from a branch**.
5. Sélectionnez la branche `main` et le dossier `/root`, puis cliquez sur **Save**.
6. Après quelques minutes, la page sera disponible à l'adresse :
   `https://VOTRE-USERNAME.github.io/atelier-marketing-digital/`

## Déploiement avec Git

```bash
git init
git add .
git commit -m "Publier l'atelier marketing digital"
git branch -M main
git remote add origin https://github.com/VOTRE-USERNAME/atelier-marketing-digital.git
git push -u origin main
```

Ensuite, activez GitHub Pages depuis **Settings** → **Pages**.
