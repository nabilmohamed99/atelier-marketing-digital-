# Atelier — Introduction au Marketing Digital + Page 2 SEA

Projet HTML statique prêt pour GitHub Pages.

## Pages incluses

- `index.html` : atelier principal Marketing Digital avec QCM, KPI, classification en glisser-déposer et étude de cas.
- `sea.html` : deuxième page SEA avec QCM interactif, calcul du Ad Rank, correction automatique et actions Quality Score.
- `.nojekyll` : fichier utile pour éviter le traitement Jekyll par GitHub Pages.

## Déploiement rapide avec GitHub Pages

1. Ajoutez `index.html`, `sea.html`, `README.md` et `.nojekyll` à la racine du dépôt GitHub.
2. Allez dans **Settings** → **Pages**.
3. Dans **Build and deployment**, choisissez **Deploy from a branch**.
4. Sélectionnez la branche `main` et le dossier `/root`, puis cliquez sur **Save**.
5. Après quelques minutes, la page principale sera disponible à l'adresse :
   `https://VOTRE-USERNAME.github.io/NOM-DU-REPO/`
6. La page SEA sera disponible à l'adresse :
   `https://VOTRE-USERNAME.github.io/NOM-DU-REPO/sea.html`

## Déploiement avec Git

```bash
git init
git add .
git commit -m "Ajouter atelier marketing digital et page SEA"
git branch -M main
git remote add origin https://github.com/VOTRE-USERNAME/NOM-DU-REPO.git
git push -u origin main
```

Ensuite, activez GitHub Pages depuis **Settings** → **Pages**.
