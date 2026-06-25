---
layout: default
title: Fonctionnement
nav_order: 2
parent: xTool P3
---

# Fonctionnement

## Allumage

Pour allumer la P3, activez l'interrupteur situé à l'arrière de la machine. La machine peut se déplacer brièvement pendant la phase de démarrage — pas d'inquiétude, tout est normal si vous n'y touchez pas. Profitez de ce calibrage pour préparer votre matériau ou charger votre fichier dans le logiciel xTool.

<img src="images/xTool P3/1. Bouton allumage de la P3 dans le coin droite.jpeg" width="300" style="float:right; margin-right:15px;">

## Charger un fichier

Une fois la machine allumée, lancez le logiciel xTool.

**[Icône du logiciel xTool]**

Dans xTool, cliquez sur « New Project » en haut à droite pour ouvrir un nouveau projet.

**[Image du bouton avec un contour rouge et une flèche]**

Vérifiez que la machine sélectionnée (encadré en haut à droite) est bien la P3 et qu'elle est marquée comme connectée — pas la F2 Ultra.

**[Image de l'encadré de machine connectée]**

>NOTE : si la P3 n'est pas sélectionnée, cliquez sur l'encadré et choisissez la P3.

Importez ensuite un fichier `.svg` ou `.dxf` via le bouton « Import ».

**[Image du bouton avec un contour rouge et une flèche]**

## Affichage de la zone de travail

Avec le fichier chargé dans xTool, positionnez-le correctement pour que la découpe/gravure se fasse à l'emplacement souhaité.

1. Ouvrez le couvercle vitré de la machine.
2. Vérifiez que les rails/barres de la zone de travail sont correctement positionnés.

**[Image de la zone de travail sans soucis]**

Si tout est OK, posez votre matériau sur la zone de travail surlignée en rouge.

**[Image de toute la zone de travail surlignée en rouge]**

Scannez la zone de travail avec le bouton « Refresh background » pour afficher la zone et l'emplacement du matériau.

**[Image de la zone de travail scannée — entourez en rouge et pointez le bouton correspondant]**

Refermez ensuite le couvercle de la machine.

>NOTE : si la résolution du scan est mauvaise sur certaines parties, ou si vous souhaitez reprendre une photo d'un endroit précis après le scan général, refermez le couvercle et appuyez sur « Close shot ». Sélectionnez ensuite la zone voulue ; la tête prendra une photo ciblée.

## Organisation du fichier

Avec la zone scannée visible dans le logiciel, placez votre fichier sur la grille de positionnement.

**[Image d'un fichier bien positionné sur la grille]**

Une fois le fichier positionné, calibrez la tête d'impression sur le point de travail : cliquez sur « Precise measurement » puis cliquez au centre de votre fichier.

**[Image du logiciel avec le bouton entouré et pointé d'une flèche, avec le curseur sur le milieu du fichier]**

La tête passera deux fois sur ce point : une fois avec la zone abaissée, puis avec la zone relevée.

## Sélection du matériau

Cliquez sur « Material » pour ouvrir la fenêtre de sélection (par défaut « Unknown Material »).

**[Image de la zone Material entourée et pointée par une flèche en rouge]**

Recherchez le matériau par nom ou épaisseur, ou utilisez les catégories à gauche pour filtrer les résultats.

**[Image de la fenêtre de sélection de matériau — encadrer la recherche en vert et les catégories en bleu]**

>NOTE : si vous doutez du matériau à sélectionner, demandez au personnel du MakerSpace — ne choisissez pas un matériau au hasard.

(Ex. : pour du bois 5 mm, il peut être nécessaire de choisir un préréglage 6 mm dans xTool selon les presets.)

## Gestion des process

Les "process" représentent les différentes étapes d'un job : actions liées aux éléments du fichier et leurs paramètres. Vous pouvez sélectionner une partie spécifique et choisir entre trois modes :

- **Score** : graver le contour de l'élément sélectionné.
- **Engrave** : graver la surface entière de l'élément.
- **Cut** : découper le matériau selon la forme de l'élément.

**[Image des trois modes entourés de rouge, avec une flèche]**

Vous pouvez visualiser une "preview" de chaque process grâce au bouton dédié.

**[Image du bouton Preview entouré de rouge avec une flèche]**

>NOTE : les previews des modes Engrave et Cut sont interactives — cliquez sur différentes parties du preview pour ajuster les presets de puissance et de vitesse.

## Lancer le job

Avant d'exécuter le job, vérifiez manuellement que chaque process utilise la bonne puissance et vitesse.

Appuyez ensuite sur le bouton « Preview » pour obtenir une simulation digitale du résultat final. Cette prévisualisation permet de détecter rapidement les erreurs dans la planification des process.

**[Image d'une preview d'un projet]**

Si tout est correct, cliquez sur "Process" puis "Start" pour envoyer le job à la machine, puis appuyez sur le bouton à droite de la machine pour commencer le travail.

**[Image du bouton Start entouré de rouge avec une flèche, avec la vue de quand un job est envoyé dessus]**

## Pendant le job

RESTEZ BIEN DEVANT LA P3 DURANT L'**ENTIERETÉ** DU JOB.

Il est obligatoire de vérifier le bon déroulement du job pour éviter un déprat d'incendie lorsque vous avez le dos tourné. Si vous devez pour X ou Y raisons vous éloigner de la machine, vous êtes dans l'obligation de mettre en pause la machine avec le même bouton qui permet de démarer le job.

## Après le job

Une fois le job terminé, veuillez attendre 20 à 30 secondes avant d'ouvrir le couvercle afin de s'assurer que toutes les fumées soient extraites par la ventilation.

Vous pouvez ensuite récuperer votre ou vos pièces découpées et/ou gravées en toute sécurité.

N'oubliez pas d'éteindre la machine si personne d'autre ne compte l'utiliser après vous.