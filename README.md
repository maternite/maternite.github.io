# Introduction

Site regroupant les éléments pour guider l'informatisation du dossier médical du Pavillon Sainte Fleur.

  * les concepts fondamentaux généraux

  * le schéma du NameSpace

  * le schéma de l'arborisation des dossiers
  
  * la liste des formulaires:
  
    * concepts spécifiques au formulaire

    * références bibliographiques 
 
    * liste des items en anglais et en français

# mode d'emploi

  * cloner le dépôt

  * éditer les fichiers Markdown \*.md (Le langage de markup Markdown est le plus simple qui existe à ce jour, voir l'article [Wikipedia Markdown](https://fr.wikipedia.org/wiki/Markdown) et la [traduction française de la syntaxe](https://michelf.ca/projets/php-markdown/syntaxe/)

  * convertir les fichiers Markdown en fichiers HTML5 \*.html avec le logiciel pandoc:

`pandoc -f markdown -t html5 -s index.md -o index.html`

  * git commit -a -S

  * git push
