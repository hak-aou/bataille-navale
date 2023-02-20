# Bataille navale en Python
#### *Auteur : Hakim AOUDIA, Sylvain TRAN*
#### *Langage : Python*
#### *Date : 2020*
#### *Niveau : L1, S1*

<p align="center">
  <img src="https://user-images.githubusercontent.com/106891439/218288052-4a601ab9-aa12-489d-9d96-fac3f5bc9c1f.png" width="50%" height="50%">
</p>
On a utilisé la bibliothèque graphique de l'université : fltk.

## Menu principal

Le menu principal offre les options suivantes : 
- Jouer contre un humain
- Jouer contre un bot
- Quitter le jeu

L'utilisateur utilise les flèches directionelles et valide avec la touche entré son choix.

## Choix pseudo

Une fois les pseudos/prénoms écrits, on valide avec la touche entrée.
<p align="center">
    <img src="https://user-images.githubusercontent.com/106891439/218288399-136a4be8-1164-4995-9204-d4913be4736d.png" width="35%" height="35%">
</p>

## Choix bateaux

<img src="https://user-images.githubusercontent.com/106891439/218288404-f32f5d3b-6dca-4980-9310-2864baec83de.png" width="35%" height="35%" style="float: left;">

Le joueur peut choisir parmi plusieurs types de bateaux, chacun ayant un nombre de cases différent. Les bateaux disponibles sont :
- Navire de 1 case
- Navire de 2 case
- Navire de 3 case
- Navire de 4 case
- Navire de 5 case
- Navire de 6 case

6 bateaux de chaque type au maximum.

## Positionnement des bateaux
<img src="https://user-images.githubusercontent.com/106891439/218288411-54a8a975-dc44-4ddf-af3e-ae5f30984eb4.png" width="35%" height="35%">
Une fois que le joueur a choisi ses bateaux, il peut les positionner sur la grille de jeu. Il peut choisir de les placer verticalement ou horizontalement. 

- Bouger avec touches directionnelles
- R pour les tourner
- P pour placer les bateaux automatiquement sur le plateau

## Choix des tirs

<div style="display:flex;">
  <img src="https://user-images.githubusercontent.com/106891439/218288424-8fd375e7-db93-46ec-89ae-e2539b6d9c88.png" width="35%" height="35%" style="margin-right:10px;">
  <p>Le joueur peut tirer sur la grille en utilisant le clique gauche de la souris. Si un bateau est touché ou coulé alors le joueur peut réitérer un tir, sinon c’est à l’autre joueur de tirer et vice versa. Le premier qui a sa flotte détruite perd.</p>
</div>

