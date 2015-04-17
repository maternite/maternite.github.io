#Namespaces

##Attribuer des identifiants uniques aux items et aux formulaires

Tous les formulaires et items de formulaires doivent être identifiés par un identifiant unique.

Ces identifiants doivent être persistants dans le temps (dans le cas de mise à jour du formulaire).
Ils sont utilisés pour le stockage des données dans la base de données.

Il est préférable, pour éviter les conflits de nommage, d'utiliser des espaces de nommage. Les
espaces de nommage peuvent être séparés par : '::', ':', '.', '__'.

Nous choisissons "::" comme séparateur.

![dot/namespaces.svg](graph namespaces)
