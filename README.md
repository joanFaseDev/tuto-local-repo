# Tutorial Git & Github

## Commandes Git pour initialiser un dépôt local, le lier à un dépôt distant puis mettre à jour ce dernier

_git init_ -> Crée un dépôt Git vide ou réinitialise un dépôt existant.

_git add._ -> Mettre à jour le contenu de l'index du dépôt local en vue du prochain _git commit_

_git commit_ -> Enregistre les modifications dans le dépôt

- Avant de passer à la suite, créer un dépôt distant (e.g sur le site de GitHub) puis récupérer l'adresse &sol; la clé SSH afin de pouvoir référencer le dépôt.

_git remote add origin *URL*_ -> Ajoute au dépôt local une référence vers un dépôt distant.

_git push -u origin master_ -> Mets à jour le dépôt distant par rapport au dépôt local et fournit une référence pour pouvoir utiliser le raccourci _git push_ lors des prochaines mises à jour.
