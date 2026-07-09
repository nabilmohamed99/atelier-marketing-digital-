# Atelier — Introduction au Marketing Digital

Page HTML statique prête pour GitHub Pages.

La version inclut un exercice de classification en glisser-déposer : les étudiants déplacent les termes vers les bonnes colonnes, puis cliquent sur “Corriger la classification”.

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


## Mise à jour — Page 3 SEO

Cette version ajoute une troisième page pédagogique **Référencement & SEO** avec :

- Quiz interactifs sur hébergement, indexation, positionnement, KPI et intentions de recherche.
- Ateliers Google Search Console avec captures intégrées.
- Calculs SEO guidés : CTR, part de trafic, lecture sitemap.
- Exercice drag & drop pour classifier les mots-clés.
- Corrections masquées par défaut, affichables avec les boutons de correction.

Pour publier la mise à jour sur GitHub Pages, remplacez `index.html`, ajoutez le dossier `assets/`, puis attendez le workflow Pages dans l'onglet **Actions**.
