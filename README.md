# Boite-histoires

Description de la réalisation d'une boite à histoires basée sur Arduino Nano, capteur RFID, lecteur DFPlayer, bouton tactile TTP223 et affichage leds WS2812.
Chaque pastille RFID lance la lecture d'un fichier son MP3 ou WAV. Lorsque la pastille est retirée la lecture est stoppée.
L'appui sur le bouton pendant la lecture la met en pause, un autre appui la relance. Quand il n'y a pas de RFID le bouton est inactif

Version 1 :   

Version 1A :  positionnement des leds à environ trois centimètres au dessous du capteur RFID pour une plus grande diffusion des couleurs.
              stockage sur clef USB. Utilisation du répertoire \MP3 avec les fichiers numérotés de 0001 à 0010 


A venir :   lecture du contenu de la mémoire du RFID pour configurer les paramètres numéro de piste, couleur, luminosité, séquence de lecture, séquence lumineuse, etc ....              
            ajout de TTP223 pour réglages du volume, luminosité
            
