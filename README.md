## Recrutement stagiaire

Afin de départager les candidats au stage, un exercice est à effectuer.

Le candidat avec la meilleur note sera le stagiaire. Le départage se fait suivant
les critères suivants :

- Respect des consignes fournies
- Qualité du code

### Consignes

A l'aide du langage PHP v7.3, du JavaScript, de la librairie jQuery v3.4, 
de Bootstrap v4 et de la bibliothèque d'icônes FontAwesome v4.7 effectuez les
fonctionnalités suivantes :

*Un fichier docker-compose.yml est à votre disposition pour lancer un serveur Apache.
La commande `docker-compose up -d` devrai suffire. Attention à mettre à jour la ligne
9 de ce fichier dans le cas où vous utilisez Docker Toolbox sur Windows (./src doit être remplacé par le chemin absolu
du dossier src).*

*Dans le script database/articles.php se trouve un tableau d'articles. Pour chaque article il existe
un titre (title), une date de création (created_at), un résumé (abstract) et un contenu (content).*

*Pour enregistrer les données, la variable de session est autorisée (les bases de données n'ayant pas encore
été abordées en cours)*

1. Afficher la liste des articles dans index.php
2. L'utilisateur doit pouvoir se rendre sur la page de l'article afin de le lire
3. Dans la liste des articles et sur la page d'un article, afficher à l'utilisateur s'il a déjà vu ou non l'article
4. Permettre à un utilisateur d'ajouter un commentaire à un article et afficher les commentaires