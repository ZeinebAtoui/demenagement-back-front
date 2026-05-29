# DemenagementBackFront
 #  Plateforme de Réservation de Déménagements

Ce projet est une application web Fullstack permettant la gestion et la réservation de services de déménagement. 

##  Fonctionnalités clés
- **Authentification Sécurisée** : Mise en place de Spring Security avec authentification par Token **JWT**.
- **Gestion des Réservations** : Système complet de prise de rendez-vous et suivi via une interface dynamique.
- **Notifications** : Système intégré d'envoi automatique de mails de confirmation.
- **API REST** : Communication fluide entre le frontend et le backend via des services RESTful.

##  Stack Technique

### Backend (Java / JEE)
- **Framework** : Spring Boot
- **Sécurité** : Spring Security & JSON Web Token (JWT)
- **Gestion de projet** : Maven
- **Serveur d'application** : Apache Tomcat
- **Base de données** : MySQL

### Frontend
- **Framework** : Angular
- **Langage** : TypeScript
- **Architecture** : MVC (Model-View-Controller)

## Structure du Projet

Le projet est divisé en deux parties principales : le Backend (Spring Boot) et le Frontend (Angular).

###  Backend (Spring Boot)

src/main/java/com/project/demenagement/
├── config/             # Configuration Spring Security & CORS
├── controller/         # Points d'entrée de l'API (REST Controllers)
├── dto/                # Objets de transfert de données (Request/Response)
├── entity/             # Modèles de données (JPA/Hibernate Entities)
├── repository/         # Interfaces pour l'accès à la base de données
├── service/            # Logique métier du projet
└── security/           # Configuration JWT, Filtres et UserDetailsService
    ├── jwt/            # Logique de génération et validation des tokens
    └── services/       # Implémentation de la sécurité utilisateur

src/main/resources/
└── application.properties # Configuration MySQL, Port et Clé JWT
### Frontend


src/app/
├── components/         # Composants UI (Login, Reservation, Home, etc.)
├── services/           # Services pour les appels API vers le Backend
├── models/             # Interfaces TypeScript (User, Reservation)
├── guards/             # Protections de routes (AuthGuard)
├── interceptors/       # Intercepteur JWT pour ajouter le Token aux requêtes
├── app-routing.module.ts # Configuration des routes de l'application
└── app.component.html  # Structure principale de l'interface


##  Installation et Utilisation
1. Clonez le dépôt : `git clone https://github.com/ZeinebAtoui/demenagement-back-front.git`
2. Configurez la base de données MySQL dans le fichier `application.properties`.
3. Lancez le Backend via Maven ou votre IDE.
4. Installez les dépendances du Frontend : `npm install`.
5. Lancez le Frontend : `ng serve`.

##  Compétences mises en œuvre
- Développement d'API REST robustes.
- Sécurisation d'applications web modernes.
- Intégration de services tiers (Emailing).
- Collaboration via Git/GitHub.
