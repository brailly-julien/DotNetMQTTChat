# DotNetMQTTChat

TD : implémenter un forum de discussion en temps réel (CHAT)
- Mosquitto / Hive MQ / MQTT Explorer
Fonctionnalités :
- Login avec un username (unique)
- Chat général pour discuter
- Possibilité de créer un canal de discussion avec un nom
- Inviter des utilisateurs dans un canal de discussion
- Un utilisateur peut rejoindre un canal, quitter un canal et discuter dans un
canal avec les autres utilisateurs du canal.
o N’importe quel utilisateur peut créer un canal
- Possibilité de discuter en one to one avec un autre utilisateur
Il n’y a pas de mise en place de gestion de droits et de rétention (si on démarre
l’application, les canaux sont vides, ainsi que les utilisateurs). Car ça n’est pas le but
du TD.
Interface :
- Page Web ou une console ou une application (wpf …)
Contrainte :
- Utilisation de MQTT pour les messages
Notation sur 15 points
- 3 point pour l’explication sur le fonctionnement de votre solution
o Les commandes utilisées
o Le fonctionnement de vos topics
o Le fonctionnement global de la solution
- 3 points pour le chat général
- 3 points pour le fonctionnement en one to one
- 4 points pour la gestion d’un canal de discussion (création, invitation,
discussion, sortie)
- 2 points pour la qualité du code
o Traitement des exceptions
o Messages d’erreurs
Si le programme ne démarre pas à partir de vos explication, la note sera divisée
par 2.
