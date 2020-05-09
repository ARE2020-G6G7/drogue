# Travail à faire :

## Semaine 1 
Tout d'abord, nous avons décidé de choisir une ville précise afin de collecter toutes les données et les statistiques nécessaires pour notre étude. D'apres nos premieres recherches scientifiques, la ville de Détroit, aux Etats-Unis, nous parait la plus apte à convenir au projet.

Pour répondre à notre problématique nous nous sommes demandés : 
 - Quels critères devons-nous prendre en compte ? 
 - Comment modéliser une ville dynamique ? 
 Nos recherches nous ont fait comprendre que beaucoup trop de facteurs sont liés à l'influence que peut avoir la drogue dans une ville. Cependant, suites aux restrictions sanitaires et donc a la fermetre de l'université, nous ne pouvons pas considérer tout les facteurs (âge, éducation, corruption ...) et créer une modélisation parlante. 
 Nous avons finalement décidés de prendre comme paramètre uniquement les facteurs socio-économique, pour cela nous allons créer une matrice qui répartie la classe moyenne a riche et la classe pauvre. Pour mieux visualiser notre ville, ils seront modéliser par des 0 et des 1.
 Pour éviter toute erreur, noud vérifions à chaque fois le nombre d'habitants dans la ville.
 
Ensuite, nous allons créer une nouvelle matrice, qui créera une nouvelle version de la ville avec cette fois-ci les consommateurs de drogues et les non-consommateurs.
En effet, lorsqu'un individu est entouré d'un carré de '0', il se transforme en -1. 



Auteur : Nada Lassoued 

## Semaine 2

Une étude a montré que Détroit a perdu 60% de sa population entre les années 50 et 2018, passant de 1,8 millions d'habitants à 600 000.
Logiquement, la population décroit dans une ville sous-développée, cela entraine donc des demandes de déménagements de plus en plus fortes. 
C'est pour cela, que pour cette deuxieme semaine, nous allons ajoutés des fonctions  sur le voisinage : 
Premièrement, une fonction 'voisins' qui met dans une liste l'entourage.Ensuite, une fonction qui calcule la moyene de la liste des voisins. 
- Lorsqu'un '1' a une moyenne voisins <0.5, cela signifie que son entourage est constitué de plus de 0 que de 1. Alors, il a les moyens de vivre dans un milieu plus aisé, ce dernier va chercher à déménager.
- Lorsqu'un '0' a une moyenne voisins >0.5,son entourage est constitué de plus de 1 que de 0. Alors n'ayant pas les moyens de vivre dans un milieu aisé, il va chercher à déménager. 

On va donc les regrouper dans une liste, et pour mieux les visualiser nous allons encore modifier la matrice et représenter ces derniers par des 2. 


Auteur : Nada Lassoued


## Semaine 3

L'objectif de la troisieme semaine est de finir les fonctions "déménagement" afin de commencer a créer les graphiques.
Nous avons également ajouté une derniere modélisation générale de la ville selon n générations, pour visualiser l'évolution de la ville. 
En ajoutant ceci a nos programmes, on peut enfin comprendere par quel processus une ville ou les habitants étaient tous placés aléatoirement, va devenir une ville avec des concentrations de même population aux mêmes endroits et donc créer des "mauvais quartiers" ou l'influence de la drogue ne ferait que s'accroître. 

A aprtir de ces résultats, nous avons pu observer un phénomène. 
- Avec la fonction déménagement, de plus en plus de séparations sont apparus entre riches et pauvres. 
Cela explicite les inégalités économiques et montre que finalement la mixité n'est pas de rigueur entre différentes classes sociales. 

On peut dire que les inégalités économiques sont responsables en partie de l'influence de la drogue sur le développement d'une ville mais notre projet n'est pas une étude assez complète pour pouvoir l'affirmer. 
Il faudrait prendre en compte beaucoup plus de paramètres pour pouvoir faire une étude plus fiable. 

Auteur : Nada Lassoued 

## Semaine 4 (Finalisation des graphiques)

Ce projet nous a permis de nous rendre un peu plus compte d'une société avec beaucoup d'inégalités autant économiques que territoriales. Un phénomène, certes, présent dans beaucoup de pays, mais plus assumé aux Etats-Unis.
Nous sommes satisfaits de notre projet car malgré toutes les difficultés que nous avons pu rencontrer, nous avons réussis à tirer des bons résultats.

Ce projet nous a permis d'apprendre beaucoup de nouvelles choses : 
- La démarche scientifique : les recherches documentaires
- L'analyse de nos résultats 




Auteur : Lassoued Nada
