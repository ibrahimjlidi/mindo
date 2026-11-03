# Mindo

Boutique en ligne statique pour Mindo, avec catalogue de produits, panier et commande via WhatsApp.

## Utilisation

Ouvrez `index.html` dans un navigateur. La page `contact.html` donne accès à WhatsApp et à Facebook. Le point jaune du logo ouvre le tableau dans `tableau.html`, avec une invite de mot de passe côté navigateur.

## Déploiement sur Vercel

Importez le dépôt GitHub `ibrahimjlidi/mindo` dans Vercel. Il s’agit d’un site HTML/CSS/JavaScript statique : choisissez **Other** si Vercel demande un framework, laissez la commande de build et le répertoire de sortie vides, puis déployez. La page d’accueil est `index.html`.

Les commandes sont préparées dans WhatsApp pour le numéro `+216 xxx xxx`. Le client vérifie et envoie lui-même le message.

### Important : mot de passe du tableau

L'invite de mot de passe de `tableau.html` est une barrière visuelle côté navigateur, pas une authentification. Le code et les données du classeur sont publiés avec la page et restent inspectables ou contournables. Ne l'utilisez pas pour protéger des informations confidentielles.
