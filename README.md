# USSD-Togo

## Évolution du secteur des télécommunications au Togo

Le secteur des télécommunications au Togo a connu une transformation majeure depuis 2019, avec la privatisation de l'opérateur historique et le repositionnement stratégique des deux principaux acteurs du marché. Cette évolution s'inscrit dans le cadre du Plan National de Développement (PND) du Togo, qui vise à faire du pays un hub régional pour la digitalisation et la technologie.

### Yas Togo (anciennement Togocom, Togo Telecom et Togo Cellulaire)

En novembre 2019, le gouvernement togolais a accepté l'offre d'Agou Holding, un consortium composé du Groupe Axian et d'Emerging Capital Partners (ECP), pour acquérir 51% des parts de Togocom, la holding regroupant Togo Telecom et Togo Cellulaire (Togocel). Cette privatisation a valorisé l'entreprise à plus de 210 milliards de FCFA. L'État togolais conserve 49% des parts. Le consortium s'est engagé à investir 245 millions d'euros (environ 160 milliards de FCFA) sur sept ans pour révolutionner le secteur numérique au Togo.

Depuis cette acquisition, l'opérateur a considérablement développé son infrastructure. En novembre 2020, Togocom a lancé le premier réseau 5G d'Afrique de l'Ouest, en partenariat avec Nokia. En novembre 2022, l'opérateur a atteint le jalon de 1000 stations de base, couvrant 88% du territoire national et 98% de la population togolaise. En janvier 2024, l'entreprise a obtenu un prêt de 60,2 millions de dollars de la Société Financière Internationale (IFC) pour moderniser son infrastructure et étendre ses services 4G LTE et fibre optique.

Le 25 novembre 2024, Togocom a officiellement changé de nom pour devenir Yas Togo, dans le cadre d'une stratégie de rebranding menée par le groupe panafricain Axian. Ce changement s'inscrit dans une démarche d'unification des marques d'Axian Telecom à travers l'Afrique, où Tigo en Tanzanie, Telma à Madagascar et aux Comores, Free au Sénégal, et Togocom au Togo sont désormais réunis sous le nom Yas. Dans la même dynamique, le service de mobile money TMoney a également été renommé et s'appelle désormais Mixx by Yas.

### Moov Africa Togo (anciennement Moov Togo)

Moov Togo, opérateur privé présent au Togo depuis 1998, était une filiale d'Atlantique Telecom. En 2015, Maroc Telecom a acquis Atlantique Telecom et ses filiales en Afrique de l'Ouest et Centrale, dont Moov Togo. Maroc Telecom est lui-même détenu à 53% par le groupe Etisalat et à 30% par le Royaume du Maroc.

En janvier 2021, dans le cadre d'une stratégie de marque unifiée, Maroc Telecom a rebaptisé toutes ses filiales africaines sous la marque "Moov Africa". Ainsi, Moov Togo est devenu Moov Africa Togo. Cette nouvelle identité illustre la vision "L'Afrique en mouvement" du groupe Maroc Telecom et vise à renforcer les synergies entre ses différentes filiales présentes dans 11 pays africains.

### État actuel du marché et avancées technologiques

Aujourd'hui, le marché des télécommunications au Togo est dominé par ces deux opérateurs qui investissent massivement dans les technologies de nouvelle génération. La 4G est largement déployée dans les zones urbaines, et la 5G a commencé à être déployée à Lomé depuis fin 2020. Yas Togo (ex-Togocom) vise à fournir un accès Internet mobile à 95% de la population d'ici 2025, tandis que Moov Africa Togo continue d'améliorer ses services avec des vitesses de téléchargement moyennes de 31,60 Mbps selon une étude de 2023.

Ces développements s'inscrivent dans la Stratégie de Transformation Digitale du gouvernement togolais, qui vise à améliorer la connectivité mobile et fixe à haut débit pour l'ensemble de la population, favorisant ainsi l'inclusion numérique et le développement économique du pays.

---

Ce repos cree pour tuer le temps rassemble les codes USSD des operateurs de telephonies mobile present au Togo.
J'essayerai de le mettre a jour le plus souvent que possible.

