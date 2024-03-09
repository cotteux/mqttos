# MqttOS
Système d'exploitation personnel fonctionnant sur Mqtt pour les nœuds Meshtastic.

En utilisant une installation Node-Red, vous disposerez d'un serveur personnel avec des commandes utiles du système d'exploitation.

Vous aurez 2 versions :

-Version de serveur public avec des fonctionnalités limitées mais une confidentialité totale et pas besoin d'Internet.
Vous pouvez utiliser un petit Raspberry Pi dans un nœud de serveur. J'utilise un petit Orange pi one 512 Mo et ça marche très bien.

-Version de serveur privé avec options avancées et assure le suivi des utilisateurs et des journaux. Il faut également Internet pour certaines fonctionnalités comme le courrier électronique, la météo...

Disponible pour la version publique

help : vous donne la liste des commandes disponibles.

date : vous donne la Date et l'Heure, heure de l'Est

info : infos sur le serveur et votre identifiant sur meshtastic

setting : futur programme de configuration

conv : conversion d'un format à un autre

convic 56 convertit 56 pouces en cm

convci 56 convertit 56 cm en pouces

convfc 56 convertit 56 °F en °C

convcf 56 convertit 56 °C en °F

calc : calculatrice de base avec fonction : + - * / () et exp **

calc (56/4+32)**2

Disponible pour la version privée

Toutes les commandes de la version publique sont disponibles ici.

email : Envoyer un e-mail de Meshtastic vers Internet

ssh : connexion via meshtastic à un serveur ssh (web ou local)

weather : Dernières informations météo de openweathermap.org

