# Maze_Generator_and_Solver

## AI Developer in wonderland !! "Late, always late !"

Vous sentez vos yeux très lourds se fermer lentement ... 10 secondes plus tard vous vous retrouvez dans un immense labyrinthe. Le décor est somptueux, vous prenez le temps de l’admirer… mais l’envie d’en sortir le plus rapidement possible se manifeste. Courez, sentez l’air sur votre visage… l’algorithme déroule sous vos pieds...

## Contexte du projet
### Vous ne révez plus... vous venez de faire le plein de ressources... Aujourd'ui vous allez créer votre premier labyrinthe !!

Un labyrinthe est un ensemble complexe de chemins tortueux, à embranchements multiples, dans lequel on peut tourner en rond et se perdre. Il existe un point d’entrée et aussi une issue qu’il convient d’atteindre, cette dernière pouvant être confondue avec le point d’entrée. On peut aussi placer en un certain endroit un objet qu’il s’agit d’atteindre. Dans tous les cas, on doit trouver un moyen d’explorer le labyrinthe en passant partout de façon systématique, du moins jusqu’à l’issue finale, en évitant de refaire plusieurs fois le même chemin ou de tourner en rond. Pour s’en sortir, on connaît le fil d’Ariane, les cailloux disposés sur son chemin par le Petit Poucet, ou la stratégie qui consiste à toujours longer les murs que l’on a à sa droite (ou à sa gauche si l’on préfère). Mais tout cela demande à être précisé.

Le but de ce projet est de créer un code python qui va générer aléatoirement des grilles de labyrinthe, qui va être capable de trouver la solution de celles-ci, si elle existe (eh oui, il se peut qu'un labyrinthe soit insoluble!), et qui pourra afficher tout ça sous la forme d’une image !

On a appris à parcourir un arbre, en choisissant par exemple d’aller à droite lorsque plusieurs bifurcations se présentent, et en faisant demi-tour lorsqu’on atteint une feuille de l’arbre. Pour résoudre un labyrinthe, l’approche est similaire. Pour cela considérons un objet mobile en forme de carré, caractérisé par sa position (x, y) et dirigé dans une certaine direction, celle qu’il a devant lui. A partir de cette direction, l’objet mobile peut soit garder cette direction, soit faire un quart de tour à droite, soit faire un quart de tour à gauche, soit faire demi-tour. Pour respecter les conditions de l’exploration, il va privilégier de tourner à droite, mais s’il tombe sur un mur, il choisira d’aller devant, et s’il tombe encore sur un mur, il ira à gauche. Enfin, s’il tombe sur un cul-de-sac, il fera demi-tour.
## « Dans le labyrinthe, tu ne te perds pas... tu te retrouves »

## Livrables

Créer une application permettant de générer de manière aléatoire un labyrinthe (l’utilisateur pourra décider de la taille du labyrinthe généré, par exemple 10x10 ou 50x100) et permettant également de résoudre le labyrinthe.

## Ressources

https://fr.wikipedia.org/wiki/Mod%C3%A9lisation_math%C3%A9matique_de_labyrinthe

## Modalités pédagogiques

Votre rendu se fera sur **Simplonline sous la forme d'un lien github **via lequel sera accessible le code de votre application. Un rendu individuel est attendu au plus tard le lundi 11 janvier 2021 à 17h30.

## Critères de performance

L'algorithme de résolution du labyrinthe devra proposer comme solution le chemin le plus court. Le temps d'exécution de l'algorithme est un critère important.

## Modalités d'évaluation

Le code devra être fonctionnel et structuré selon les standards de la programmation objet. Les méthodes proposées dans votre application devront être commentées. L'implémentation de tests unitaires est un plus.
