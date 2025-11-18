# Regard Social - URL Permanente

EN CONSTRUTION NE PAS UTILISER POUR LE MOMENT

Ce dépôt héberge une page de redirection automatique vers le dernier Regard Social publié par Prisme.

## 🔗 URL permanente

**https://github.io/Tokasur/regard-social**

Cette URL ne change jamais et affiche toujours le dernier Regard Social publié.

## 📁 Fichiers

- `index.html` : Page de redirection avec chargement dynamique
- `config.json` : Configuration contenant l'URL du dernier Regard Social

## 🔄 Mise à jour automatique

Ce dépôt est mis à jour automatiquement chaque vendredi par un workflow Power Automate qui :
1. Détecte le nouveau Regard Social sur https://prisme.netboard.me/
2. Met à jour le fichier `config.json`
3. GitHub Pages redéploie automatiquement la page

## 🛠️ Modification manuelle

Pour mettre à jour manuellement l'URL du Regard Social :

1. Éditez `config.json`
2. Modifiez la valeur de `latest_url`
3. Commitez les changements

Le changement sera visible en 1-2 minutes.

## 📊 Utilisation

Cette URL peut être utilisée :
- Dans une iframe sur un site web
- Comme lien partagé sur les réseaux sociaux
- Dans des emails ou newsletters

## 📝 Notes

- GitHub Pages se met à jour automatiquement après chaque commit
- La page utilise JavaScript pour charger dynamiquement l'URL depuis `config.json`
- Compatible avec l'affichage en iframe
