## Déploiement avec Vercel

4- vercel --version

5- ng new DeploiementAvecAngular

6- vercel

7- vercel list

8- vercel logs deploiement-avec-angular-g1dxh84gc.vercel.app

9- vercel inspect deploiement-avec-angular-g1dxh84gc.vercel.app
Cette commande sert à récupérer des informations sur un déploiement en faisant un état des lieux des fichiers présents dans le déploiement

10- Les variables d'environnement servent à être appelées partout dans un environnement et surtout pendant les étapes de compilation et d'exécution du code du projet.

11- vercel env add plain VAR1 production

12- vercel env list

13- Les secrets sont des variables d'environnements chiffrées utilisées dans l'environnement de production

14- vercel secrets add SECRET1 "Some secret"

15- Les trois environnements :
- Développement
- Preview
- Production
Il y a plusieurs versions non seulement pour permettre plus d'organisations mais surtout pour permettre de bien vérifier les changements avant de le mettre à disposition du public

18- https://test-git-vercel.vercel.app/

19- Un pull request permet de demander à d'autres développeurs de vérifier le code avant de l'ajouter dans une branche principale

20- Vercel essaie de déployer automatiquement le pull request sur l'environnement de preview

21- 	- Git associe mon environnement de production à la branche (pull request) nouvellement mergée
- Le pull request est pris en compte directement dans l'environnement de production dès qu'il est mergé.
- Le workflow d'une feature de son développement à sa production (Simplement) :
- Développement (Environnement de Développement)
- Pull request (Environnement de Preview)
- Merge (Environnement de Production)

22- Serverless veut dire que l'application front-end utilise des directives d'un langage ou un framework de backend pour comprendre les requêtes HTTP et donner des réponses.
C'est pratique de faire ainsi car on peut simuler les langages ou frameworks de backend sans pour autant passer par une api.
