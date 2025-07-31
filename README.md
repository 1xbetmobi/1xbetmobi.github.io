# Boutique E-commerce Jeux Vidéo

Ce projet est une boutique en ligne dédiée à la vente de jeux vidéo, développée en HTML, CSS, JavaScript et utilisant Firebase pour l’authentification.

## Structure du projet

```
ecommerce-jeux/
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   ├── auth.js
│   └── firebase-config.js
├── data/
│   └── produits.json
├── pages/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── admin.html
│   └── product.html
├── index.html
├── cart.html
├── checkout.html
├── confirmation.html
├── 404.html
└── README.md
```

## Fonctionnalités

- **Accueil** : Affichage des jeux disponibles
- **Panier** : Ajout et gestion des jeux à acheter
- **Commande** : Validation et confirmation d'achat
- **Authentification** : Inscription, connexion, déconnexion via Firebase
- **Admin** : (statique) Ajout de nouveaux jeux (à connecter à Firestore si besoin)

## Installation

1. Cloner le repo ou copier la structure.
2. Ajouter vos clés Firebase dans `js/firebase-config.js`.
3. Héberger sur un serveur statique (ou utiliser Live Server en local).

## À venir

- Connexion à Firestore pour stocker produits et commandes
- Gestion avancée du panier
- Sécurité et gestion des droits admin

## Auteur

Projet de démonstration généré par Copilot - à personnaliser !