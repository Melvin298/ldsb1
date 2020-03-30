# ldsb1

* Sur gitHub je créé un repositoy ldsb1 et je coche l'ajout du fichier readme.md, je modifie aussi son accès en public.
Je créé ensuite dans le repository un fichier index.html, je lui ajoute un H1 dans la branche master

* Dans le bash local git je créé un repository git dans mon dossier utilisateur avec la commande :
**git init ldsb1

* Après je relie mon dépot gitHub à mon repository local:
**git remote add depot https://github.com/Melvin298/ldsb1

* Ensuite je récupère mes fichiers sur mon dépot gitHub pour les mettre sur mon repository local:
**git clone https://github.com/Melvin298/ldsb1

* Ensuite je regarde ce qui y a dans mon dossier ldsb1 pour vérifier que j'ai bien récupérer mes fichiers:
**ls
 
* Je créé une nouvelle branche test:
**git branch test

* On passe sur la deuxième branche:
**git checkout test

* On vérifie que l'on est bien sur la branche test:
**git branch

* Ensuite je vais rajouter un changement, en ajoutant un H2 sur le fichier index.html 
avec l'app nano:
**nano index.html

* Je commit ma modification avec la commande :
**git commit -m "ajout d'un h2"

* On repasse sur la branche principale:
**git checkout master

* Puis on remet les modifiactions dans la master:
**git merge test

* Et pour finir on envoie nos modifications dans notre depot GitHub:
**git push origin master
