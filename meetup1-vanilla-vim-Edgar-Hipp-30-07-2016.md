5 levels:
=========

-	Débutant ultime
-	Débutant
-	Intermédiaire
-	Avancé
-	Expert

Débutant ultime
===============

-	vimtutor ou :Tutor
-	:e pour éditer un fichier
-	:w pour sauver un fichier
-	:q pour quitter
-	:wq pour quitter et sauver
-	:help <subject> pour obtenir de l'aide

Colorschemes:

-	:colorscheme
-	:colorscheme industry en builtin (mais quand meme bien moche)
-	:colorscheme seoul256 https://github.com/junegunn/seoul256.vim
-	:colorscheme nofrils-dark (mon thème minimaliste) https://github.com/robertmeta/nofrils

Débutant
========

Gestion de split

-	:vs pour ouvrir un split vertical
-	:sp pour ouvrir un split horizontal
-	<C-w>hjkl pour aller sur un autre split

Gestion de buffers

-	:ls pour afficher les buffers
-	:b<number> pour changer de buffer
-	:b <partoffilename> pour changer de buffer

Recherche dans un fichier

-	/pattern

Chercher remplacer

-	:%s/pattern/replacement

Recherche dans plusieurs fichiers

-	:vimgrep pattern \**/*.js

Intermédiaire
=============

-	Macros : qq puis @q
-	gf : Go to File
-	Ctrl-N et Ctrl-P : autocomplétion
-	C-6 : toggle entre deux fichiers
-	:E pour afficher le répertoire du fichier en cours
-	:Se pour le faire dans un split horizontal
-	:Ve pour le faire dans un split vertical

Avancé
======

-	:norm, :%norm, ... pour éxécuter une commande sur chaque ligne
-	:g/pattern/action pour éxécuter une action sur chaque pattern

Expert
======

-	+ permet d'aller au premier caractère (non vide) de la prochaine ligne, utile dans les macros
-	`[ et`] : mark du début/fin du dernier paste
-	Bien voir que beaucoup est verbe/motion : Exemples : =},=G,=gg
-	Utilisez les marks (et marks globales)
