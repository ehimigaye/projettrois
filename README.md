Bonjour, 
etant donné que le k means ne me satifisfaisait pas j' ai utilisé le minibatching KMEANS qui m' a donné de meilleur résultat.
Par contre , il ne me permettait d' optimiser les prediction , j' ai donc essayé de modifier mes données en incluant des parametres temporelles aux données spatiales pour avoir des données
utilisables avec des algorithmes tels que la regression linéaire.
Apres avoir creer le modele les metriques ont montrer qu' il n' etait pas tres pertinents en terme d' efficacité de prédiction.
Apres d' autre recherche j' ai essayé d' essayer un autre alghoritme la foret aléatoire de régression mais le volume de donnée etant trop important ma machine et ma connexion n' etait pas 
assez performante pour gerer le flux de données.
J' ai finalement opter pour un autre algorithme le xgbosst qui regle les probles de flux de données importantes et d' optimisation des models.
Cette fois ci le scoring est satisfaisant .
