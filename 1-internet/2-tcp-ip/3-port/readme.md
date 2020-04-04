# Les ports

Avec IP, nous avons de quoi envoyer et recevoir des paquets de données d'un ordinateur à l'autre.
Si nous avons plusieurs programmes qui fonctionnent en même temps sur le même ordinateur, par exemple un navigateur, un logiciel d'email, ou encore spotify.

Quand l'ordinateur reçoit le paquet IP, comment savoir à quel logiciel donner ce paquet IP?

Nous allons donner un numéro unique à chaque logiciel dans l'ordinateur.
Il nous suffit alors d'inclure ce numéro dans chaque paquet IP pour pouvoir s'adresser à tel ou tel logiciel.

On appelle ces numéros des ports.

> Vous pouvez pensez à un colis vous mettez une adresse d'un immeuble (l'IP) mais il faut aussi le numéro de l'appartement (port)

L'adresse IP permet de s'adresser à un ordinateur donné, et le numéro de port permet de s'adresser à un logiciel particulier sur cet ordinateur.

UDP/IP est un protocole qui permet justement d'utiliser des numéros de port en plus des adresses IP (On l'appelle UDP/ID car il fonctionne au dessus d'IP).
IP s'occupe des adresses IP et UDP s'occupe des ports.

Chaque couche (UDP et IP) va ajouter ses informations:

- Les informations de IP vont permettre d'acheminer le paquet à destination du bon ordinateur. Une fois arrivé à l'ordinateur en question, la couche UDP va délivrer le paquet au bon logiciel (ici: au serveur HTTP).
- Les deux logiciels se contentent d'émettre et de recevoir des données ("Hello !"). Les couches UDP et IP en dessous s'occupent de tout.

> Ce couple (199.7.55.3:1057, 204.66.224.82:80) est appelé un socket. Un socket identifie de façon unique une communication entre deux logiciels.
