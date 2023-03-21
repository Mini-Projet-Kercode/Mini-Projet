# Mini-Projet
Mino projet kercode

KARL/MAITE/MELISSA/NICOLAS

      Nous partirons des travaux proposés par Ulrich M. dans son cours MVC qui traite de l'architecture MVC avec l'objet. Les ressources sont (re)données ci-dessous.

      Le projet initial propose un backend pour la lecture et la modification des profils d'utilisateurs enregistrés dans une base de données.

Nous allons faire évoluer ce projet pour qu'il permette :

    à un utilisateur de s'enregistrer
    à un utilisateur enregistré de se connecter / de se déconnecter
    à un utilisateur authentifié de créer ou de modifier son profil
    à un utilisateur authentifié de supprimer son compte
    
   -------------------------------------------------------------------------------------------------------------------------------------------------------------

- Vos missions :

   1. reprendre le modèle de la base de données afin qu'il autorise une séparation fonctionnelle entre création de compte et remplissage du profil. 
      De cette manière,i l n'y aura pas d'obligation à renseigner son profil en même temps que la création de son compte (c'est plus confortable d'un point de vue UX)
   2. adapter le (ou les) modèle(s) en essayant de garder la connection sur la base de données ouverte sur la durée du script (cycle de vie de l'objet PDO)
   3. faire une petite arborescence des pages
   4. déduire de l'arborescence les routes et les vues puis les implémenter
   5. assembler et tester


- L'ensemble du travail devra être réalisé :

    . en appliquant les règles et les mécanismes de sécurité,
    . en utilisant le package dotenv pour la configuration (ou une méthode équivalente)
    . en utilisant les namespaces
    . en activant un mécanisme d'autoload (celui de Composer est tout indiqué)
    . en proposant une belle structuration des fichiers sur le serveur


 * Dans cet exercice, la priorité n'est pas de proposer un look d'enfer du côté du front. Ne pas perdre de temps la dessus *
 
 
 -------------------------------------------------------------------------------------------------------------------------------------------------------------

 MODIFIER LE FICHIER DB_SETUP.PHP (supprimer les lignes  13-27 / 40-56)
 SUPPRIMER LE FICHIER USER.PHP
 -------------------------------------------------------------------------------------------------------------------------------------------------------------
 
 Reprendre le modèle de la base de données afin qu'il autorise une séparation fonctionnelle entre création de compte et remplissage du profil : 
 
 1er tâche - BASE DE BONNEE / 1 personne 

  - schema MCD 
  - schema MLD 
  - Contraintes d'intégrité
  - Crée le schéma sur un logiciel adapté
  - exporter/importer vers PHPMYADMIN sur la basse de donnée 
  - Vérification groupé des TABLE / KEY
  
  
2em Tâche - ADAPTER LE (OU LES) MODELE(S) / 4 personne 
  
   * repérer les modification à effectuer pour la connection à la DB / les modification à effectuer*
  
   * Phase Modification - 
  
   * Phase Création -
  
  
3em Tâche ARBORESCENCE PAGE/VUE
 
 
 
 -------------------------------------------------------------------------------------------------------------------------------------------------------------
