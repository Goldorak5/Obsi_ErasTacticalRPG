## Définition 

Le nombre de tour est relatif au nombre de personnage jouable et d'ennemis dans le combat. Leur ordre est défini par son initiative.
## Initiative

L'initiative est le résultat du nombre de point de mouvement et la dextérité des personnages jouables et des ennemies. 

*Exemple:* Paolo a 4 points de mouvement et 2 Dextérité. 

Donc: 

4 + 2 = 6.   

Paolo a donc 6 d'initiative. 

## Résultat Identique 

Si plusieurs personnages jouables ou ennemis ont la même initiative, les personnages joueurs joueront toujours avant les ennemies. Si deux personnages jouables ont la même initiative, le joueur pourra décider de l'ordre entre les cibles qui ont la même initiative. 

Notre algorithme s'assure de ne jamais donner une initiative identique pour deux ennemis présent dans le même combat. Cette solution est valable grâce au nombre de point de mouvement variant des cibles ennemies.

## Logique de caméra 

Au début des tours, la caméra se centrera sur le personnage ou l'ennemi à qui est le tour. Cette logique s'applique à chaque fois que le tour d'une entité dans la phase de combat s'active.

D'ailleurs, lors de moment de planification ou d'attente, le joueur peut bouger la caméra dans une axe cardinal afin de voir plus loin en haut/en bas/à gauche/à droite selon la position initiale de la caméra dans l'écran du joueur.
