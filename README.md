# Contribuer à maCave.io

Vous pouvez participer au développement de de ce site. Votre contribution sera la bienvenue. Vous pouvez signaler un bug, une erreur dans le texte ou de traduction, ou demander une amélioration spécifique.

Quelques éléments à vérifer avant de poster votre demande :

* Vérifier que celle-ci n'existe pas déjà.
* En cas de signalement d'un bug, essayer le maximum de détail pouvant permettre de reproduire celui-ci. 
* Indiquer votre login sur le site afin de pouvoir identifier votre matériel.

Merci d'avance pour votre aide.

Nicolas

# Les projets

## La Cave

Le site principal qui contient la gestion de sa cave, ses vins et les fonctionnalités associées pour consommer au mieux vous bouteilles.

## Module Arduino

Ce projet est basé sur le développement d'un module Arduino de surveillance de cave à vin. Celui-ci prévoit les éléments ci-dessous :

- Mesure des températures intérieure et extérieure.
- Mesure de l'humidité intérieure et extérieure..
- Détection de mouvements.
- Contrôle des entrées/sorties par identification RFID.

L'ensemble électronique comprend :
- Module Arduino Sigfox.
- Module Arduino Mini.
- Des capteurs de température et d'humidité.
- Un capteur de mouvement.
- Un capteur de luminosité.
- Un écran LCD.
- Des diodes pour indiquer l'état du module.

![Arduino](https://macave.io/cellars/images/pcm.v2.04.mini.jpg)

Module Arduino de Développement

## Dashboard

Le module capte les données et les transmet part une liaison réseau RJ45 au serveur maCave.io. Elles sont ensuite accessible à travers une adresse https unique et personalisée. Vous pouvez ainsi accèder à l'état de votre cave à tout moment à partir d'un accès internet. En cas d'une intrusion non indentifier par le lecteur RFID une alerte SMS vous est transmise.

![Dashboard](https://macave.io/cellars/images/pcm.v2.05.mini.jpg)

Page de web du Dashboard
