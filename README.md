# Districall

Pour lancer l'application, cloner le projet, aller dans le fichier .env et changer les valeurs pour votre base de données. 
Aller dans le dossier server, faire les commandes suivantes : php bin/console doctrine:database:create, puis php bin/console doctrine:migrations:migrate.
Enfin, lancer le projet avec la commande symfony server:start

J'ai choisi de faire le status avec des valeurs (0,1,2) pour pouvoir facilement assigner ces chiffres à des valeurs dans le formulaire.
