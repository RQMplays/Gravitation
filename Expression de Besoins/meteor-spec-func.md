Auteur : Benoit 'RQM-' Laurent  
Date de dernière M.A.J: 09/01/2018  
Version : 1.4.0  

# Spécification Fonctionnelles

## Scénario d'utilisation de l'application

### Scénario d'inscription d'un utilisateur
![Inscription](images/inscription.png "Inscription")

### Scénario de connexion d'un utilisateur déjà inscrit
![Connexion](images/connexion.png "Connexion")

### Scénario d'un utilisateur déjà connecté
![Dashboard](images/dashboard.png "Dashboard")

## F1 Gestion des comptes utilisateurs

### F1.1 Navigation entre création de compte/connexion à un compte existant
**SpecTech** : T1.1  
une barre de navigation permet de passer du formulaire de connexion à un compte existant au formulaire de création de compte  

### F1.2 Création d'un compte utilisateurs
**SpecTech** : T1.2  
L'utilisateur peut créer un compte propre au site web en remplissant un formulaire de création de compte.
Ce formulaire comprend 4 champs à remplir et un bouton de validation.
les quatres champs à remplir sont :
 * Nom d'utilisateur ( Username )
 * Adresse E-mail ( Email )
 * Mot de passe ( Password )
 * Confirmation de mot de passe ( Confirmation )  

### F1.3 Connexion à un compte utilisateur existant
**SpecTech** : T1.3  
l'utilisateur peut se connecter à un compte existant en remplissant un formulaire comprenant deux champs à remplir et un bouton de validation.
Ces deux champs sont :
 * Nom d'utilisateur ou E-mail ( Username or Email )
 * Mot de passe ( Password )  

### F1.4 Affichage des Erreurs après validation d'un formulaire de création de compte erronées/connexion à un compte erronées
**SpecTech** : T1.4  
Un message d'Erreurs expliquant à l'utilisateur pourquoi la création de compte ne s'est pas bien déroulé est affiché en haut du formulaire le cas échéant  

### F1.5 Redirection après envoi d'un formulaire de création de compte ou de connexion à un compte existant
**SpecTech** : T1.5  
Si la création de compte ou connexion à un compte s'est bien déroulé, l'utilisateur est alors redirigé vers l'écran principal de l'application, le Dashboard.  

### F1.6 Déconnexion d'un utilisateur
**SpecTech** : T1.6  
L'utilisateur aura accès à un bouton pour ce déconnecter à partir du Dashboard, il serra alors redirigé vers la vue de connexion à un compte/création de compte  

## F2 Utilisateurs connectés

### F2.1 Visualisation des utilisateurs connectés
**SpecTech** : T2.1  
Les pseudonymes ainsi que les status de connection des utilisateurs actuellement connectés sont visible par les autres utilisateurs, et ce en temps réel.  

## F3 Gestion du jeu

### F3.1 Intégration du jeu
**SpecTech** : T3.1  
L'utilisateur peut appuyer sur un Bouton 'Play' pour afficher/cacher le canvas du jeu.  

## F3.2 Gestion d'une base de données représentative de l'état du jeu multijoueur
**SpecTech** : T3.2  
Work In Progress  
