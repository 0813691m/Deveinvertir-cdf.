# 📱 Deveinvertir CDF

**Deveinvertir CDF** est une application d'investissement conçue pour la République Démocratique du Congo (RDC).  
Elle offre plusieurs fonctionnalités pour permettre à chaque utilisateur de gérer ses investissements, recharges, retraits et parrainages en toute sécurité.

---

## 🏗️ Architecture des pages de l’application

### 1️⃣ Première page – Onboarding / Splash
- **Description :** Présentation du logo, slogan et navigation vers l’inscription ou la connexion.
- **Boutons :**
  - S’inscrire
  - Se connecter

### 2️⃣ Page d’inscription
- **Description :** Création de compte utilisateur/service.
- **Champs requis :**
  - Email
  - Mot de passe
  - Nom et prénom
  - Numéro de téléphone
  - Rôle (choix parmi 5 rôles)
  - Code d’invitation (si applicable)
- **Bouton :** S’inscrire

### 3️⃣ Page de sélection du rôle
- **Description :** Chaque nouvel utilisateur/service choisit son rôle :
  1. **Admin**
  2. **Agent de recharge**
  3. **Agent de retrait**
  4. **Super agence**
  5. **Directeur technique**

### 4️⃣ Page de connexion
- **Description :** Connexion avec email et mot de passe.
- **Boutons :**
  - Se connecter
  - Mot de passe oublié
  - Créer un compte

### 5️⃣ Tableau de bord (Accueil utilisateur/service)
- **Description :** Vue principale après connexion, adaptée selon le rôle.
- **Composants principaux :**
  - Solde actuel
  - Bouton Recharger
  - Bouton Investir
  - Accès rapide : investissements en cours, annonces, invitations, profil

### 6️⃣ Page d’investissement en cours
- **Description :** Liste des investissements actifs.
- **Actions :**
  - Voir détails (montant, durée, gains)
  - Retirer bénéfice (si disponible)

### 7️⃣ Page d’annonces
- **Description :** Affichage des annonces officielles ou informations importantes.

### 8️⃣ Page d’invitations / Parrainage
- **Description :** Parrainage d’utilisateurs et suivi des filleuls.
- **Fonctionnalités :**
  - Affichage du code d’invitation
  - Partage du code
  - Liste des parrainages réussis
  - Un utilisateur peut inviter d'autres utilisateurs, et chaque nouvel utilisateur peut investir et faire gagner un bonus à son parrain.

### 9️⃣ Page de profil
- **Description :** Gestion des informations personnelles et du rôle.
- **Actions :**
  - Modifier le mot de passe
  - Modifier les informations personnelles
  - Déconnexion
  - Voir le rôle attribué

---

## 🔑 Système des rôles et gestion des droits

### Utilisateur
- Peut :  
  - Recharger son compte  
  - Investir  
  - Retirer ses gains  
  - Parrainer d'autres utilisateurs (gagner un bonus)  
  - Être averti, bloqué ou débloqué par un agent/admin  
- Actions sur son argent :
  - Charger
  - Retirer
  - Investir
  - Recevoir un avertissement ou être bloqué par un agent/admin

### Agent (Recharge / Retrait)
- Peut :
  - Confirmer ou valider une transaction de recharge ou de retrait  
  - Rejeter ou supprimer une transaction  
  - Bloquer/débloquer un utilisateur  
  - Envoyer des avertissements

### Admin, Super agence, Directeur technique
- Ont tous les droits de gestion, validation, supervision, sécurité, et modération sur la plateforme.

---

## 🔘 Boutons et actions récurrents

- **Recharger** : Ajouter des fonds via Mobile Money.
- **Investir** : Placer de l’argent dans une caisse.
- **Retirer** : Retirer les gains selon les conditions.
- **Partager code** : Parrainer par invitation.
- **Déconnexion**
- **Console de montant** : Champ pour saisir le montant à investir/recharger/retirer.
- **Confirmer / Valider / Rejeter / Supprimer** (agents/admins)
- **Avertir / Bloquer / Débloquer** (agents/admins)

---

## 📋 Conditions d’utilisation

- Montant minimum de recharge : 20 000 CDF
- Montant maximum de recharge : 5 000 000 CDF
- Montant minimum de retrait : 20 000 CDF
- Montant maximum de retrait : 500 000 CDF
- Retraits disponibles uniquement sur les bénéfices
- 2 % de chaque retrait sont envoyés vers la **Caisse Smart**

---

## 🛠 Développé par

**Mulumba Dev**  
📍 République Démocratique du Congo  
📧 Email : `annytamulumba@gmail.com`

---

## 🌐 Informations techniques

- **Nom du projet :** Deveinvertir CDF
- **Langue principale :** Français
- **Version web :** [ulumbardev.infinityfreeapp.com](http://ulumbardev.infinityfreeapp.com)
- **Dépôt GitHub :** [`github.com/0813691m/Apk-Deveinvertir-cdf-`](https://github.com/0813691m/Apk-Deveinvertir-cdf-)

---

## 🚀 Objectif

Promouvoir l’investissement local, intelligent et accessible à tous les Congolais grâce à une application mobile simple, rapide et sécurisée.

---

## 💡 Commandes Git pour publier

```bash
git init
git add .
git commit -m "Ajout de mon application depuis Base Studio"
git remote add origin https://github.com/0813691m/Apk-Deveinvertir-cdf-.git
git push -u origin main
```

---

> **Astuce** : Ajoute des captures d’écran de chaque page pour rendre la documentation plus visuelle et claire !
