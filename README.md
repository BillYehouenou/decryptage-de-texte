# Décryptage d'un texte

Une méthode de chiffrement classique consiste à appliquer une permutation sur les lettres de l’alphabet. Pour décoder un texte il faut donc connaître la permutation qui a été utilisée. Trouver cette clé en testant toutes les possibilités est très coûteux (pour un alphabet de *n* lettres on a *n*! possibilités). Une façon de faire c’est d’utiliser l’algorithme de Metropolis Hastings sur l’espace de permutations, pour trouver une permutation *plausible*. 
