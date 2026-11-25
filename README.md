
1. Créez un dépôt GitHub (de préférence **privé** si vous ne souhaitez pas rendre le code public ; vérifiez les conditions GitHub Pages de votre compte avant de choisir le dépôt privé).
2. À la racine du dépôt, téléversez `index.html` et `.nojekyll`.
3. Cliquez sur **Settings → Pages**.
4. Dans **Build and deployment**, choisissez **Deploy from a branch**.
5. Choisissez la branche `main` et le dossier `/ (root)`, puis cliquez sur **Save**.
6. Attendez la publication ; GitHub affichera l'adresse du site dans la section Pages.

## Important — limites de cette version statique

Cette version fonctionne sans serveur. Les dossiers, paramètres et tarifs sont enregistrés dans le stockage local du navigateur (`localStorage`) de chaque appareil.

- Les données d'un navigateur ne sont **pas partagées** avec les autres utilisateurs ou appareils.
- Effacer les données du navigateur peut supprimer les dossiers locaux. Utilisez régulièrement **Administration → Télécharger une sauvegarde complète** et conservez le fichier JSON ailleurs.
- L'écran d'accès hors ligne n'est pas une authentification serveur : ne considérez pas cette version comme un espace sécurisé pour des données confidentielles.
- Pour un usage collaboratif avec dossiers partagés et comptes réellement protégés, il faut une API et une base de données hébergées. Ce dépôt statique seul ne fournit pas ces fonctions.

## Fichier principal

`index.html` contient l'application autonome. Les règles de cotation et l'interface ont été reprises du fichier HTML autonome fourni pour ce projet ; aucune modification des règles métier n'est prévue dans cette préparation.
# iag-apps-test2
