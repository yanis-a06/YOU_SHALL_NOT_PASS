02/11/2021
réalisation du schéma de la topologie réseau
Créations de 2 VM : VM1:openBSD, VM2: freeBSD

03/11/2020
Réinstallation de la VM openBSD sans interface graphique
Adressage IP des iterfaces
configuration du server DHCP ( erreur masque incorecte)

04/11/2020
Installation de VMware
installation de la VM1 et laVM2
adressage ip des 2 machines
server DHCP fonctionnel (il assigne une adresse du bon LAN à la VM2).

05/11/2020
Projet iron man

06/11/2020
Lorsque j'ai qu'une machine qui interrog le DHCP elle peut ping le serevr. Des que j'ajoute une seconde machine, le server DHCP fait bien son travail il distribut une adresse du bon LAN au client. Cependant le ping ne fonctionne plus entre la machiine FreeBSD et le server DHCP tandis que mon autre machine cliente (Debian) ping le server DHCP.
Les machines clientes n'ont pas accès au WEB surement a cause du masque du LAN que ma bbox fournit (addresse de classe C)



 


