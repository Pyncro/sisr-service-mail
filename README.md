# sisr-service-mail


### Contexte :

Le groupe lyonnais Lise Charmel a été victime d’un ransomware le 8 novembre 2019. La société a refusé de
payer et son système informatique complet est resté bloqué pendant près d’un mois, ralentissant
considérablement l’activité du groupe et de ses 1 150 employés au niveau mondial.
Le manque à gagner est chiffré par ses dirigeants à plusieurs millions d’euros.
Le vers qui a intégralement crypté les données de l’ensemble des machines du réseau, serveurs de
sauvegarde compris, est arrivé via un mail reçu par le service commercial.
Pour éviter de se trouver à nouveau dans une situation semblable, plusieurs mesures ont été mises en
œuvre. La plus radicale, pour laquelle vous êtes recruté, est la mise en place d’un service mail interne à
l’entreprise. Les machines reliées à l’Internet seront uniquement celles nécessaires à l’activité de l’entreprise
et le seront via des sandbox. L’ensemble des communications internes se fera par ce nouveau service de
courrier interne.


### Demande du client :
L’entreprise possède un nom de domaine pour chaque lieu de production. Tous dépendent de la zone .com.
Il s’agit de mettre en place sur le LAN de
Un PC qui dispose de deux cartes réseau sera utilisé comme passerelle entre le LAN et le WAN.



### Travail à réaliser :
1. Choisir un nom de domaine. 10.0.0.0/19
2. Réaliser un routage permettant la communication de votre LAN avec le WAN.
3. Héberger une page sur une machine placée dans votre LAN. Cette page doit être accessible depuis le WAN.Une simple page statique contenant votre nom ou une image est suffisante.
4. Mettre en place un service mail sur votre LAN. Votre page doit être accessible par son nom depuisn’importe quel LAN du projet. Des messages doivent pouvoir être envoyés et reçus vers et depuis les autres LAN.
