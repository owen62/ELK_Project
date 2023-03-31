# ELK_Project

## Contexte :

L’objectif de ce TP est de tout d’abord mettre en place un conteneur docker (ça peut être un server web comme par exemple apache, nginx….) via un fichier docker-compose.yml.

Une fois le conteneur docker créé on va faire en sorte de récupérer les logs de ce container et les placer dans la stack ELK.

## Démarrage :

Vous pouvez lancer les conteneurs docker avec la commande suivante :

```bash
sudo docker-compose up -d 
```

Il est maintenant possible d'accéder à l’interface graphique de la stack ELK en tapant localhost:5601 dans la barre de recherche de votre navigateur (Username: elastic, Password: pass@123).
