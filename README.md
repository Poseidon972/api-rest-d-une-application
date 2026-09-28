Rapport – API REST de gestion des étudiants
1. Présentation du projet
Dans le cadre de ce projet, nous avons développé une API REST permettant de gérer une liste d'étudiants.

L'objectif de cette API est de permettre à une application cliente d'accéder aux informations des étudiants et de les gérer à travers différentes requêtes HTTP.

Pour réaliser ce projet, nous avons utilisé :

Visual Studio Code pour développer l'API ;

Python pour programmer les différentes fonctionnalités ;

XAMPP pour faire fonctionner le serveur local et la base de données ;

PHPMyAdmin pour gérer la base de données MySQL ;

Postman pour tester les différentes routes de l'API.

L'API permet de réaliser les opérations suivantes :

récupérer la liste de tous les étudiants ;

récupérer un étudiant à partir de son ID ;

créer un nouvel étudiant ;

modifier un étudiant ;

supprimer un étudiant.

2. Diagramme de cas d'utilisation
L'utilisateur ou l'application cliente communique avec l'API REST afin de gérer les étudiants.





3. Les 4 versions de l'API
Le projet comporte 4 versions de l'API. Ces versions permettent de faire évoluer progressivement le projet et d'ajouter ou d'améliorer les fonctionnalités.

Version	Fonctionnalités
V1	Première version de l'API et accès aux étudiants.
V2	Ajout de fonctionnalités permettant de gérer les étudiants.
V3	Amélioration des opérations de modification et de récupération.
V4	Version finale regroupant les fonctionnalités de gestion des étudiants.

Les principales méthodes HTTP utilisées sont :

GET : récupérer des étudiants ;

POST : créer un étudiant ;

PUT/PATCH : modifier un étudiant ;

DELETE : supprimer un étudiant.

4. Base de données et classe Database
Les informations concernant les étudiants sont stockées dans une base de données MySQL. La base a été créée et administrée avec PHPMyAdmin, tandis que XAMPP permet de faire fonctionner MySQL en local.

Le projet contient également une classe Database permettant à l'API de communiquer avec la base de données.


<img width="181" height="338" alt="image" src="https://github.com/user-attachments/assets/02950cae-0092-4527-bca3-1aecd5e66c4f" />

Le diagramme permet de représenter la classe Database ainsi que ses attributs et méthodes.

5. Tests avec Postman
On a utilisé Postman pour vérifier le fonctionnement de l'API. Plusieurs requêtes ont été envoyées afin de tester toutes les fonctionnalités.

<img width="463" height="202" alt="image" src="https://github.com/user-attachments/assets/7fc6d170-073d-48ee-a0e2-a0340900f4b3" />

6. Conclusion et sécurité
Ce projet nous a permis de mettre en pratique le fonctionnement d'une API REST et de comprendre comment une application peut communiquer avec une base de données.

L'API réalisée permet de gérer les étudiants de manière simple grâce aux différentes opérations de consultation, création, modification et suppression.

Pour améliorer la cybersécurité de l'API, plusieurs solutions pourraient être mises en place : ajouter une authentification des utilisateurs, contrôler les données reçues, utiliser des requêtes préparées pour éviter les injections SQL, protéger les informations sensibles et utiliser HTTPS pour sécuriser les communications.

Ce projet nous a donc permis de travailler sur plusieurs aspects du développement web : API REST, Python, base de données MySQL, requêtes HTTP et tests avec Postman.
