# Regard Social - URL Permanente

Ce dépôt héberge une page de redirection automatique vers le dernier Regard Social publié par Prisme.

## 🔗 URL permanente

**https://tokasur.github.io/regard-social/**

Cette URL ne change jamais et redirige vers toujours le dernier Regard Social publié.

## 📁 Fichiers

- `index.html` : Page de redirection avec chargement dynamique
- `config.json` : Configuration contenant l'URL du dernier Regard Social

## 🔄 Mise à jour automatique

Ce dépôt est mis à jour automatiquement chaque vendredi par un workflow Power Automate qui :
1. Détecte le nouveau Regard Social sur https://prisme.netboard.me/
2. Met à jour le fichier `config.json`
3. GitHub Pages redéploie automatiquement la page

## 📊 Utilisation

Cette URL peut être utilisée :
- Dans une iframe sur un site web
- Comme lien partagé sur les réseaux sociaux
- Dans des emails ou newsletters

## 📝 Notes

- GitHub Pages se met à jour automatiquement après chaque commit
- La page utilise JavaScript pour charger dynamiquement l'URL depuis `config.json`
- Compatible avec l'affichage en iframe
