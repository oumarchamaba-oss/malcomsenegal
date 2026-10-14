# Portfolio Boubacar Sakho (Malcolm)

Site statique (HTML + images), sans build.

## Déployer
1. Créez un dépôt GitHub, puis : `git init && git add . && git commit -m "Portfolio" && git branch -M main && git remote add origin <URL> && git push -u origin main`
2. Sur vercel.com : **Add New > Project**, importez le dépôt. Framework : *Other*. Aucun build, dossier racine `/`. Cliquez **Deploy**.
3. **Aperçu WhatsApp / Facebook** : l'image d'aperçu (`img/og.jpg`, portrait de Malcom) est branchée automatiquement. Au déploiement, Vercel remplace `__SITE__` dans `index.html` par l'adresse de votre site (voir `buildCommand` dans `vercel.json`). Si vous préférez le faire à la main, remplacez `__SITE__` par votre domaine (sans `https://`) dans `index.html`, et supprimez la ligne `buildCommand`.
4. Si WhatsApp ou Facebook affichent encore l'ancien aperçu, forcez la mise à jour avec le débogueur de partage de Facebook (developers.facebook.com/tools/debug) : ils gardent l'aperçu en cache.
