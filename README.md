# FrameWork Css


Ce framework est composé de 8 fichiers .scss : 


* _alert.scss : style des messages d'alerte ;

* _board.scss : style pour les tableaux ;

* _button.scss : style pour les boutons (taille, couleur) ;

* _grid.scss : style pour une grille de mise en pages, qui permet un alignement facile d'éléments

* _navbar.scss : style pour les menus de navigation (menu, fil d'Ariane, pagination) ;

* _resert.scss : réinitialise à 0 la valeurs de certains éléments HTML, reset CSS de MeyerWeb ; 

* _typo.scss : style pour la typographie du framework ;

* _variables.scss : contient toutes les variables présents dans les fichiers précédents, à utiliser pour changer les valeurs par défaut
et customiser le framework. 

Une version pure CSS est également présente, elle a été produite à partir des fichiers ci-dessus. 


Page Demo: https://nicolas-jcqm.github.io/FrameworkCSS/FrameworkTest.html

## Doc d'installation 

D'abord cloner ou télécharger le dépôt : 
    
    git clone git@github.com:Nicolas-jcqm/FrameworkCSS.git
    
Pour utiliser le framework, vous pouvez :

* Prendre le fichier de style dans le dossier css et faire le lien avec votre fichier .html

* Vous pouvez également prendre les fichiers dans le dossier scss et le personnaliser comme vous voulez. Vous trouverez
dans le fichier _variables, une liste de valeurs à modifier pour personnaliser les couleurs, les tailles, ...
Une fois, les modifications effectuées, ouvrez un terminal à la racine du projet et taper (Sass doit être installé, voir ci-dessous pour l'installation): 

        sass --watch scss:css
        
    Il ne vous reste plus qu'à lier le nouveau fichier de style dans le dossier css à votre fichier .html.
    

## Installation de Sass sous Linux : 

Installer Ruby, puis taper la commande : 

    sudo gem install sass --no-user-install
    
 ## Installation de Sass sous Windows : 
 
 Installer Ruby (https://rubyinstaller.org/), puis taper la commande : 
 
     gem install sass --no-user-install
     
## Installation de Sass sous Linux : 

Installer Ruby, puis taper la commande : 

    gem install sass
