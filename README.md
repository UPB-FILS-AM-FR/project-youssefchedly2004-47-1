# Your Project Name
    PONG sur Écran OLED
| | |
|-|-|
|`Author` | youssef chedly

## Description
Ce projet implémente le jeu classique PONG sur un écran OLED SSD1306 (128x64 pixels). Deux joueurs s'affrontent simultanément en contrôlant chacun une raquette via un joystick analogique.Le jeu inclut une physique de balle avec rebond angulaire, une accélération progressive pour augmenter la difficulté, et un système de score automatique.
## Motivation
L'objectif est de créer un système embarqué interactif et complet respectant les contraintes suivantes :Utilisation d'une breadboardç 830) sans soudure.Utilisation de protocoles de communication standards (I2C pour l'écran).Gestion d'entrées analogiques multiples en temps réel.Structure de code modulaire et optimisée pour atteindre environ 50 FPS.
## Architecture
L'architecture du système repose sur une unité centrale de traitement, l'Arduino Nano. Le système utilise l'architecture I2C pour la communication avec l'écran OLED, ce qui réduit le nombre de fils nécessaires à seulement 2 broches de données (SDA et SCL). Pour le contrôle du jeu, les deux joysticks utilisent les entrées analogiques A0 et A1 de la carte

### Block diagram

<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic
file:///C:/Users/pc/AppData/Local/Temp/e1857515-1dec-4fbf-b0cf-c0b27b0a748c_arduino_project_final%20(1).zip.48c/arduino_project/maquette_virtuelle.svg
![Schematic](schematics/kicad_schematic.png)

### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
|Arduino Nano |	Microcontroleur ATmega328P, 16MHz, 32KB Flash — compatible breadboard|[25 RON]
|Ecran OLED SSD1306 	128x64 pixels, |interface I2C, 0.96 pouce — adresse 0x3C	[10 RON ]

|Module Joystick Analogique |	Joystick 2 axes (X/Y) + bouton integre — type PS2 compatible Arduino	]23 RON [

|Breadboard 830 points |	Plaque d'essai sans soudure — 830 trous, format standard	10 RON@
|	Fils de Connexion Male-Male |	Jumper wires dupont 20cm — pack de 40 fils assortis	1 pack	15 RON@@
	|Cable USB Mini-B ESSENTIEL	Cable USB-A vers Mini-USB pour programmer l'Arduino Nano	5 RON ]

	|Batterie 9V + Connecteur OPTIONNEL	Pile 9V avec clip snap + connecteur jack DC 2.1mm pour alimentation sans USB		12 RON][
|Buzzer Passif 5V OPTIONNEL	Pour ajouter des sons de rebond / point marque (broche D8)
### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May


## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
