# Movie - db - user

Projet rails léger pour reviser les notions des deux premieres semaines de rails.

Nous allons creer un site qui permettra de lister nos films preferes.

La liste sera visible de tous, comme page d'accueil de notre site, mais il sera necessaire de se connecter pour ajouter/supprimer des films de la liste.

## 1 - Installation

Commencer un projet rails et le mettre en ligne sur Heroku.

## 2 - Movies database

Creer un model `Movie` qui aura un `title`, un `director` et une `release_year`.

> Il est possible de faire cette etape en une seule ligne avec la commande `generate`.

Seeder cette liste avec au moins 3 films.

La page index doit nous permettre de voir ces films et de les supprimer en un clic. 

En dessous de la liste, un formulaire nous permet de rajouter un film.

## 3 - Users

Creer un model user qui aura un `username` et un mot de passe sécurisé.

Le header de notre page comporte maintenant un bouton `login`. 

Un visiteur ne pourra pas éditer la liste, seulement la voir.

À la place du formulaire d'ajout de film, le visiteur voit un lien qui l'invite à creer un compte ou à se connecter pour ajouter ou supprimer un film.

## 4 - Bonus

La liste permet de voir quel utilisateur a ajoué quel film.

Chaque utilisateur peut voter pour un film (type reddit, + ou -).

Les films sont affichés en fonction de leur note (du plus plebiscité au plus detesté).