## Moov Africa Togo (anciennement Moov Togo / Atlantique Telecom Togo)
[Site Officiel](https://www.moov-africa.tg)

_Mise à jour: Novembre 2024_

### Services de base
- `*101#` - Consulter son crédit
- `*102#` - Transfert de crédit de communication
  - Pour transférer : `*102*crédit*numéro*code#`
- `*106#` - Connaître son numéro
- `*107#` - Gérer ses numéros préférés
  - Ajouter un numéro: `*107*1*numéro#`
  - Supprimer un numéro : `*107*0*numéro#`
- `*108*numéro#` - Rappel moi (demande de rappel sans crédit)
- `*109*code crédit*numéro#` - Achat de crédit à distance

### Services Flooz (Mobile Money)
- `*155#` - Menu principal Flooz/Moov Money
- `*155*1#` - Transfert d'argent
- `*155*3*1#` - Achat de crédit via Moov Money
- `*155*4*3#` - Réabonnement CANAL+
- `*155*4*4#` - Paiement en magasin
- `*155*5#` - Participation à une collecte de fonds
- `*155*6#` - Consultation du solde Moov Money
- `*155*7#` - Paiement de frais d'inscription aux examens et concours
- `*155*9#` - Service Bank'vi (tontine digitale) et achat de forfaits

### Nouveaux services (2024)
#### PASS MONEY FLOOZ (lancé en juin 2024)
- Permet de transférer de l'argent entre les comptes Flooz et Orabank sans nécessiter de connexion internet
- Accessible via le code USSD `*155*7*2*4#`
- Fonctionnalités:
  - Transfert Orabank vers Flooz
  - Transfert Flooz vers Orabank
  - Consultation de solde
  - Mini-relevé de compte
- Procédure de souscription:
  1. Saisir `*155#`
  2. Choisir l'option 7, « Ma Banque en ligne»
  3. Choisir l'option 2 « Banques »
  4. Choisir l'option 4 « ORABANK »
  5. Choisir l'option 5 « Souscription »
  6. Suivre les instructions pour finaliser la souscription

#### Bank'vi (service de tontine digitale)
- Permet de constituer une épargne rotative (tontine) à partir d'un compte Mobile Money Flooz
- Accessible via le code USSD `*155*9#`
- Les participants s'engagent à verser une somme prédéterminée à une fréquence donnée
- Fonctionnalités:
  - Sécurité des fonds: tous les fonds sont collectés sur un compte Mobile Money Flooz différent des comptes des membres
  - Sécurité de collecte: protection contre le vol ou le détournement des fonds
  - Transparence de la gestion: notifications SMS pour chaque transaction
  - Gestion du cycle de la tontine: validation transparente des demandes de remboursement

### Autres services
- `*100*1*1#` - Connaître son numéro et profil
- `*100*2#` - Codes pour migration de profil
- `*100*3#` - Activer/désactiver des services (moovtones, Soscredit, Moovkiosque, moovScoop)
- `*100*4#` - Informations sur les promos et événements
- `*100*5#` - Trouver une agence Moov
- `*100*8#` - Autres codes utiles


## Yas Togo (anciennement Togocom / Togocel / Togo Telecom)
[Site Officiel](https://yas.tg)

_avril 05, 2017_ Credit [emilasic](http://emilasic.blogspot.com/2017/04/les-codes-ussid-de-et-moov-togo-togocel.html)

- `*444#` Connaitre la solde de son credit de communication.

- `*555#` Afficher son numero Togocel

3. `*104*1#`

Vous voulez surfer avec la connexion 0.3G de Togocel, faites *104*1# pour activer votre service internet gratuitement.

4. `*104*2#`

Pour chargez votre data vous permettant ainsi de surfez avec " la bonne connexion" internet de Togocel.

5. `*919*8*2#`

Pour consulter votre forfait internet, c'est le code qu'il faut taper.

6. `*919#` (**Forfait Voice+Data**)

 * `*919*1#` Forfait journalier ,avec 200 F de credit, vous avez 400 F de crédit de communication vers Togocel et 200 F de credit de communication vers les réseaux nationaux + 25 SMS et 20 Mo(Data). Validité: 1 jour.


* `*919*2#` Forfait 2 jours , avec 500 F de crédit, vous  bénéficiez de  1500 F de crédit de communication vers Togocel et 500 F de crédit de communication vers les réseaux nationaux + 50 SMS et 50 Mo. Validité (2 jours)


* `*919*3#` Forfait 2 jours , avec 1000 F de crédit, vous  bénéficiez de  8000 F de crédit de communication vers Togocel et 1000 F de crédit de communication vers les réseaux nationaux + 50 SMS et 100 Mo. Validité (2 jours)


* `*919*4#` Forfait 10 jours , avec 2500 F de crédit, vous  bénéficiez de  7500F de crédit de communication vers Togocel et 2500F de crédit de communication vers les réseaux nationaux + 50 SMS et 350 Mo. Validité : 10 jours

*919*5#

Forfait Bavard de Togocel: Avec 200 F de crédit, vous avez 600 F de crédit de communication vers Togocel et 200 F vers les réseaux nationaux.
Validité: 1 jour.

*919*6#
Forfait 10 jours (2), Avec 2000 F vous bénéficiez de 8000F de communication ves les numéros Togocel et 2000F vers le numeros nationaux +50 SMS.
Validité: 10 jours.


*919*7#
Forfait 10 jours (2), Avec 3000 F vous bénéficiez de 20. 000 F de communication vers les numéros Togocel et 5.000 F vers le numéros nationaux +100 SMS.

Validité: 10 jours.


*919*8#
Si vous avez activez un de ces forfaits (*919*n#), voici le code (*919*8#)  qu'il faut taper pour consulter votre solde. Ce code vous renvoie votre montant restant de communication, le nombres de SMS restant ainsi que votre Data(Méga) restant.


*919*9#
Ce code vous permet d'accéder à un menu promo des forfait de togocel. Essayer,  les avantages sont revus.

*919*10#
Vous aimez surfer les nuit? Tapez *919*10# pour activer votre forfait Data nuit.

7. *445#
Pour vos pannes de crédit ou de Data , plus de soucis, Togocel le leader a la solutions. Il suffit de taper *445# pour bénéficier des prêts pour vous même et pour vos proches.
Attention: le remboursement se fait avec une commission de 10%.😜😜😜
