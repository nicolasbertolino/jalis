# Dandelions

## Concept

Clint Eastwood revient avec un nouveau block-buster dystopique avec comme idée central le pissenlit, ou plutôt l'idée de les manger par la racine. Ce concept basé sur une dystopie ou un futur plus ou moins apocalyptique se justifie d'un thème sombre, tout en gardant des touches jaunes-orangées pour maintenir de la chaleur sur la page.

## Structure

-	Le background est un retravail très simple du fond.jpg fourni initialement : délavage des couleurs et ajout d'un effet noise dans Photoshop pour rendre compte du côté cinéma.
-	La structure globale de la page est composée d'une barre de navigation en position: fixed et d'un container main qui est une grid à deux colonnes. Cela m'a permis non seulement d'agencer les éléments côte-à-côte mais aussi de créer une responsiveness générale avec seulement un media query.
-	Les cards sont encore une fois la conséquence d'un layout en grille avec pour cette fois l'utilisation du repeat(auto-fill), fantastique propriété de CSS qui permet à mon container de calculer automatiquement l'espace à attribuer aux cartes et à les faire glisser sur la ligne du dessous à partir d'une certaine largeur (200px ici). Un effet de hover a été appliqué sur le contenu des cartes pour ne pas visuellement surcharger le visiteur, effet qui sera cependant et évidemment supprimé dès le mode tablette.

## Assets

La typographie principale est Bahnschrift, qui est une excellente police introduite nativement dans Windows 10. Le logo ainsi que le texte de fond sont écrits avec Vortice Concept, disponible via Adobe fonts.

Les textes sont écrits en blanc (#ffffff) et la couleur secondaire est un jaune-orangé (#ffc551) qui apporte une touche de chaleur.

Les images ont été fournies via le dossier du test d'intégration, sauf les icônes, courtoisie de Font Awesome.
