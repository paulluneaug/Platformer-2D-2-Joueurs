# Platformer-2D-2-Joueurs
Platformer 2D 2 Joueurs fait sur Python avec un ami, Luc40444, dans le cadre d'un projet scolaire

Contrôles :
Joueur 1 : Les flèches directionnelles pour se déplacer, ! pour faire un dash et n pour réapparaître au dernier checkpoint

Joueur 2 : ZQSD pour se déplacer, a pour faire un dash et r pour réapparaître au dernier checkpoint

Le but du jeu est de terminer tous les niveaux. Dans chaque tableau, le but est d'arriver au portail orange en partant du portail bleu.

Au fil des tableaux, le personnage peut rencontrer de nombreux blocs différents:
-Des blocs tuant le personnage et le ramenant au dernier checkpoint

-Des blocs que le joueur ne peut pas passer dans un certain sens. Si le personnage se retrouve bloqué, il est possible d'appuyer sur R pour revenir au dernier checkpoint en perdant une vie

-Des blocs pour le faire sauter plus ou moins haut

-Des blocs pour le faire aller plus ou moins vite

-Des portes arrêtant le personnage, qu'il peut ouvrir en passant sur une clef de la même couleur

-Des blocs que le personnage peut casser en sautant et d'autres, chronométrés, qui passent d'un état où le personnage peut passer à travers et un autre dans lequel il ne peut pas, toutes les 60 images affichées par le jeu

-D'autres alternant aussi entre deux états mais pas selon le temps mais à chaque fois qu'un interrupteur est activé. Ils fonctionnent par deux, rouges et bleus. Quand l'un est activé, l'autre ne l'est pas.

-Nous avons également implémenté des lasers, qui tuent le personnage s'il est en contact avec. Ils sont émis par des émetteurs, peuvent être changés de direction avec des miroirs.

-Ces miroirs ont des couleurs, comme les portes et clefs et peuvent être tournés avec des boutons de la même couleur.

-Finalement, des récepteurs laser, pouvant, si un laser rentre en contact avec, activer un bouton, un interrupteur ou faire tourner un miroir particulier.


Le jeu a été créé en parallèle avec un éditeur de niveau,
Cet éditeur a été utilisé pour développer le jeu et il contient donc tous les blocs possibles, vous pouvez donc vous même créer des niveaux en utilisant les blocs. Vous pouvez utiliser de la molette pour changer la couleur de certains blocs ou leur forme (direction miroir par exemple). N'oubliez pas aussi la liste de changements possible grâce au boutons et  autres entrées à droite des blocs (pour le channel d’un bouton par exemple). Bonne création !

Une fois le niveau créé et nommé, il faut mettre son nom dans le dictionnaire au début du fichier "Platformer2Joueurs.py", dans la liste correspondant à la difficulté ressentie.




