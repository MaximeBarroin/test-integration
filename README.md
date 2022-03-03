# test-integration

projet test, permettant de comprendre la conception d'un gitflow dans son ensemble

On part d'un projet github, on le clone

création d'un dossier .github

création au sein du dossier.github d'un dossier workflow

Chaque steps correspond à un docker in docker selon le formateur.
chaque steps lance un conteneur, sur une machine 

Un push peut etre déclenché sur une branche ou sur un tag

un switch revient à un git checkout -b sur une version  donné

git checkout -b <branch> permet de créer une branche et switch dessus

On peut cibler des branches spécifiques comme features, en mettant branche/*

exemple: feature/*

Si on veut déclencher certaines routines en fonction de l'heure
avec schedule.