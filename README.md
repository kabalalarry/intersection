# intersection
Intersection d'un cercle
Fonction intersection (entrée R1,R2, entièr)
SommeRayon, distanceCentre en entier
Début
   Écrire ("taper les coordonnées x et y du premier cercle")
   Lire x1,y1
   Écrire ("taper les coordonnées x et y du deuxième cercle")
   Lire x2,y2
   distanceCentre= sqrt((x2-x1)^2+(y2-y1)^2)
   SommeRayon= R1+R2
   Si distanceCentre <= SommeRayon alors
       Écrire "cercle en intersection"
   Sinon
       Écrire " cercle non en intersection"
   Finsi
Fin
