# PAMI_BASE
Premières bases d'un logiciel pour un robot PAMI pour participer à la Coupe de France Robotique 2025

Le réglement de la coupe de France de Robotique organisés par Planète Sciences 
https://www.coupederobotique.fr/accueil/le-concours/reglement-2025/
nécessite la participation de petits robots, les PAMI.
Ils joueront le rôle de Star ou de Fans. 

Ce logiciel est notre base de travail pour contrôler les PAMI dans les différentes phase du jeu.

La base inclut 
- une gestion des mouvements,
- une détection d'obstacle,
- une gestion du temps (phases de jeu)

Notre robot utilise :
- 2 moteurs pas à pas pour se déplacer,
- des drivers TMC2209 pour les contrôler les moteurs pas à pas
- un ESP32 devkit V1 comme MCU
- 3 détecteurs de distances VL53L0X (Time Of Flight)
- un afficheur OLED 0.96" (SSD1306)
- un PCF8575 extension 16IO qui interface 8 DIP Switch servant au paramétrage du logiciel

Le logiciel est développé en C et C++ sous VSCode - PlatformIO - framework Arduino
