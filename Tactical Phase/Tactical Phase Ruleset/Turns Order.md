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

