**CONCEPTION D'UN MINI-SITE DE PRESENTATION POUR UNE ENTREPRISE**

Dans le cadre de l’examen de la Session Normale, nous avons réalisé un projet, qui est la conception d’un mini-site de présentaion d’entreprise en utilisant les langages HTML/CSS, JS ainsi que l’outil GIT pour l’intégration de chaque partie.
Etapes Suivies
Voici ci-dessous les différentes éapes suivies pour la realisation de ce projet accompagné des captures d’érans de chaque commande.
**1.	Création et initialisation du répositoire en ligne**
Le depot a été créé en faisant tout d’abord un cd vers le dossier du projet, et ensuite un git init suivi d’un git remote add origin <url du depot>.Un fichier README.md a été créé avec la commande touch README.md puis nous avons fait la commande git add . suivi d’un git commit –m  ‘‘Ajout du README ’’ et d’un git push –u origin main

**2.	Création de la structure HTML**
Tout d’abord, une branche feature/html-structure a été créée pour la conception de la partie HTML du mini-site en utilisant la commande git checkout –b feature/html-structure. La commande touch index.html a été utilisée pour créer le fichier. Git add . et git commit –m “Ajout du fichier index.html” sont les commandes utilisées pour active le suivi sur le fichier index.html. La commande git push origin feature/html-structure pour pousser la brancher vers le depot.

**3.	Création de la charte graphique CSS**
Tout d’abord, une branche feature/css-theme a été créée pour la conception du style css du mini-site en utilisant la commande git checkout –b feature/css-theme. La commande touch style.css a été utilisée pour créer le fichier. Git add . et git commit –m “Ajout du fichier style.css” sont les commandes utilisées pour active le suivi sur le fichier style.css. La commande git push origin feature/css-theme pour pousser la brancher vers le depot.
 
**4.	Conception des interactions Javascript**
Tout d’abord, une branche feature/js-interactions a été créée pour la conception de la partie HTML du mini-site en utilisant la commande git checkout –b feature/js-interactions. La commande touch script.js a été utilisée pour créer le fichier. Git add . et git commit –m “Ajout du fichier script.js” sont les commandes utilisées pour active le suivi sur le fichier index.html. La commande git push origin feature/js-interactions pour pousser la brancher vers le depot.
 
**5.	Réalisation de tests intermédiaires**
La branche pour les tests, test/frontend a été crée en utilisant la commande  git checkout –b test/frontend. Un test d’intégration réalisé, et la fusion des fichiers avec les commandes git pull  et git merge pour chaque test feature/* ainsi que le git push pour pousse la branche comme illustrer ci-dessous

**6.	Intération Globale dans dev**
La branche dev a été créée avec la commande  git checkout –b dev. L’intégration globale a été réalisée, ensuite la fusion des fichiers avec les commandes git pull  et git merge pour la branche test/frontend ainsi que le git push pour pousse la branche comme illustrer ci-dessous
 
**7.	Finalisation du Projet**
On a accédé à la branche main avec la commande  git checkout main. L’intégration globale a été réalisée, ensuite la fusion des fichiers avec les commandes git pull  et git merge pour la branche dev ainsi que le git push pour pousser la branche vers le depot comme illustrer ci-dessous
 

