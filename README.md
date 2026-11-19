# Unlock! Collection & Tracker

Application web en français pour suivre une collection de boîtes Unlock! et la progression dans leurs scénarios.

## Utilisation

Ouvrez `index.html` ou directement `unlock_collection_tracker.html` dans un navigateur récent. `index.html` redirige vers l’application et sert de page d’entrée à GitHub Pages.

La page charge Tailwind CSS, Font Awesome et les polices Google Fonts depuis leurs CDN : une connexion Internet est donc nécessaire pour afficher correctement le style et les icônes.

## Publication sur GitHub Pages

1. Créez un dépôt GitHub vide, puis ajoutez-le comme dépôt distant et poussez la branche `main` :

   ```sh
   git remote add origin https://github.com/<votre-compte>/<votre-depot>.git
   git push -u origin main
   ```

2. Dans le dépôt GitHub, ouvrez **Settings → Pages**.
3. Dans **Build and deployment**, choisissez **Deploy from a branch**, puis sélectionnez la branche `main` et le dossier `/ (root)`.
4. Après le déploiement, le site sera disponible à l’adresse indiquée dans cette page des paramètres. `index.html` redirigera vers le tracker.

## Fonctionnalités

- Parcourir le catalogue et rechercher par boîte, scénario, édition ou année.
- Filtrer par catégorie et état, trier les boîtes et choisir entre les vues liste et grille.
- Suivre les scénarios terminés et noter les scénarios ou les boîtes.
- Importer des jaquettes individuellement ou charger un dossier de jaquettes dont les noms correspondent aux identifiants du catalogue.
- Exporter et importer une sauvegarde JSON.
- Réinitialiser la progression et les notes sans supprimer les jaquettes importées.

## Données et sauvegardes

La progression, les notes et les jaquettes sont enregistrées dans le stockage local du navigateur. Elles ne sont pas synchronisées entre navigateurs ou appareils. Exportez régulièrement une sauvegarde JSON pour conserver ou transférer votre progression.

## Technologies

Cette application est constituée d’un seul fichier HTML, avec le CSS et le JavaScript intégrés. Elle n’utilise pas d’étape de build ni de dépendances locales.
