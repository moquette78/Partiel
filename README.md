# Partiel

Les tables de la base de données sont à créer:

Pour Etudiant :
id int primary key
nom varchar
prenom varchar
mail varchar
adresse varchar
numero varchar
dateNaissance varchar

Pour Enseignant :
id int primary key
nom varchar
prenom varchar
mail varchar
adresse varchar
numero varchar
matiere varchar

Pour Ecole :
nom varchar primary key
mail varchar
adresse varchar
numero varchar
directeur varchar

Pour Ecole :
theme varchar foreign key 
etudiant int foreign key

L' id pour etre directeur et acceder au menu est 666.
L' id pour etre responsable et acceder au menu est 666.


Lors de l'accès au menu il faut mettre la lettre correspond a l'action que l'on veut faire.
Attention, par manque de temps je n'ai pu tester le type d'entrée lorsque vous tapper quelque chose au clavier (si id demandé ne mettez pas de texte) donc soyez conciliant svp =)
