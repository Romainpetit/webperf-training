Démos et code du TP de la formation Webperf.

# Utilisation

1. cloner le projet
2. `npm install`
3. `npm start`
4. ouvrir http://localhost:8181/ ou https://localhost:8181/ (accepter les alertes de sécurité)

- les démos sont listées, le répertoire est `demos` (forcément)
- l'exemple de site est dans le répertoire `tp-ecommerce`

# Déploiement
https://vibrant-lichterman-d36650.netlify.app/tp-ecommerce/home.html
### Version initiale, CSS dans un fichier séparé.
_Test fr, lte, samsung S7_ https://www.webpagetest.org/result/211124_BiDc8X_1424fa068b3ddd11741bf56ad786acad/

### Version avec CSS inliné 
_Test fr, lte, samsung S7_ https://www.webpagetest.org/result/211124_AiDcKS_8c0036f788f287d2e15b2cd4d93aa2b7/ 

#### Comparaison: 
https://www.webpagetest.org/video/compare.php?tests=211124_AiDcKS_8c0036f788f287d2e15b2cd4d93aa2b7,211124_BiDc8X_1424fa068b3ddd11741bf56ad786acad

# Tester

Publier sur un serveur de fichier statique ([Netlify](https://app.netlify.com/signup) est recommandé pour sa simplicité), avec une URL publique (Ex: https://formation-webperf.netlify.app/tp-ecommerce/), puis utiliser des outils comme Webpagetest pour voir les effets.

# Pré-requis

- utiliser Node 14 (`nvm use stable`)

# Licence

Lire le fichier LICENSE : aucune autre utilisation que de s'entraîner sur ce code pendant et après la formation Webperf n'est autorisée.
