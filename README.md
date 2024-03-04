# MqttOS
Personal operating system running on Mqtt for Meshtastic nodes.

Using a Node-Red installation, you will have a personnal server with useful operating system commands.

You will have 2 versions:

-Public server Version with limited fonctionnality but full privacy and no need of internet. 
       You can use a small raspberry pi into a server node. I use a small Orange pi one 512 meg and it's work great.
       
-Private server version with come with advance options and keeps track of users and log.Also need internet for some functionnalities like email, weather ...

## Available for the Public Version

  **help** : give you the list of availables commands.
  
  **date** : give you the Date and Time eastern time
  
  **info** : info about server and your ID on meshtastic
  
  **setting** : future configuration program
  
  **conv** : conversion from format to another
  
  - convic 56  convert 56 inch to cm
  
  - convci 56  convert 56 cm to inchs
  
  - convfc 56  convert 56 °F to °C
  
  - convcf 56  convert 56 °C to °F
  
  **calc** : base calculator with function : + -  * / () and exp **
  
  - calc  (56/4+32)**2

## Available for the Private Version

  All commands from the public version are available here.

  **email** : Send email from Meshtastic to internet

  **ssh**  :  connection via meshtastic to a ssh server (web or local)

  **weather** :  Last weather info from openweathermap.org
  
