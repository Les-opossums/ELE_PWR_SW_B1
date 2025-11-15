# Carte lidar - opossum 2025
![Alt text](media/carte_power.png "carte_power")

Cette carte à pour but de faire le dispatch de l'alimentation du robot.

Elle gère 3 types de sorties : 
- 4 sorties pour les moteurs du robot. Elle sont pilotées par le bouton on/off du robot et par l'arrêt d'urgence. Chaque sortie est indépendante (1 mosfet par sortie).
- 3 sorties similaires pilotées par arrêt d'urgence et on/off. Elle doivent servire pour les éléments mobile du robot.
- 3 sorties uniquement pilotées par le bouton on/off. Elles sont réservées pour la partie logique du robot.