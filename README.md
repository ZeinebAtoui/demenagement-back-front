# demenagement-back-front
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
- Framework: Angular
- Langage : TypeScript
- Architecture : MVC (Model-View-Controller)

## Structure du Projet

Le projet est divisé en deux parties principales : le Backend (Spring Boot) et le Frontend (Angular).
```text

 |-- DemenagementBackFront-main
    |-- client
      |-- .vscode
      |-- src
        |-- app
          |-- admin
            |-- acceuil
            |-- add-camion
            |-- add-chauffeur
            |-- assigner-chauffeur
            |-- detail-chauffeur
            |-- list-camion
            |-- list-chauffeur
            |-- list-client
            |-- list-demenagement
          |-- auth
            |-- sign-in
            |-- sign-up
          |-- chauffeur
            |-- list-demenagement
          |-- client
            |-- add-demenagement
            |-- list-demenagement
          |-- error
            |-- forbiden
          |-- guards
          |-- interceptor
          |-- layout
            |-- admin-layout
            |-- auth-layout
            |-- chauffeur-layout
            |-- client-layout
            |-- error-layout
            |-- main-layout
          |-- main
            |-- home
          |-- models
          |-- services
          |-- shared
            |-- navbar
            |-- sidebar
        |-- assets
          |-- homeimg
          |-- images
        |-- environments
    |-- ProjectDemenagment
      |-- .mvn
        |-- wrapper
      |-- src
        |-- main
          |-- java
            |-- com
              |-- example
                |-- ProjectDemenagment
                  |-- config
                  |-- contollers
                  |-- DTOs
                    |-- request
                    |-- response
                  |-- exceptions
                  |-- models
                  |-- repositories
                  |-- securities
                    |-- jwt
                    |-- services
                  |-- services
                  |-- utils
          |-- resources
            |-- templates
        |-- test
          |-- java
            |-- com
              |-- example
                |-- ProjectDemenagment





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
