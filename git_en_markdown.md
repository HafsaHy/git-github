## *Github*
## 1 Présentation
### 1.1 GitHub
*Plateforme colleborative* pour dev, plus grand espac de stockage de travaux collaborative dasn le monde !  GitHib en lui-même n'est plus qu'un reseau social comme FB. Vous construisez un profil, vous y deposez des projets à partager et vous vous connectez avec d'autre utilisateurss en suivent leurs comptes . Même si la plupart des utilisateurs y deposant des projects de programme ou de code, rien ne vous empeche d'y placer des textes ou tout type de fichier à présenter dasn vos repretoire de projets.

### 1.2 Git

Git est un *logiciel de controle de version*, ce qui signifie qu'il gere les modifications d'un projet sans écraser n'importe qu'elle partie du projet.

## Git et GitHub

### 2.1 Vocabulaire

**ligne de commande**: En gros: le programme de l'ordinateur que nous utilisons pour entrer des commandes Git. Dans le monde UNIX, on dit qu'on travaille en en "ligne de commande" pour désigner le fait d'interagir avec un système  informatique en entrant des lignes d'instructions textuelles dans un terminal, et non a l'aide d'une interface Journal du net <https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1445276-commande-informatique-definition-precise-et-exmples/>

**Depot**: Un repertoire ou de l'espace de stockage ou vos projets peuvent vivre; els utilisateurs de GitHub raccourcissent en "repo" pour 'repesotory". Il peut etre un espace de stockage sur GitHub ou un autre hebergeur en ligne. A l'interieur d'un depot, vous pouvez conserver des fichiers de codes , des fichiers txt des images.

**controle de version**: Fondamentalement, l'objectif pour lequel Git a ete connu, quand vous avez un fichier Word =, vous l'écravez à chque fois que vous sauvegardez plusieurs versions. Avec Git, vous n'st plus oblige de faire ca. Git conserve des "instantanes" de de chaque point dans l'historique d'un projet, de sorte que vous ne pouvez jamais le perdre ou l'écraser.

**Commit**: C'est la commande qui donne à git toute puissance. Quand vous committez, vous prenez un instantané, une photo de votre depot à ce stade vous donnant point de controle que vous pouvez ensiote réévaluer ou tout simplement restaurer votre projet à cette version. Il est nécéssairede rappeler que le nom de vos commits doivent-être parlant afin de savoir à quel stade du projet celui-ci a été fait.

**Branche**: Comment plusieurs personnes travaillant sur un projet en même temps sans que Git ne s'embrouille? Habituellement, elle se debranchent du projet principal avec leur propres version complètes, des modification qu'elles on chacune produites de leur cote. Aprés avoir terminer, il est temps de fusionner cette branche pour la ramener vers la branche master, le repertoire principal du projet;

### 2.2 Commandes specifiques Git
**git init**: initialise un nouveau depot git jusqu'a ce que vous executer les commandes Git qui suivant.
**git config**:Raccourci de configuration, ceci est tout particulierement utile quand vous parametrez Git pour la premie fois identifiant  et mail d'utilisateur.

**git help**: oublie un commande , pour afficher les 21commmande de git ;

**git status**:verifie le status de votre repo. Voir les fichiers et quelle sont kes modifications à commiter et sur quelle branch ou repo vous etes en train de travailler.
**git add**:Ceci n'ajoute pas des fichiers dans votre repo, au lieu de cela, cela porte de nouveaux à l'attestation de Git. Apres avoir ajoute des fichiers, ils sont inclus dans les instantanes  du depot Git.
**git commit**: la commande la plusimportante de Git. Ares avoir effectue toute sorte de modifications vous entrez ca afin de prendre un instantanesz du depot. le mettre en memoire. on ecrit ca sous la forme de git commit -m 'votre message'. le -m indique que la section suivante de la commande devrait etre lu comme un message.

**git branche**: vous travaillez avec plusieurs collaborateurs et vous voulez produire des modifications de votre cote?  cette commande  vous permet de construire une nouvelle branche, ou une chronologie de commits, des modifications et des ajouts de fichiers qui sont completement les votres . Votre titre va apres la commande.Si vous vouliez creer une nouvelle branche appellee 'hafsa' vous saisiriez git branch hafsa pour regarder une autre branche.

**git merge**: lorsque vous avez fini de travailler sur une branche, vous pouvez fusionner vos modifications vers la  branche master, qui est visible pour tous les collaborateurs . get merge hafsa prendrait toutes les modifications que vous avez apportées à la branche hafsa et les ajouter a la branche master.
**git bush**: Si vous travaillez sue votre ordinateur en local et vous voulez que vos commits soient visibles aussi en ligne sur GitHub, vous pushez 