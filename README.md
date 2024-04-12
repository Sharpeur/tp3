**Nom :** Freret Alexandre

**Groupe :** B1

**Année :** 1ere

**IUT Le Havre - Cours GIT**



### Compte-rendu TP3 Introduction GIT


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
  **Nous allons voir dans ce tp comment travailler à plusieur via un repertoire github**
  -----------------------------------------------------------------------------------------

Êtes-vous déjà constitué en équipe ? Lancez une pièce et décidez qui assumera le rôle de Athos et qui assumera le rôle de **Porthos** pour ce travail pratique. Si vous êtes trois, deux personnes seront regroupées dans le rôle **d’Athos**.

  Dans un premier temps nous nous sommes mis d'accord sur qui allait jouer athos et porthos 

 **1. Inviter des collaborateurs dans un dépôt personnel**
 --------------------------------------------------------

 Pour commencer Athos a créé un repertoire ou il a ébergé porthos et nous avons fait ***"Invite a collaborator"*** 


**2. Développement d’un projet java en équipe**
-----------------------------------------------

Athos :

   Copiez les fichiers suivants dans le répertoire tp3/src, validez-les dans le dépôt local et distant :
   
   ***CryptoMarche.java***
        
   ***Portefeuille.java***
       
   ***TestCryptoMarche.java***
        
Porthos :

   Assurez-vous d’obtenir la dernière version du dépôt distant.


   une fois cela fait les deux font les morceaux de peogramme qu'ils manquent et une fois cela fini ils envoient leur travail modifier sur git 

   Nous partons de ça :

       Test Portefeuille transfertDevise        ... FAIL
       Test Portefeuille achatDevise            ... FAIL
       Test CryptoMarche capitalEnEuros         ... FAIL
       Test CryptoMarche capitalMonneaie        ... FAIL

  Et nous voulons obtenir ceci : 

       Test Portefeuille transfertDevise        ... TRUE
       Test Portefeuille achatDevise            ... TRUE
       Test CryptoMarche capitalEnEuros         ... TRUE
       Test CryptoMarche capitalMonneaie        ... TRUE

  

À l’aide de git log, nous pouvons également voir toutes les modifications que nous avons apportées jusqu’à présent. Passons certains paramètres à la commande pour la rendre plus lisible.


git log --graph --oneline --all --decorate --topo-order


Nous avons créé une nouvelle branche nommé test 

git checkout -b test
Switched to a new branch 'test'

 

 
