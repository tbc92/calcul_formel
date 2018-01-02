# calcul_formel
L'objectif de ce projet de d'inverser une formule, par un calcul formel.
Par exemple, à partir d'une formule comme a = (b+c)/2, on va renvoyer b=(2*a)-c et c=(2*a)-b

Dans une première verson, on EXIGE d'avoir en entrée une formule hyper-structurée. On refuse y=a+b+c ou y=a*b/c.
A la place, il faut =(a+b)+c ou bien =(a+b)/c

Les variables doivent être des lettres minuscules.
Et on peut avoir des constantes numériques : y = (a+2.5)*(b+c) 
