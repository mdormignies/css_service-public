Lien vers la page hébergé : https://mdormignies.github.io/css_service-public/
<br>
Github : https://github.com/mdormignies/css_service-public/

<hr>

Toute la page a été structuré avec Bootstrap.

# Header

Ce qui a été ajouté à la balise header est la classe "row" suivie de "align-item-center".
Le header est construit de façon à ce que le logo prenne 9 colonne sur 12 et quant à la div contenant la barre de recherche, elle prend 3 colonne.

# NavBar

La navbar est construite de la même manière mais les classes dropdown, dropdown-menu, dropdown-item ont été ajouté afin que le le sous-menu s'affiche seulement si l'utilisateur passe sa souris sur le menu parent.
Du style a été ajouté pour avoir un dégradé de couleur : grâce à la méthode background: linear-gradient.

# Mon Tableau de bord : partie main

Pour cette partie j'ai aussi utilisé les colonnes de Bootstrap afin que le tableau de bord prenne la plus grosse partie de l'écran. Ce qui a été ajouté au CSS est l'alignement des textes,
  la couleur du background, la couleur du texte qui devait être respectée etc. J'ai utilisé la méthode border-radius poura voir cet effet arrondie de la bordure.

# La partie aside

Cette partie n'a pas grand chose de différent par rapport à la partie main. J'ai modifié la couleur des liens afin qu'elle soit par défaut, et lorsque l'utilisateur survole le lien cela change la décoration.
Aussi, pour les divs contenant "Toutes les astuces" et "Toutes les actualités" j'ai eu recrous aux classes "d-flex flex-column justify-content-end" afin qu'elles soient affichés en bas à droite.

# Footer

La partie footer a également était structuré avec Bootstrap sauf que j'ai ajouté dans le HTML, une autre balise li (qui est vide) afin qu'elle prenne 2 colonnes sur 12 
  pour laisser un vide sur la partie droite du footer. On a donc comme structuration : Le logo (column 1), les li (column 2) sauf le li "Informations légales" qui en prend 3.

# Problème rencontrée

La marge du container a fait décalée beaucoup d'élements rendant ainsi l'alignement difficile.
