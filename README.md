# Audit_Admin_integrated_account

# Audit du compte Administrateur intégré - Active Directory

Script PowerShell pour auditer l'utilisation du compte Administrateur intégré (SID S-1-5-21-*-500) dans un environnement Active Directory.

## 📋 Description

Ce script permet de détecter :
- Les tâches planifiées utilisant le compte Administrateur
- Les services configurés avec le compte Administrateur
- Le statut et dernière connexion du compte
- Génère un rapport CSV détaillé

## 🚀 Fonctionnalités

- Audit centralisé de l'ensemble du parc
- Rapport au format CSV

## ⚙️ Pré-requis

- PowerShell 5.1+
- Module ActiveDirectory
- Module ScheduledTasks
- Droits Domain Admins
- Stratégie d'exécution PowerShell : `RemoteSigned`

