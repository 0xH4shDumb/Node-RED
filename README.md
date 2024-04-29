# Projet Node-RED 

Ce projet vise à faciliter la récupération et l'exploitation des données provenant d'un capteur connecté à une passerelle LoRaWAN Milesight en utilisant Node-RED.

## Configuration requise

Avant de commencer, assurez-vous d'avoir les éléments suivants :

- Une passerelle LoRaWAN Milesight configurée et opérationnelle.
- Un capteur compatible avec la passerelle LoRaWAN Milesight.

Node-RED est directement disponible sur la passerelle.

## Récupération de données

Pour récupérer les données envoyées par le capteur, utiliser le fichier "GET_DATA.js".

Les différentes répertoires présents dans ce projet concernant majoritairement le levé d'alarmes en cas d'alertes majeures.

## Bonus

La modification visuelle des jauges pouvant être particulièrement complexes, voici un accès à la mise en place de cette jauge:
![image](https://github.com/0xH4shDumb/Node-RED/assets/98525935/70faea52-48f7-47ae-8a17-cc30942e83db)

Réalisation sur Node-RED:
![image](https://github.com/0xH4shDumb/Node-RED/assets/98525935/5b1faefa-2788-4d3e-9c26-cc875c2897ae)

Configuration du noeud "Change" (noeud jaune):
![image](https://github.com/0xH4shDumb/Node-RED/assets/98525935/0b21e942-743d-4e13-a6ce-b4e7c09c251d)

Configuration du noeud "Function" (noeud orange):
![image](https://github.com/0xH4shDumb/Node-RED/assets/98525935/bef89169-28cd-4875-8cfe-eb07e391a5e0)

Configuration du noeud "Gauge" (noeud bleu):
![image](https://github.com/0xH4shDumb/Node-RED/assets/98525935/15448816-1289-4ce7-b876-460917f149c3)
