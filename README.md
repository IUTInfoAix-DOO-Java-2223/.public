# Commencer à travailler avec Eclipse

Lisez toutes les phrases jusqu'au bout avant de faire les commandes !

1 - Sur github, forker la séance du jour.

2 - Dans un terminal, se placer dans le répertoire qui contiendra le nouveau répertoire de la nouvelle séance, par exemple Année1 -> Semestre2 -> DOO

	2 - optionnel : si vous ne l'avez jamais fait, faites exécuter la commande qui enregistera par la suite votre token github
	git config --global credential.helper store

3 - Cloner votre fork.

4 - Ouvrir eclipse : quand Eclipse propose de choisir le workspace, choisir celui qui contient les répertoires de vos clones.
(en cas d'erreur, il faut par la suite changer le répertoire du workspace, Menu File -> Switch workspace)

5 - Créer un nouveau projet Java : Menu File -> New -> Java project : lui donner EXACTEMENT le nom du répertoire du dépot de la séance ; ne pas créer de module : décocher la case en bas de la fenêtre.

6 - Choisir la perspective Java (bouton quadrillage sur la droite).

7 - Supprimer le source folder src (sélectionner et touche clavier suppr).

8 - Créer un folder src (attenion pas un Source Folder), puis dedans un folder main, puis dedans un folder java : Menu File -> New -> Folder.

9 - Clic droit sur le folder java : choisir Buid path -> Use as source folder.

10 - Click droit sur src/main/java : choisir new -> package -> donner le nom de l'exercice par exemple exo1.

11 - De même créer vos classes en sélectionnant le package, click droit New -> Class.

12 - Pour commiter vos changements avec Git, ouvrir le perspective -> Git, choisir l'onglet Git Staging pour sélectionner les changements à mettre en staging (bouton +). Commiter dès que le travail doit être conservé. Pousser au plus tard en fin de séance, plus souvent si souhaité.

Par la suite, on peut basculer de la perspective Git à celle de Java suivant les besoins.
