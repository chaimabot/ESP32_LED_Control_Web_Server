# ESP32_LED_Control_Web_Server
Le projet **"ESP32 LED Control Web Server"** permet de contrôler deux LEDs via une interface web sur ESP32. Le serveur gère les requêtes HTTP pour allumer ou éteindre les LEDs.

Détails des entrées et sorties :
Entrées :

Wi-Fi : Connexion à un réseau Wi-Fi avec SSID et mot de passe.|
Bouton LED1 : Envoi de la requête pour allumer ou éteindre LED1.|
Bouton LED2 : Envoi de la requête pour allumer ou éteindre LED2.|
Requête HTTP : Commandes envoyées via le navigateur pour contrôler les LEDs ( /led1/on, /led1/off, /led2/on, /led2/off).|
Sorties :

LED1 : La LED1 s'allume ou s'éteint selon les requêtes HTTP.|
LED2 : La LED2 s'allume ou s'éteint selon les requêtes HTTP.|
États :

Connexion Wi-Fi : Le processus où l'ESP32 se connecte au réseau Wi-Fi.|
Serveur Web prêt : Le serveur HTTP est lancé et prêt à recevoir des requêtes.|
Attente de requête HTTP : Le serveur attend une commande pour actionner les LEDs.|
LED1 allumée / éteinte : Action correspondant à l'état de la LED1.|
LED2 allumée / éteinte : Action correspondant à l'état de la LED2.|
