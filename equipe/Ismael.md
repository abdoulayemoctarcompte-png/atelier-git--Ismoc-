# Mohamed Ismael Sanogo

- Pseudo GitHub : @Sanogo2429
- Ce que je connais déjà de Git : La différence entre un dépôt distant (Github le site web de git) et local (cdespaces), le principes des copies indépendantes et la nécessité de push et pull pour synchroniser. 
- Ce que j'attends de cet atelier : apprendre à traviller en équipe et gérer les confilts de fusion.
## Quiz

1. Juste après `git commit`, où se trouve mon commit ?
Il se trouve en local, dans l'historique de ton dépôt Git local (dans ton Codespace), pointé par ta branche active et ton HEAD. Il est enregistré sur ta machine/ton conteneur, mais il n'est pas encore partagé sur GitHub.
2. Juste après `git push`, où se trouve-t-il ?
Il se trouve à la fois en local ET sur le dépôt distant (sur GitHub, par exemple sur origin/master). Il est stocké sur les serveurs de GitHub, ce qui permet à ton équipe (comme Moctar) de le récupérer.
3. Que se passe-t-il si je supprime mon Codespace après un commit mais sans push ?
Le commit est perdu définitivement. Un Codespace est un environnement de développement cloud éphémère : tout ce qui n'a pas été envoyé (pushed) sur un dépôt distant GitHub est supprimé en même temps que le conteneur. C'est la règle d'or à retenir : un commit sécurise ton travail en local, mais seul un push le met à l'abri dans le cloud !
