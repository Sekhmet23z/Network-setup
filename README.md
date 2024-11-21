# Network-setup tool

Ce projet propose un outil conçu pour calculer les informations réseau essentielles en fonction du nombre d'hôtes requis. Il détermine l'adresse réseau, les IP utilisables, l'adresse de diffusion (broadcast) et le masque de sous-réseau.

Fonctionnalités

Détection de classe : sélection automatique des classes de réseau A, B ou C selon le nombre d'hôtes.
Calcul du masque de sous-réseau : ajustement dynamique pour s'adapter au nombre d'hôtes.
Affichage des adresses : montre la première et la dernière IP utilisable, l'adresse de diffusion, la passerelle (gateway) et le prochain réseau.
Interface interactive : menu simple en ligne de commande pour une expérience utilisateur conviviale.

Installation et Exécution (fichier .deb)

Installation
Télécharger le fichier .deb depuis le dépôt ou un autre support.

Installer le paquet :

sudo dpkg -i network-setup-tool.deb

Une fois installé, exécutez simplement la commande :

network-setup

Détails Techniques

Langage : Python 3
Bibliothèques utilisées : ipaddress, math, pyfiglet
Compatibilité : Python 3.8 ou plus
Auteurs

Sekhmet.23z - Créateur du script

Licence

Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus d'informations.
