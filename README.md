# Basket autour de Cholet — carte interactive

Site statique pour GitHub Pages, sans compilation ni serveur.

## Publication

1. Créer un dépôt public GitHub, par exemple `basket-cholet`.
2. À la racine du dépôt, ajouter **le contenu du ZIP** (et non le ZIP lui-même) : `index.html`, `terrains_basket_cholet.geojson`, `.nojekyll` et `README.md`.
3. Dans **Settings → Pages**, sous **Build and deployment**, sélectionner **Deploy from a branch**, puis `main`, `/ (root)` et **Save**.
4. Une fois le déploiement terminé, le site sera accessible à `https://VOTRE_PSEUDO.github.io/basket-cholet/`.

## Utilisation

Carte interactive, filtres d'accès, recherche et itinéraires Google Maps. Le bouton **Partager** utilise la feuille de partage de votre téléphone ou copie le lien.

## Limitations

20 fiches provenant du recensement initial : 10 positions indicatives sur la carte et 10 lieux avec adresse mais sans géocodage fiable. Les lieux ne sont pas tous confirmés accessibles au public ; aucun cliché de terrain n'a été authentifié. Il ne s'agit pas d'un inventaire exhaustif. Les tuiles de fond et la bibliothèque Leaflet sont chargées en ligne.

Données GeoJSON fournies pour les 10 lieux géolocalisés.
