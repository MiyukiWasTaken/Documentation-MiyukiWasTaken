---
layout: default
title: Fonctionnement
nav_order: 2
parent: xTool P3
---

# Fonctionnement

## Allumage

Pour allumer la P3, activez l'interrupteur situé à l'arrière de la machine. La machine peut se déplacer brièvement pendant la phase de démarrage, pas d'inquiétude, tout est normal si vous n'y touchez pas. Profitez de ce calibrage pour préparer votre matériau ou charger votre fichier dans le logiciel xTool.
<img src="../images/xTool P3/bouton-allumage.jpeg" alt="Bouton d'allumage de la xTool P3" width="300" style="margin-top:15px;">
<div style="clear:both;"></div>

## Charger un fichier

Une fois la machine allumée, lancez le logiciel xTool.

<img src="../images/xTool P3/xtool-icon.png" alt="Icône du logiciel xTool" width="100">
<div style="clear:both;"></div>

Dans xTool, cliquez sur « New Project » en haut à droite pour ouvrir un nouveau projet.

<img src="../images/xTool P3/bouton-new-project.png" alt="Bouton New Project" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

Vérifiez que la machine sélectionnée (encadré en haut à droite) est bien la P3 et qu'elle est marquée comme connectée — pas la F2 Ultra.

<img src="../images/xTool P3/machine-connectee.png" alt="Machine Connectée" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

>NOTE : si la P3 n'est pas sélectionnée, cliquez sur l'encadré et choisissez la P3.

Importez ensuite un fichier `.svg` ou `.dxf` via le bouton « Import ».

<img src="../images/xTool P3/bouton-import.png" alt="Bouton Import" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

## Affichage de la zone de travail

Avec le fichier chargé dans xTool, positionnez-le correctement pour que la découpe/gravure se fasse à l'emplacement souhaité.

1. Ouvrez le couvercle vitré de la machine.
2. Vérifiez que les rails/barres de la zone de travail surlignée en rouge sur la première photo sont correctement positionnés comme sur la deuxième photo.

<img src="../images/xTool P3/zone-de-travail.jpeg" alt="Zone de travail sans soucis" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>
<img src="../images/xTool P3/barres-zone-de-travail.png" alt="Zone de travail sans soucis" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

Si tout est OK, posez votre matériau sur la zone de travail. (Zone de travail en vert, matériau en bleu)

<img src="../images/xTool P3/zone-de-travail-avec-materiau.jpeg" alt="Matériau sur la zone de travail" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

Scannez la zone de travail avec le bouton « Refresh background » pour afficher la zone et l'emplacement du matériau.

<img src="../images/xTool P3/bouton-refresh-background.png" alt="Zone de travail scannée" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>
<img src="../images/xTool P3/zone-de-travail-scanee.png" alt="Zone de travail scannée" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

**Refermez ensuite le couvercle de la machine.**

>NOTE : si la résolution du scan est mauvaise sur certaines parties, ou si vous souhaitez reprendre une photo d'un endroit précis après le scan général, refermez le couvercle et appuyez sur « Close shot ». Sélectionnez ensuite la zone voulue ; la tête prendra une photo ciblée.

## Organisation du fichier

Avec la zone scannée visible dans le logiciel, placez votre fichier sur la grille de positionnement.

<img src="../images/xTool P3/fichier-bien-organise.png" alt="Fichier bien placé" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

Une fois le fichier positionné et le couvercle refermé, calibrez la tête d'impression sur le point de travail : cliquez sur « Precise measurement » puis cliquez au centre de votre fichier.

<img src="../images/xTool P3/bouton-precise-measure-curseur.png" alt="Precise Measure et curseur" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

La tête passera deux fois sur ce point : une fois avec la zone abaissée, puis avec la zone relevée.

## Sélection du matériau

Cliquez sur « Material » pour ouvrir la fenêtre de sélection (par défaut « Unknown Material »).

<img src="../images/xTool P3/bouton-material.png" alt="Bouton Material" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

Recherchez le matériau par nom ou épaisseur dans le champ de reherche encadré en violet, et/ou utilisez les catégories à gauche encadrées en bleu pour filtrer les résultats. Le plus simple est d'utiliser à la fois la recherche pour filtrer les matériaux à l'épaisseur souhaitée, puis d'utiliser les catégories pour sélectionner le bon matériau.

<img src="../images/xTool P3/fenetre-selection-materiaux.png" alt="Fenêtre de sélection des matériaux dans xTool" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

>NOTE : si vous doutez du matériau à sélectionner, demandez au personnel du MakerSpace — ne choisissez pas un matériau au hasard.

## Gestion des process

Les "process" représentent les différentes étapes d'un job : actions liées aux éléments du fichier et leurs paramètres. Vous pouvez sélectionner une partie spécifique et choisir entre trois modes :

- **Score** : graver le contour de l'élément sélectionné.
- **Engrave** : graver la surface entière de l'élément.
- **Cut** : découper le matériau selon la forme de l'élément.

<img src="../images/xTool P3/trois-modes-score-engrave-cut.png" alt="Trois modes du logiciel xTool : Score, Engrave et Cut" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

Vous pouvez visualiser une "preview" de chaque process grâce au bouton dédié.

**[GIF du bouton Preview entouré de rouge avec une flèche]**

>NOTE : les previews des modes Engrave et Cut sont interactives — cliquez sur différentes parties du preview pour ajuster les presets de puissance et de vitesse.

## Lancer le job

Avant d'exécuter le job, vérifiez manuellement que chaque process utilise la bonne puissance et vitesse.

Appuyez ensuite sur le bouton « Preview » pour obtenir une simulation digitale du résultat final. Cette prévisualisation permet de détecter rapidement les erreurs dans la planification des process.

<img src="../images/xTool P3/preview-projet.png" alt="Aperçu de projet dans le logiciel xTool" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

Si tout est correct, cliquez sur "Process" puis "Start" pour envoyer le job à la machine, puis appuyez sur le bouton à droite de la machine pour commencer le travail.

<img src="../images/xTool P3/bouton-start.jpeg" alt="Bouton Start du logiciel xTool" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

## Pendant le job

Pendant le job, le logiciel affiche la vue d'une caméra à l'intérieur de la P3, ainsi que le temps restant estimé pour le job. 

<img src="../images/xTool P3/vue-logiciel-pendant-job.png" alt="Vue du logiciel xTool pendant l'exécution du job" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

RESTEZ BIEN DEVANT LA P3 DURANT L'**ENTIERETÉ** DU JOB.

Il est obligatoire de vérifier le bon déroulement du job pour éviter un déprat d'incendie lorsque vous avez le dos tourné. Si vous devez pour X ou Y raisons vous éloigner de la machine, vous êtes dans l'obligation de mettre en pause la machine avec le même bouton qui permet de démarer le job.

<img src="../images/xTool P3/job-en-cours.gif" alt="Animation du job en cours sur la P3" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

## Après le job

Une fois le job terminé, veuillez attendre 20 à 30 secondes avant d'ouvrir le couvercle afin de s'assurer que toutes les fumées soient extraites par la ventilation.

Vous pouvez ensuite récuperer votre ou vos pièces découpées et/ou gravées en toute sécurité.

<img src="../images/xTool P3/job-termine.jpeg" alt="Job terminé" width="600" style="margin-top:15px;">
<div style="clear:both;"></div>

N'oubliez pas d'éteindre la machine si personne d'autre ne compte l'utiliser après vous.