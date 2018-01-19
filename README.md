# parallel-coordinates

## Définition
"Parallel coordinates" ou "coordonnées parallèles" est une technique de visualisation de données de grande dimension permettaant d'analyser des données multivariées. Cette technique est inspirée de la méthode des séries temporelles.

## Principe
Un espace de dimension n est représenté par n axes verticaux parallèles et disposés de manière équi-écartée. Chaque axe est gradué et correspondra à une des dimensions de l'espace. Un point de dimension n sera donc représenté par une ligne brisée reliant les valeurs de chaque dimension sur son axe correspondant.

## Pratique
Pour représenter un point M(x1,...,xn) on trace n axes parallèles. On place sur ces axes les points de coordonnées (i,xi). Ces points sont ensuite reliés par une ligne brisée.

## Exemple
La figure suivante utilise les coordonnées parallèlles afin de visualiser la base de données IRIS :
![IRIS Plot](/img/ParCorFisherIris.png)
__Coordonnées parallèles appliquées à la BD Iris__

## Historical uses
L'une des premières utilisations de cette technique remonte aux années 1880 avec la visualisation de Henry Gannets : "General Summary, Showing the Rank of States, by Ratios, 1880" qui représente le classement des différents états américains quivant plusieurs critères.
![US Plot](/img/friendly_2008_GASS_19.png)
__General Summary, Showing the Rank of States, by Ratios, 1880__

Ce type de visualisation est devenu populaire dans les années 60 (fin des années 50) dans des applications de détection de collisions dans le traffic aérien, data mining, détection d'intrusion et de vision par ordinateur.

## Incovénients
Cette méthode permet de visualiser les relations entres une dimension et ses dimensions voisines directes à savoir n-1 et n+1. Dans le cas des séries temporelles, il est naturel de comparer les temps t-1 et t+1 avec t, mais dans le cas de dimensions quelconques ce n'est pas toujours le cas. Cela présente une limitation car on doit choisir un ordre bien précis des axes.

## Sources
https://fr.wikipedia.org/wiki/Coordonn%C3%A9es_parall%C3%A8les
https://en.wikipedia.org/wiki/Parallel_coordinates
http://www.sci.utah.edu/~kpotter/Library/Papers/friendly:2008:GASS/
