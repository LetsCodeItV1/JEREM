# Jere'm - Un Pont entre la Diaspora et Haïti

## Description
**Jere'm** est une plateforme innovante qui connecte la diaspora haïtienne à leurs proches en Haïti. Elle permet d'envoyer facilement des biens essentiels (alimentaires, matériaux de construction, produits de santé, etc.) tout en soutenant l'économie locale grâce à des partenariats avec des fournisseurs locaux. 

### Fonctionnalités principales
- **Commandes en ligne** : Sélectionnez des biens via une interface intuitive.
- **Paiements sécurisés** : Intégration avec des systèmes comme Zelle, MonCash et Stripe.
- **Livraison rapide et personnalisée** : Livraison avec suivi en temps réel.
- **Impact économique local** : Collaboration avec des commerçants locaux pour stimuler l'économie.

## Technologies Utilisées
- **Frontend** : Basé sur un template existant utilisant [React.js](https://react.dev) ou [Angular](https://angular.io).
- **Backend** : [Node.js](https://nodejs.org) avec [Express.js](https://expressjs.com).
- **Base de données** : [MongoDB](https://www.mongodb.com) et [Firestore](https://firebase.google.com/products/firestore).
- **Paiements** : Intégration de Stripe, MonCash, ou autres.

## Installation et Exécution
### Prérequis
- Node.js et npm installés sur votre machine.
- Un compte MongoDB (ou une instance locale).

### Étapes
1. Clonez ce repository :
   ```bash
   git clone https://github.com/votre-utilisateur/jere-m.git
   ```
2. Installez les dépendances dans les dossiers backend et frontend :
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```
3. Configurez les variables d'environnement :
   - Créez un fichier `.env` dans le dossier `backend` avec les informations suivantes :
     ```env
     MONGO_URI=<votre-url-mongodb>
     JWT_SECRET=<votre-clé-secrète>
     STRIPE_API_KEY=<votre-clé-stripe>
     ```
4. Lancez le serveur backend :
   ```bash
   cd backend
   npm run dev
   ```
5. Lancez le serveur frontend :
   ```bash
   cd ../frontend
   npm start
   ```
6. Accédez au site à l'adresse [http://localhost:3000](http://localhost:3000).

## Fonctionnalités à venir
- Notifications push pour les mises à jour de commandes.
- Tableau de bord pour les administrateurs afin de gérer les produits et les utilisateurs.
- Extension à d'autres régions d'Haïti.

## Contribution
Les contributions sont les bienvenues ! Veuillez suivre ces étapes :
1. Forkez le repository.
2. Créez une branche pour vos modifications :
   ```bash
   git checkout -b feature/nom-de-la-fonctionnalite
   ```
3. Faites vos modifications et commitez-les :
   ```bash
   git commit -m "Ajout de [fonctionnalité]"
   ```
4. Poussez vos modifications :
   ```bash
   git push origin feature/nom-de-la-fonctionnalite
   ```
5. Créez une Pull Request sur le repository principal.

## Licence
Ce projet est sous licence MIT. Veuillez consulter le fichier [LICENSE](LICENSE) pour plus de détails.

## Auteurs
- **Votre Nom** - Développeur principal
- **Contributeurs** - Merci à tous ceux qui ont aidé à faire de ce projet une réalité.

---
**Jere'm** - Plus qu'un service, un lien de solidarité entre la diaspora et leurs proches.

