🎭 Eventini – Application Mobile de Réservation d'Événements Culturels
Eventini est une application mobile Android développée en Java permettant aux utilisateurs de découvrir, consulter et réserver des événements culturels en Tunisie.
L'application est connectée à un backend Spring Boot et une base de données PostgreSQL.

📱 Fonctionnalités principales
🔍 Parcourir les événements : Liste des spectacles populaires et de tous les événements disponibles

🎟️ Réserver des billets : Choix du type de place (VIP, Normal, Économie)

📍 Géolocalisation : Localisation interactive des lieux d'événements

🔐 Authentification utilisateur : Inscription et connexion sécurisées

❤️ Gestion des favoris : Ajout et consultation des événements préférés

📅 Historique des réservations : Consultation des réservations passées

🎨 Interface intuitive : Conforme aux principes Material Design

🔎 Recherche et filtres : Filtrage par catégorie, date et notation

🛠️ Architecture Technique
Technologies utilisées
Composant	Technologies
Frontend Mobile	Android Studio, Java
UI / UX	Material Design, Glide
Réseau	Retrofit, OkHttp
Backend	Spring Boot, Hibernate, JPA
Base de données	PostgreSQL
Versioning	Git, GitHub
Design	Figma
Modèle de données (UML)
Les principales entités gérées sont :

Spectacle : Événements culturels (titre, date, durée, description, etc.)

Artiste : Intervenants des spectacles (nom, prénom, spécialité)

Lieu : Salles et adresses (nom, adresse, capacité, coordonnées GPS)

Billet : Tickets de réservation (catégorie, prix, statut)

User : Comptes utilisateurs (nom, email, mot de passe)

TicketPrice : Tarifs des billets par catégorie

Architecture Backend
API REST sécurisée avec Spring Boot

Couches : Controllers, Services, Repositories (JPA)

Authentification via Spring Security

Base de données relationnelle PostgreSQL

Endpoints principaux :

/api/auth : Connexion / Inscription

/api/events : Gestion des événements

/api/tickets : Réservation de billets

📲 Interfaces Utilisateur
L'application propose une navigation intuitive avec les écrans suivants :

Écran d'accueil : Liste des événements populaires, tous les spectacles et barre de recherche

Détails d'événement : Informations complètes, artistes, lieu et bouton de réservation

Connexion/Inscription : Authentification sécurisée des utilisateurs

Sélection de billet : Choix de la catégorie (VIP, Normal, Économie)

Confirmation de réservation : Récapitulatif et processus de paiement

🚀 Installation et Exécution
Prérequis
Android Studio

JDK 11+

PostgreSQL

Spring Boot (backend)

Étapes d'installation
Cloner le dépôt :

bash
git clone https://github.com/votre-username/eventini.git
Backend Spring Boot :

Importer le projet Spring Boot dans votre IDE

Configurer la base de données PostgreSQL dans application.properties

Lancer l'application Spring Boot

Application Android :

Ouvrir le projet Android dans Android Studio

Configurer l'URL de l'API dans le fichier de configuration

Synchroniser et construire le projet

Exécuter sur un émulateur ou appareil physique

⚠️ Difficultés Rencontrées et Solutions
Difficulté	Solution mise en œuvre
Gestion des dates/heures entre backend et mobile	Utilisation de LocalDateTime et conversion avec DateTimeFormatter
Affichage fluide des listes de spectacles	RecyclerView avec pagination et placeholder pendant le chargement
Gestion des favoris hors ligne	Stockage local avec SharedPreferences
Synchronisation des données	Architecture REST avec cache côté mobile
Gestion des erreurs réseau	Messages d'erreur explicites et bouton de réessai
Affichage des images artistes	Bibliothèque Glide avec cache et placeholder
👨‍💻 Auteur
Mohamed Ghaith Hamzaoui
Étudiant en développement mobile
Encadré par : Dr. Olfa Lamouchi
Année universitaire : 2024-2025
Date : 1er mai 2025

🔭 Currently Working On
Pitchi - New exciting project in development

🌱 Currently Learning
Android Generative AI - Exploring AI integration in mobile applications

Three JS - Learning 3D graphics and animations for web

📫 How to Reach Me
Email: mohamedghaith.hamzaoui@enicar.ucar.tn

🌍 Connect with Me
https://img.shields.io/badge/-Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white
https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white
https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white

🛠️ Tech Stack
🎨 Design
<div align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" width="50" height="50" alt="Figma" title="Figma"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/illustrator/illustrator-plain.svg" width="50" height="50" alt="Illustrator" title="Illustrator"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg" width="50" height="50" alt="Photoshop" title="Photoshop"/> </div>
💻 Languages
<div align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="50" height="50" alt="C" title="C"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="50" height="50" alt="C++" title="C++"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50" height="50" alt="Python" title="Python"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="50" height="50" alt="Java" title="Java"/> </div>
🌐 Web
<div align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="50" height="50" alt="HTML5" title="HTML5"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="50" height="50" alt="CSS3" title="CSS3"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" height="50" alt="JavaScript" title="JavaScript"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="50" height="50" alt="React" title="React"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" width="50" height="50" alt="Angular" title="Angular"/> </div>
⚙️ Backend
<div align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original-wordmark.svg" width="50" height="50" alt="Node.js" title="Node.js" style="filter: hue-rotate(30deg)"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original-wordmark.svg" width="50" height="50" alt="Express" title="Express" style="filter: grayscale(100%) brightness(0%)"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="50" height="50" alt="Spring" title="Spring"/> </div>
🗃️ Databases
<div align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="50" height="50" alt="PostgreSQL" title="PostgreSQL"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="50" height="50" alt="MongoDB" title="MongoDB"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" width="50" height="50" alt="Oracle" title="Oracle"/> </div>
🔧 Tools
<div align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="50" height="50" alt="Git" title="Git"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" width="50" height="50" alt="Postman" title="Postman"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" width="50" height="50" alt="Android Studio" title="Android Studio"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" width="50" height="50" alt="Arduino" title="Arduino"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="50" height="50" alt="Linux" title="Linux"/> </div>
📄 Licence
Ce projet est à but éducatif et n'est pas destiné à un usage commercial.
