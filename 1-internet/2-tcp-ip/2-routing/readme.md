# Le routage IP

Pour envoyer un message sur internet, vous déposez le paquet IP sur l'ordinateur le plus proche (celui de votre fournisseur d'accès en général). Le paquet IP va transiter d'ordinateur en ordinateur jusqu'à atteindre le destinataire.

> Vous pouvez utiliser traceroute (iOS) et tracert (Windows) suivi de l'IP de votre destinataire pour suivre ce routage.  
> exemple: traceroute 178.170.102.194

```bash
traceroute to 178.170.102.194 (178.170.102.194), 64 hops max, 52 byte packets
 1  bbox.lan (192.168.1.254)  4.070 ms  3.233 ms  2.923 ms
 2  i16-les03-ix2-176-181-64-2.dsl.dyn.abo.bbox.fr (176.181.64.2)  12.282 ms  12.316 ms  12.458 ms
 3  * * 62.34.2.49 (62.34.2.49)  14.822 ms
 4  be28.cbr01-ntr.net.bbox.fr (212.194.171.70)  18.316 ms  18.334 ms  18.200 ms
 5  * * *
 6  ikoula.par.franceix.net (37.49.236.76)  18.544 ms  18.370 ms  17.994 ms
 7  po2.core11.th2.ikoula.com (213.246.32.125)  18.235 ms  18.632 ms  18.703 ms
 8  core16.ikdc1.eth-trunk4.ikoula.com (213.246.50.193)  20.240 ms  20.165 ms  20.207 ms
 9  * po2.vss1.ikdc1.ikoula.com (213.246.50.182)  21.266 ms  19.909 ms
10  * * *
```
