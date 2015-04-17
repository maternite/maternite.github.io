#Espaces de nommage (Namespaces)

##Attribuer des identifiants uniques aux items et aux formulaires

Tous les formulaires et items de formulaires doivent être identifiés par un identifiant unique.

Ces identifiants doivent être persistants dans le temps (dans le cas de mise à jour du formulaire).
Ils sont utilisés pour le stockage des données dans la base de données.

Il est préférable, pour éviter les conflits de nommage, d'utiliser des espaces de nommage. Les
espaces de nommage peuvent être séparés par : '::', ':', '.', '__'.

Nous choisissons "::" comme séparateur.

![dot graph namespaces](dot/namespaces.png)

##Structure des dossiers

Les formulaires xml sont regroupés dans deux dossiers principaux:

  *completeforms
  *subforms

Chaque formulaire xml doit être placé dans un dossier spécifique:
  * plus de clarté
  * possibilité d'ajouter:
    * fichier .ui (user interface)
    * fichier .js
    * 1 sous-dossir html contenant le masque d'exportation (xx/*.html) nécessaire
    à l'impression

Pour simplifier, la structure des dossiers suivra la structure des namespaces.
