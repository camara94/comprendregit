# Comprendre git et github

## Les commandes de bases de git et github
1. **git init:** pour unitialiser un repository
2. **git status:** pour voir l'état de repository
3. **git add . ou git add ./fichier ou git add ./dossier:** pour enregister une modification 
4. **git commit -m "message de commit":** pour ajouter une modification à un repository une branche
5. **git branch: ** pour afficher les branches du repository
6. **git branch nomBranch:** pour créer la branche
7. **git checkout -b nombranch:** pour créer une branche, si elle n'existe pas 
	sinon changer de branche
8. **git checkout commitnumber index.html:** pour aller à un commit 
9. **git reset commitnumber index.html:** pour annuler l'action précedente

## Pour un repository local à un repository en ligne 
	Il faut tout d'abord créer un repository en ligne qui a le même nom que celui en local ensuite on copie url du repository en ligne et puis:
* À l'invite, saisissez ce qui suit pour configurer votre 
      référentiel local pour établir un lien avec votre référentiel 
      Git en ligne: <br><code>git remote add origin repositoryURL</code> 
*  ensuite pour pousser vos commits vers le référentiel en ligne
     <code>git push -u origin master</code>

## Clonage d'un référentiel en ligne
*   <code>git clone repository URL</code>

> Je n'ai pas encore fait mon nouveau commit, 
> mais je veux annuler tous les changements 
> que je n'ai pas encore commités. Possible ?

* Possible avec un reset
<code> git reset --hard‌</code