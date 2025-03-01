# Compte rendu semaine du 24/02/2025 au 02/03/2025


Lors de cette semaine, nous avons commencé à travailler sur le premier prototype :

- Reception et démontage d'un Dreame L10 pro

- Test des différents composants

- Decoupe laser d'un châssis 

- Montage des premiers éléments récupérés sur le châssis 


## Le Dreame L10 pro


### Choix et réception

Suite à la dernière réunion nous avons décidé d'acheter un aspirateur robot d'occasion sur la plateforme Leboncoin.

Nous avons choisi le Dreame L10 pro pour plusieurs raisons : 

- Les pièces détachées de cet aspirateur sont trouvables facilement et à des prix corrects

- Il y avait plusieurs tests, effectués par des sites connus qui lui ont attribué une bonne note :

    - https://www.lesnumeriques.com/aspirateur-robot/dreame-l10-pro-p64593.html
    - https://www.frandroid.com/test/1577718_test-dreame-l10s-pro-aspirateur-robot-laveur

- C'était une très bonne affaire

Le vendeur ayant perdu la base de recharge ne pouvait plus s'en servir, nous avons donc pu l'avoir à un prix réduit 


### Démontage

Suite à la réception de l'aspirateur robot, nous avons pu le démonter.

Malheureusement nous n'avons pas filmé le démontage, voici la liste non exhaustive des pièces que nous avons pu récuperer :

- 2 roues avec moteurs et engrenages

- Un systéme d'aspiration complet composé de :

    - Un support de brosse avec moteur
    - Une boîte à poussière
    - Un moteur d'aspiration 

- Une batterie Lithium-Ion de 14,4V

- Une roue folle

- Un lidar

- Divers capteurs

- 2 lasers

- Une camera

- Un moteur de petite brosse 

## Les tests

Grâce à un générateur et divers cables nous avons pu faire fonctionner les moteurs de roue ainsi que le moteur de brosse.

Le moteur d'aspiration étant un moteur de type BLDC, il nécéssite un driver pour le controler, malheureusement suite à une mauvaise manipulation nous avons endommagé ce moteur et nous allons surement devoir en trouver un nouveau.

## Le châssis 

Pour la réalisation du châssis, nous avons décidés de le faire en bois, à l'aide d'une machine de découpe laser.

Nous avons donc dans un premier temps modéliser le châssis sur Fusion 360, puis nous avons pu faire la découpe.

## L'assemblage

Suite à ça nous avons pu commencer à assembler les divers éléments sur le châssis.

Pour ce faire, nous avons percés de petits trous pour pouvoir attacher les composants au châssis avec du fil de fer.

## La suite

Il faut trouver un nouveau moteur d'aspiration, et réussir à le faire fonctionner.
Il nous faut aussi trouver un moyen de faire fonctionner l'ensemble des moteurs avec un Raspberry Pi, le problème étant qu'un Raspeberry ne peut recevoir et délivrer que 5V.

Nous allons aussi pouvoir commencer à réfléchir au prototype n°2

