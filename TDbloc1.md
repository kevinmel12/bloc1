**1. Différences entre les méthodes http GET et POST**

* Une méthode http GET permet d'accéder à une ressources précise. * 
* Cependant la méthode Post permet d'envoyer des données qui est généralement indiqué par le titre *Content-Type* . *


**2. Utilisez les exemples précédents pour effectuer un comparatif (tableau avec critères) entre ces 2
méthodes**

|GET|POST|
|---|----|
|Demander des données au serveur, (qu'on peut apprecevoir danss l'URL en tant que paramètre de requête)|La méthode POST permet d'envoyer les données au serveur|
|GET est moins sécurisé que POST car comme dis juste avant les données sont visibles dans l'URL|La méthode POST permet d'envoyer les données au serveur.|
|En général, les requêtes GET sont considérées comme idempotentes, ce qui signifie que l'exécution multiple de la même requête n'a pas d'effet différent.|Les requêtes POST ne sont pas nécessairement idempotentes, car elles peuvent entraîner des modifications de l'état du serveur à chaque exécution.|


**3. Expliquez précisément en quoi le protocole http est extensible. **
