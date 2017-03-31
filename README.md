# Labo3_chat

Mode Serveur

Procédure de connexion en mode « server ».

1)	Lancer l’invite de commande.
2)	Démarrer le serveur en tapant « Server Server.py » dans l’invite de commande (avec la route du fichier en question).
3)	L’adresse IP s’affiche.
4)	Un message reprenant l’adresse IP et le pseudo des clients se connectant au serveur vous sera transmis.
5)	Un message reprenant la liste des personnes connectées leur sera également transmis.



Mode Client

Procédure de connexion en mode « client ».

1)	Lancer l’invite de commande.
2)	Démarrer le serveur en tapant « Client Server.py » dans l’invite de commande (avec la route du fichier en question).
3)	Il vous sera demandé d’entrer l’adresse IP du serveur que vous voulez rejoindre.
4)	Entrez votre pseudo.
5)	Le serveur renvoie une liste des personnes connectées avec lesquelles vous pouvez « chatter ». (En tapant « /help », une liste des commandes - disponibles -  avec leur description vous sera renvoyée.)



Description des commandes

« /connect » : permet de de parler avec une personne. Le serveur demandera avec qui vous désirer « chatter », il vous suffit d’entre le pseudo de cette personne. Il est également possible de parler à plusieurs personnes en même temps mais vous devez alors insérer la commande « /connect » à chaque fois que vous souhaitez parler à une personne différente.

« /send » : insérez cette commande avant de rédiger le message que vous souhaitez envoyer.

« /refresh » : permet de rafraîchir la liste des personnes connectées.

« /quit » : permet de quitter la conversation.

« /exit » : permet de fermer le programme.
