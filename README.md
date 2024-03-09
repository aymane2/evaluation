# evaluation

# Installation de Docker sur Mac :

Téléchargez Docker Desktop pour Mac à partir du site officiel de Docker.
Double-cliquez sur le fichier téléchargé pour lancer l'installation.
Suivez les instructions à l'écran pour installer Docker Desktop.
Une fois l'installation terminée, lancez Docker Desktop depuis votre dossier Applications.
Clonage du code source de l'application de vote :

# Ouvrez Terminal sur votre Mac.
Utilisez la commande git clone pour cloner le dépôt Git contenant le code source de l'application de vote.
Cela créera un répertoire flask-app contenant le code source de l'application.
Construction de l'image Docker :

# Accédez au répertoire flask-app dans Terminal.
Créez un fichier Dockerfile dans ce répertoire et définissez les instructions pour construire votre image Docker.
Utilisez la commande docker build pour construire l'image Docker à partir du Dockerfile, en remplaçant nom_image par le nom que vous souhaitez donner à votre image.
Exécution de l'application dans un conteneur Docker :

# Après la construction de l'image, exécutez votre application dans un conteneur Docker en utilisant la commande docker run, en spécifiant le port à utiliser.
Cela lancera l'application de vote dans un conteneur Docker sur votre machine.
Test de l'application :

# Ouvrez un navigateur web sur votre Mac.
Accédez à l'URL http://localhost pour tester l'application de vote.
