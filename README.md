# Système de Gestion de l'Apprentissage en Ligne (LEARN_CONNECT)

## Introduction

**LEARN_CONNECT** est une plateforme eLearning complète et innovante construite avec **Laravel**. Elle offre une solution robuste pour la gestion de cours en ligne, permettant aux étudiants de suivre des formations gratuites ou payantes tout en offrant des outils avancés pour les instructeurs et les administrateurs.  

Cette application vise à simplifier le processus d'apprentissage en ligne tout en fournissant une expérience utilisateur optimale et sécurisée.

---

## Fonctionnalités

- **Authentification des Utilisateurs :**  
  Gestion sécurisée de l'inscription, de la connexion et des comptes des utilisateurs.  

- **Gestion des Rôles et Permissions :**  
  - Rôles intégrés : SuperAdmin, Instructeur et Étudiant.  
  - Permissions spécifiques adaptées à chaque rôle.  

- **Gestion des Cours :**  
  - Création, publication et gestion des cours par les instructeurs.  
  - Les étudiants peuvent s'inscrire à des cours et accéder à des contenus interactifs.  

- **Organisation des Cours :**  
  - Classement des cours par catégories et types pour une navigation intuitive.  

- **Gestion des Profils Utilisateurs :**  
  - Mise à jour des informations personnelles.  
  - Visualisation des cours inscrits et suivis.  

- **Système de Paiement Intégré :**  
  - Ajout de cours au panier.  
  - Paiement sécurisé pour les cours payants.  

- **Accès au Contenu des Cours :**  
  - Contenus riches : vidéos, documents, quiz et autres supports pédagogiques.  

- **Filtres de Recherche Avancés :**  
  Recherche rapide et précise de cours en fonction de catégories ou autres critères.  

---

## Stack Technologique

- **Framework Backend :** Laravel (PHP)  
- **Base de Données :** MySQL  
- **Frontend :** HTML, CSS, jQuery  
- **Moteur de Templates :** Laravel Blade  

---

## Identifiants de Démonstration

- **SuperAdmin :**  
  - Email : `admin@gmail.com`  
  - Mot de passe : `123`  

- **Instructeur :**  
  - Email : `instuteur@gmail.com`  
  - Mot de passe : `1234`  

---

## Installation et Démarrage

Suivez ces étapes pour configurer et démarrer le projet localement :

1. **Cloner le dépôt :**  
   ```bash
   git clone https://github.com/Djennhya/LEARN_CONNECT.git
   cd LEARN_CONNECT
   ```

2. **Installer les dépendances PHP :**  
   ```bash
   composer install
   ```

3. **Configurer le fichier `.env` :**  
   - Dupliquez le fichier `.env.example` et renommez-le en `.env`.  
   - Configurez vos informations de connexion à la base de données :  
     ```env
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=laravel_elearning
     DB_USERNAME=root
     DB_PASSWORD=
     ```

4. **Générer la clé de l'application :**  
   ```bash
   php artisan key:generate
   ```

5. **Migrer la base de données :**  
   ```bash
   php artisan migrate
   ```

6. **Installer les dépendances front-end :**  
   ```bash
   npm install
   npm run dev
   ```

7. **Lancer le serveur de développement :**  
   ```bash
   php artisan serve
   ```

   L'application sera accessible depuis : [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## Auteur

Développé par [Djennhya](https://github.com/Djennhya).  
Pour toute question ou suggestion, n'hésitez pas à me contacter.
