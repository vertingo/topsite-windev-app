![Image](https://raw.githubusercontent.com/vertingo/Easy_Admin_YouTube_Newsletter_Firebase/master/web/assets/images/github/vertin_go_website.jpg)
### Apporter votre soutien au projet :heart: pour de futures évolutions!
[![GitHub stars](https://img.shields.io/github/stars/vertingo/screenshott.svg?style=social&label=Star)](https://github.com/vertingo/WinDevTopSiteApp) [![GitHub forks](https://img.shields.io/github/forks/vertingo/screenshott.svg?style=social&label=Fork)](https://github.com/vertingo/WinDevTopSiteApp/fork) [![GitHub watchers](https://img.shields.io/github/watchers/vertingo/screenshott.svg?style=social&label=Watch)](https://github.com/vertingo/WinDevTopSiteApp) [![GitHub followers](https://img.shields.io/github/followers/vertingo.svg?style=social&label=Follow)](https://github.com/vertingo)
[![Twitter Follow](https://img.shields.io/twitter/follow/Vertin_Go.svg?style=social)](https://twitter.com/Vertin_Go)

# WinDev(https://www.pcsoft.fr/) Illustrations de l'applications TopSiteApp pour ne rien manquer des dernières news VertinGo Website en un clic depuis votre bureau!
L'exécutable de l'installateur disponible à l'adresse suivante: 
http://vertin-go.com/Fonctions_Annexes/annexes/pdt-page-de-telechargement/install/download.php?fichier=Install_Ex%C3%A9cutable_Windows_32_bits


<p align="center">
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="https://raw.githubusercontent.com/vertingo/WinDevTopSiteApp/master/Images/TopSiteApp.png" width="650" height="350"/></a>
  <br>
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="https://raw.githubusercontent.com/vertingo/WinDevTopSiteApp/master/Images/TopSiteApp2.png" width="650" height="350"/></a>
   <br>
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="https://raw.githubusercontent.com/vertingo/WinDevTopSiteApp/master/Images/TopSiteApp3.png" width="650" height="350"/></a>
   <br>
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="https://raw.githubusercontent.com/vertingo/WinDevTopSiteApp/master/Images/TopSiteApp4.png" width="650" height="350"/></a>
   <br>
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="https://raw.githubusercontent.com/vertingo/WinDevTopSiteApp/master/Images/TopSiteApp5.png" width="650" height="350"/></a>
   <br>
  <a href="https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1"><img src="https://raw.githubusercontent.com/vertingo/WinDevTopSiteApp/master/Images/TopSiteApp6.png" width="650" height="350"/></a>
</p>


# Tutoriel pour se Familiariser avec WinDEV: Création d'un projet sur WinDev et persistance des données

- Créer un projet depuis l'interface accueil de Windev

- Nommer votre projet et passer directement à la partie chartes. Sélectionnez "Gensteel"

- Passer à l'étape base de données

## Création de l'analyse

- Par défaut, le nom de l'analyse correspond au nom du projet et le répertoire de l'analyse est 
un répertoire ".ana" dans le répertoire du projet. Conserver ces paramètres par défaut.

- Sélectionnez le type de base de donnée HFSQL

- Passez à l'étape suivante de l'assistant. Validez. 
L'assistant de création d'un fichier de données se lance automatiquement.

## Création de la description des fichiers de données

- Nous allons créer maintenant les tables suivantes: Client, Commande, ModeRèglement, LigneCommande, Produit.
Pour se faire nous allons avoir recourt à plusieurs méthodes

Première methode: Création d'un fichier de données : utilisation d'un fichier prédéfini
- Placer vous dans l'onglet Analyse et cliquer sur Nouveau.
Sélectionnez dans l'assistant l'option "Sélectionner une description parmi des fichiers de données prédéfinis"

- Nous allons créer le fichier "Client". Dans la liste des fichiers de données, sélectionnez "Client". 
Passez à l'étape suivante.

- L'assistant propose la liste des rubriques à intégrer dans le fichier Client
Cochez uniquement les rubriques suivantes : IDClient, Société, Nom, Prénom, Adresse, CodePostal, Ville, EtatDep, Pays, Téléphone, Mobile, Email. 

- Validez
Le fichier "Client est automatiquement créé sous l'éditeur d'analyses. 

Deuxième méthode: Création d'un fichier de données : création du fichier et des rubriques
- Placer vous dans l'onglet Analyse et cliquer sur Nouveau.

- Sélectionnez dans l'assistant l'option "Créer une nouvelle description d'un fichier de données". 

- Passez à l'étape suivante de l'assistant.

- Nous allons créer le fichier "Commande". Saisissez son nom "Commande" dans l'assistant. Ce nom sera utilisé 

- Dans le champ "Un enregistrement représente" saisissez "Une commande"

- Dans la zone "Identifiant automatique", conservez l'option "Identifiant automatique sur 8 octets".

- Passez à l'étape suivante et sélectionnez le type de la base associée au fichier de données HFSQL Classic. 

- Cliquez sur le bouton vert pour valider. Le fichier de données est automatiquement créé dans l'analyse. 
La fenêtre de description des rubriques et des index s'ouvre. 

- Ajouter dans nom la rubrique suivante Nome date: "Date", Libellé: "Date de la commande", Type "Date"
Re-sélectionnez la ligne de la rubrique "Date" pour activer les champs de description présents sur la droite de l'écran. 
Il suffit alors de préciser le type de clé utilisé. Dans notre cas, la date est une clé avec doublons et le tri par 
défaut sera "ascendant". 

- Ajouter dans nom la rubrique suivante Nome date: "Etat", Libellé: "Etat de la commande", Type "Sélecteur, Liste, Combo"

- Dans la partie basse de l'écran, cliquez sur le lien pour afficher les paramètres du champ lié à la rubrique sélectionnée. 
Nous allons saisir les options suivantes dans l'onglet "Contenu" :
Cliquez sur l'onglet "Contenu".
Cliquez sur le bouton "+" pour ajouter la première option.
L'option 1 correspond à En attente. Saisissez "En attente" dans le champ de saisie à droite du sélecteur.
Cliquez sur le bouton "+" pour ajouter la seconde option.
Saisissez "Validée" à la place de "Option 2".
Cliquez à nouveau sur le bouton "+".
Saisissez "Annulée" à la place de "Option 3". 

- Validez la fenêtre de description du champ relié à la rubrique. 

- Ajouter dans nom la rubrique suivante Nome date: "TotalHT", Libellé: "TotalHT", Type "Monétaire"

- Ajouter dans nom la rubrique suivante Nome date: "TotalTTC", Libellé: "TotalTTC", Type "Monétaire"

Troisième méthode: Importation d'un fichier CSV
- Pour créer le fichier "ModeRèglement", contenant les caractéristiques du règlement, nous allons utiliser une autre méthode : 
l'import d'un fichier CSV.

- Sous le volet "Analyse", dans le groupe "Création", déroulez "Importer" et sélectionnez "Importer des descriptions de fichiers/tables".
Sélectionnez le format des fichiers à importer. Ici, sélectionnez "Fichier texte". Passez à l'étape suivante de l'assistant. 
Indiquez le chemin du fichier à importer : "\Autoformation\Exercices\WD Ma Première Base De Données\ModeRèglement.csv" 

- Indiquez les paramètres d'importation suivants :
Enregistrements délimités par : "<Retour chariot/Saut de ligne>"
Colonnes délimitées par : "<Point-virgule>"
Chaînes délimitées par : "<Aucun>"
Séparateur décimal : "<Automatique : point ou virgule>" 

- Cocher l'option "La première ligne contient les noms des colonnes" et validez

- La structure du fichier de données qui va être créé apparaît. Conservez les options par défaut. 
Passez à l'étape suivante. 

- Le contenu du fichier CSV va être automatiquement converti au format HFSQL. L'assistant vous propose de créer 
le fichier HFSQL dans le répertoire du projet. Conservez les options proposées et passez à l'étape suivante. 
Validez l'assistant. WINDEV crée le fichier de données.

////////

Quatrième méthode: Importation directe de fichiers de données existants

- Dans le dossier suivant "\Autoformation\Exercices\WD Ma Première Base De Données" sélectionnez le fichier "Produit.fic"
Faites un copier glisser du fichier dans l'éditeur d'analyse de WinDev

- L'assistant d'importation se lance. Validez les différents écrans. Le fichier de données apparaît sous l'éditeur d'analyses.
A partir de la seul la description du fichier produti à été importé il faut maintenant importe rles données

- Ouvrez directement l'explorateur de fichiers sur le répertoire de votre projet : sous le volet "Accueil", dans le groupe "Général", 
cliquez sur l'icone en forme de dossier
Depuis le dosssier "\Autoformation\Exercices\WD Ma Première Base De Données" copiez via l'explorateur de fichiers, les fichiers "Produit.fic", 
"Produit.mmo" et "Produit.ndx" vers le sous-répertoire EXE du répertoire de votre projet.

## Création des liaisons

- Client et Commande (0,n) et (1,1)

- ModeRèglement et Commande (0,n) et (1,1)

- Produit et Commande


## Génération de l'analyse

- La génération de l'analyse consiste à valider les modifications de l'analyse (création de fichiers de données, ajout ou suppression de rubriques, ...) 
et à les propager dans tout le projet (pages, champs reliés, états, ...).

- Pour générer l'analyse :
Sous l'éditeur d'analyses, sous le volet "Analyse", dans le groupe "Analyse", cliquez sur "Génération".
La génération de l'analyse est automatiquement lancée.


## RAD (Rapid Application Development)

- Pour lancer la génération du RAD :
Sous le volet "Projet", dans le groupe "Génération", cliquez sur "RAD Application complète". L'assistant de génération de l'application RAD se lance. 

- Sélectionnez "RAD Simple".

- Indiquez si le groupware utilisateur doit être utilisé dans l'application. "Non"

- Indiquez si le menu automatique doit être intégré à l'application. "Oui"

- Conservez l'option "Aide des FAA (Fonctionnalités Automatiques de l'Application)".


## Test de l'application

- Pour lancer le test de l'application :
Cliquez sur GO parmi les boutons d'accès rapide. L'application se lance.


# Consommer un Webservice

- Dans la page d'accueil, cliquez sur "Cours d'auto-formation" et sélectionnez le projet "Application complète (Exercice)".

- Dans l'onglet projet cliquer sur Importer et dans le menu déroulant sélectionner un Webservice

- Indiquez l'adresse à laquelle la description WSDL du Webservice doit être importée : 
https://exemples.webdev.info/WSAUTOFORMATIONV2_WEB/awws/WSAutoformationV2.awws?wsdl
(Ce Webservice permet d'interroger une base fournisseur pour vérifier la disponibilité (stock) d'un produit à partir de sa référence.)

- Validez la fenêtre d'information. Le Webservice importé est présent dans le dossier "Webservices importés" de l'explorateur de projet.
Dans l'explorateur de projet, déroulez le dossier "Webservices importés".

- La structure est constituée de :
le nom du Webservice (WSAutoformationV2 dans cet exemple),
le nom de chaque fonction (ProduitEnStock dans cet exemple)

- Pour utiliser le Webservice :
Ouvrez sous l'éditeur la fenêtre "FEN_Menu" (double-cliquez sur son nom dans l'explorateur de projet par exemple).
Dans le volet "Liste des produits", ajoutez un bouton :
Sous le volet "Création", dans le groupe "Champs usuels", cliquez sur .
Cliquez dans la fenêtre sous le bouton "Modifier".
Le bouton est automatiquement créé.
Modifiez les caractéristiques du bouton (option "Description" du menu contextuel). Ce champ a pour nom "BTN_EnStock" et pour libellé "En stock ?". 
Affichez les traitements associés au bouton (option "Code" du menu contextuel). 
Dans le traitement "Clic sur BTN_EnStock" saisissez le code suivant :

```
// Affiche la réponse du Webservice
InfoConstruit("Nombre de produits ""%1"" en stock : %2", COL_Référence, ProduitEnStock(COL_Référence))

```
  
- Examinons ce code:
La fonction du Webservice ProduitEnStock est appelée. Ce code utilise le prototype de la fonction que nous avons précédemment affiché dans l'éditeur de code. 
La réponse est mise en forme et affichée.
Fermez l'éditeur de code et enregistrez la fenêtre ( ou Ctrl + S).

Executer le projet sur GO


# Evénement Windows

Ouvrez l'exemple unitaire "La fonction Evénement".

Pour ajouter un traitement optionnel :
Affichez les traitements liés au champ Liste présent dans la fenêtre de l'exemple unitaire :
Sélectionnez le champ Liste.
Appuyez sur la touche F2.
L'éditeur de code est affiché.
Cliquez sur le lien "Ajouter d'autres traitements ...": 

La liste complète des traitements optionnels disponibles s'affiche:
Pour ajouter un traitement, il suffit de cocher la case correspondante et de valider cette fenêtre. 
Par exemple, ajoutez l'événement "Touche Enfoncée". 

# Les threads

# Le FTP

- Ouvrez l'exemple unitaire "Les fonctions FTP"

Pour se connecter:
Host: ftp.vertin-go.com
Pseudo: vertin-go.com


# POO 

Cliquer sur Ouvrir -> Ouvrir un exemple 
Recherche POO et ouvrir WD POO Simple

## Déclarer une classe

- Dans l'explorateur de projet, sélectionnez le dossier "Classes".
Affichez le menu contextuel de ce dossier (clic droit de la souris) et sélectionnez l'option "Créer une classe vierge".
Dans la fenêtre qui s'affiche, indiquez le nom de la classe (par exemple TestGAF) et validez.

- Dans l'explorateur de projet, sélectionnez le dossier "Classes".
Ouvrez le dossier "Classes" (en cliquant sur la flèche présente devant le nom du dossier).
Double-cliquez sur la classe cSavane.
Le code de la classe s'affiche sous l'éditeur de code. Le code de déclaration de la classe est de la forme:

## Ajout de méthode

- Cliquez avec le bouton droit de la souris sur votre classe présente dans l'explorateur de projet.
Choisissez "Nouvelle méthode" dans le menu contextuel.
Dans la fenêtre qui s'affiche, indiquez le nom de la méthode et validez.
Saisissez le code de la méthode sous l'éditeur de code.


## Génération de Diagramme UML

- Pour afficher le diagramme UML lié au projet :
Double-cliquez sur "ModèleUML" dans l'explorateur de projet : 

- Pour créer un diagramme UML :
Sous le volet "Accueil", dans le groupe "Général", cliquez sur "Nouveau".
La fenêtre de création d'un nouvel élément s'affiche : cliquez sur "Architecture" puis sur "UML".
L'assistant de création d'un modèle UML se lance, vous permettant de choisir le modèle à créer : 



A little boost is always welcome:

==> https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1
==> https://www.facebook.com/vertingo/


# Statistique : champs Graphe et Tableau Croisé Dynamique

- Dans la page d'accueil de WINDEV (Ctrl + <), cliquez sur "Cours d'auto-formation", puis sélectionnez "Application complète (Corrigé)"

- Cliquez sur nouveau parmi les boutons d'accès rapide.
La fenêtre de création d'un nouvel élément s'affiche : cliquez sur "Requête".
Nous allons réaliser une requête de sélection. Sélectionnez l'option "Sélection (SELECT)". Passez à l'étape suivante.
La fenêtre de description de la requête apparaît.

- Ajoutez les rubriques Commande.Date et Commande.TotalTTC à la requête :
Sur la gauche, déroulez le fichier "Commande".
Double-cliquez sur la rubrique Date puis sur la rubrique TotalTTC.
Les deux rubriques apparaissent au centre de l'écran (dans la zone "Liste des éléments de votre requête").
Pour effectuer la somme des valeurs de "Commande.TotalTTC" :
Sélectionnez la rubrique "Commande.TotalTTC" au centre.
Dans les "Actions", sur la droite, cliquez sur "Somme". 

# Déployer l'application

- Dans la page d'accueil de WINDEV (Ctrl + <), cliquez sur "Cours d'auto-formation", puis sélectionnez "Application complète (Corrigé)"

# GDS

- Ouvrir le projet Application complète (Corrigé)

- Sous le volet "GDS", dans le groupe "Ajouter le projet", cliquez sur "Ajouter le projet dans le GDS". 
L'assistant d'ajout d'un projet dans le GDS se lance : 
Sélectionnez l'option "Création d'une base en mode partage réseau" et indiquez le répertoire de cette
 base de sources ("C:\Mes Projets\GDS Base de sources locale" par exemple).

# Administrer une base HFSQL Client/Serveur

## Création d'un projet HFSQL Client/Serveur

- Créer le projet en demandant à créer une nouvelle base de données.
Créer l'analyse en spécifiant que les bases de données utilisées par le projet seront de type "HFSQL Client/Serveur".
Indiquer les caractéristiques de la connexion au serveur HFSQL Client/Serveur à utiliser.
Lors de la création d'un fichier sous l'analyse, indiquer que ce fichier est en mode Client/Serveur et préciser la connexion utilisée.

## Adaptation d'une application pour utiliser une base de données HFSQL Client/Serveur

- Ouvrez si nécessaire le projet "WD Application Complète". 
Dans l'explorateur de projet, sélectionnez si nécessaire, la configuration de projet "Exécutable Windows 32 bits". 
Chargez l'analyse de votre projet sous l'éditeur d'analyses : cliquez sur  parmi les boutons d'accès rapide. L'éditeur d'analyses s'affiche.
Sous le volet "Analyse", dans le groupe "Connexion", cliquez sur "Nouvelle connexion". Un assistant s'ouvre, permettant de créer une connexion.
Sélectionnez le type de connexion à créer : "HFSQL Client/Serveur". 
Passez à l'étape suivante. 
Indiquez dans les étapes suivantes : 
Saisissez le nom de la connexion (conservez le nom proposé).
Passez à l'étape suivante et validez. La connexion à la base est automatiquement créée. 
L'assistant propose d'associer les différents fichiers de données présents dans l'analyse à la connexion qui vient d'être créée. 
Cliquez sur "Oui".
Dans l'étape suivante, sélectionnez tous les fichiers proposés : 
Passez à l'étape suivante. 
L'assistant propose ensuite de copier les fichiers de données sur le serveur. Validez (option "Copier maintenant"). 
Sélectionnez les fichiers de données de l'analyse à copier sur le serveur : dans notre cas, ce sont tous les fichiers de données du répertoire EXE. 
Passez à l'étape suivante et validez.
Les fichiers de données de l'analyse sont automatiquement transformés en fichiers de données HFSQL Client/Serveur et associés à la connexion choisie. 
Générez l'analyse : sous le volet "Analyse", dans le groupe "Analyse", cliquez sur "Génération". Une modification automatique des fichiers de données est automatiquement effectuée. 
Si tous les fichiers de données sont à jour, vous pouvez annuler la modification automatique des fichiers de données.
Vous avez adapté le projet de développement. Il peut être également nécessaire d'adapter l'application déployée (par exemple si l'application déployée utilise des fichiers HFSQL Classic). 
Cette opération se paramètre lors de la création du programme d'installation de l'application.

# Utiliser des données SQL

A little boost is always welcome:

==> https://www.youtube.com/channel/UC2g_-ipVjit6ZlACPWG4JvA?sub_confirmation=1
==> https://www.facebook.com/vertingo/


