# USSD-Togo

Ce dépôt rassemble les codes USSD des opérateurs de téléphonie mobile présents au Togo.

_Dernière mise à jour: Mai 2025_

## Moov Africa Togo
[Site Officiel](https://www.moov-africa.tg)

### 1. Informations générales et gestion du compte

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Menu principal | **\*100#** | Infos numéro, Profil, Avantages, Offres, P&S... |
| Consultation du solde | **\*101#** | Consulter son solde |
| Statut identification | **\*202#** ou **\*848#** | Vérifier le statut d'identification de votre SIM |
| Désactivation/Activation push | **\*100\*3\*4#** | Accéder au menu désactivation/Activation des notifications push |
| Connaître son numéro | **\*106#** | Afficher son propre numéro de téléphone |

### 2. Transfert de crédit et gestion du code secret

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Modifier code secret | **\*102\*0000\*nouveau code#** | Modifier son code secret |
| Transfert de crédit | **\*102\*montant\*numéro d'appel du bénéficiaire\*code secret#** | Transférer du crédit à un autre numéro |
| Rechargement d'un tiers | **\*109#** | Accéder au service rechargement |

### 3. Migration entre profils

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Migration Moov Classic | **\*106\*0#** | Code de Migration dans le profil Moov Classic |
| Migration Epiq Nation | **\*106\*2#** | Code de Migration dans le profil Epiq Nation |
| Migration Moov Seconde | **\*106\*3#** | Code de Migration dans le profil Moov Seconde |
| Migration Moov Privilège | **\*106\*4#** | Code de Migration dans le profil Moov Privilège |

### 4. Gestion des numéros complices

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Voir liste des numéros complices | **\*107#** | Voir ma liste de numéro(s) complice(s) |
| Ajouter un numéro complice | **\*107\*1\*numéro#** | Enregistrer un nouveau numéro complice |
| Supprimer un numéro complice | **\*107\*0\*numéro#** | Supprimer un numéro complice |

### 5. Moov Bip et autres services

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Moov Bip | **\*108\*numéro du correspondant#** | Envoyer un bip à un correspondant |

### 6. Moov Money Flooz (Services financiers)

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Menu principal Flooz | **\*155#** | Accéder au menu principal de Moov Money Flooz |
| Activation du compte Flooz | **\*155#** | Activer automatiquement votre compte Moov Money Flooz |
| Transfert vers un numéro Moov | **\*155\*1\*1\*Numéro Moov\*Montant\*Code Secret#** | Transférer de l'argent vers un numéro Moov au Togo |
| Transfert vers un autre réseau | **\*155\*1\*1\*Numéro autre réseau\*Montant\*Code Secret#** | Transférer de l'argent vers un numéro d'un autre réseau au Togo |
| Achat de crédit pour soi | **\*155\*3\*1\*Montant\*Code Secret#** | Acheter du crédit pour son propre numéro |
| Achat de crédit pour un proche | **\*155\*3\*2\*Numéro\*Montant\*Code Secret#** | Acheter du crédit pour un autre numéro |
| Paiement de factures | **\*155\*4#** | Accéder au menu de paiement de factures |
| Paiement CEET/TDE | **\*155\*4\*1#** | Payer une facture d'électricité ou d'eau |
| Paiement Université | **\*155\*4\*2#** | Payer des frais universitaires |
| Paiement Cashpower | **\*155\*4\*5#** | Acheter du crédit Cashpower |
| Duplicata Cashpower | **\*155\*4\*5#** option 3 | Obtenir un duplicata de code Cashpower |
| Réabonnement Canal+ | **\*155\*4\*8\*1#** | Réabonnement Canal+ à l'identique |
| Consulter solde Flooz | **\*155\*6#** | Consulter son solde Moov Money Flooz |

### 7. Forfaits Internet et services

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Forfaits Internet 4G | **\*100\*3\*1#** | Acheter un forfait Internet |
| Consultation volume Internet | **\*100\*3\*2\*1#** | Consulter son volume Internet restant |
| Achat de pass pour un tiers | **\*100\*3\*4#** | Acheter un forfait Internet pour un tiers |
| Forfaits mixtes et voix | **\*100\*1#** | Acheter un forfait mixte (appels, SMS, Internet) |
| Forfaits internationaux | **\*100\*5#** | Acheter un forfait pour appels internationaux |
| Pass internationaux | **\*100\*3\*6#** | Souscrire à un pass international (roaming) |

## Yas Togo (anciennement Togocom / Togocel / Togo Telecom)
[Site Officiel](https://yas.tg)

### 1. Menu principal et services généraux

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Menu principal | **\*909#** | Menu principal regroupant tous les services |
| Consultation du solde | **\*444#** | Consulter son solde |
| Service client | **888** | Appeler le service client mobile |
| Service client Fibre | **119** | Appeler le service client Fibre |
| Service client Yas Togo | **8845** | Appeler le service client général |

### 2. Forfaits Internet (Net)

| Forfait | Volume | Validité | Prix | Code USSD |
|---------|--------|----------|------|-----------|
| Net100 | 45 Mo | 24h | 100 FCFA | **\*909\*212#** |
| Net199 (Nuit) | 1 Go | 22h-6h | 199 FCFA | **\*909\*218#** ou **\*909\*199#** |
| Net250 | 250 Mo | 2 jours | 250 FCFA | **\*909\*250#** |
| Net250 Alèz | 375 Mo | 24h | 350 FCFA | **\*909\*350#** |
| Net350 | 280 Mo | 2 jours | 350 FCFA | **\*909\*214#** |
| Net500 (Nuit) | 3 Go | 22h-6h | 500 FCFA | **\*909\*215#** |
| Net600 | 700 Mo | 2 jours | 600 FCFA | **\*909\*216#** |
| Net1499 | 5 Go | 3 jours | 1499 FCFA | **\*909\*242#** |
| Net1000 | 1 Go | 7 jours | 1000 FCFA | **\*909\*221#** |
| Net1500 | 1.6 Go | 7 jours | 1500 FCFA | **\*909\*222#** |
| Net3000 | 3 Go | 30 jours | 3000 FCFA | **\*909\*231#** |
| Net5000 | 6 Go | 30 jours | 5000 FCFA | **\*909\*232#** |
| Net10000 | 20 Go | 30 jours | 10000 FCFA | **\*909\*233#** |
| Air Fiber | 60 Go | 30 jours | 15000 FCFA | **\*909\*234#** |
| Air Fiber+ | 110 Go | 30 jours | 25000 FCFA | **\*909\*235#** |

### 3. Forfaits Mixtes (OVO)

| Forfait | Appels | Internet | SMS | Validité | Prix | Code USSD |
|---------|--------|----------|-----|----------|------|-----------|
| OVO200 | 700F | 20 Mo | 25 SMS | 24h | 200 FCFA | **\*909\*311#** |
| OVO250 | 1000F | 20 Mo | 25 SMS | 24h | 250 FCFA | **\*909\*314#** |
| OVO300 | 1500F | 35 Mo | 25 SMS | 24h | 300 FCFA | **\*909\*312#** |
| OVO500 | 2200F | 70 Mo | 25 SMS | 48h | 500 FCFA | **\*909\*313#** |
| OVO1000 | 5400F | 120 Mo | 50 SMS | 7 jours | 1000 FCFA | **\*909\*321#** |
| OVO2500 | 13500F | 350 Mo | 50 SMS | 7 jours | 2500 FCFA | **\*909\*322#** |
| OVO5000 | 20000F | 1 Go | 100 SMS | 30 jours | 5000 FCFA | **\*909\*332#** |
| OVO7500 | 42000F | 1.5 Go | 100 SMS | 30 jours | 7500 FCFA | **\*909\*331#** |
| OVO10000 | 400 min | 3 Go | 100 SMS | 30 jours | 10000 FCFA | **\*909\*333#** |

### 4. Forfaits Voix & SMS (LEMA)

| Forfait | Appels | SMS | Validité | Prix | Code USSD |
|---------|--------|-----|----------|------|-----------|
| LEMA200 | 1000F | 25 SMS | 24h | 200 FCFA | **\*909\*411#** |
| LEMA400 | 1800F | 75 SMS | 48h | 400 FCFA | **\*909\*413#** |
| LEMA500 | 2500F | 25 SMS | 3 jours | 500 FCFA | **\*909\*412#** |
| LEMA600 | 3100F | 75 SMS | 3 jours | 600 FCFA | **\*909\*414#** |
| LEMA1000 | 5500F | 50 SMS | 7 jours | 1000 FCFA | **\*909\*421#** |
| LEMA2000 | 12000F | 100 SMS | 7 jours | 2000 FCFA | **\*909\*4\*222#** |
| LEMA3000 | 17100F | 100 SMS | 10 jours | 3000 FCFA | **\*909\*4\*223#** |
| LEMA9000 | 60000F | 200 SMS | 30 jours | 9000 FCFA | **\*909\*431#** |

### 5. Forfaits International

| Destination | Minutes | Validité | Prix | Code USSD |
|-------------|---------|----------|------|-----------|
| Bénin et Nigéria | 6 min | 30 jours | 500 FCFA | **\*909\*621#** |
| Côte d'Ivoire, Ghana, Sénégal | 5 min | 30 jours | 800 FCFA | **\*909\*622#** |
| Canada, USA, Chine, Inde, Royaume Uni | 10 min | 30 jours | 600 FCFA | **\*909\*623#** |
| Arabie Saoudite | 10 min | 30 jours | 1000 FCFA | **\*909\*624#** |

### 6. Forfaits Roaming

| Zone | Volume | Validité | Prix | Code USSD |
|------|--------|----------|------|-----------|
| Bénin | 225 MB | 30 jours | 500 FCFA | **\*909\*61211#** |
| Bénin | 500 MB | 30 jours | 1000 FCFA | **\*909\*61222#** |
| Arabie Saoudite | 500 MB | 30 jours | 7500 FCFA | **\*909\*6123#** |
| Ghana | 370 MB | 30 jours | 5000 FCFA | **\*909\*6124#** |
| Ghana | 1 Go | 30 jours | 1400 FCFA | **\*909\*61231#** |
| Ghana | 4 Go | 30 jours | 5000 FCFA | **\*909\*61232#** |
| Gabon | 500 MB | 30 jours | 7500 FCFA | **\*909\*6125#** |
| Côte d'Ivoire | 225 MB | 30 jours | 500 FCFA | **\*909\*61221#** |
| Côte d'Ivoire | 500 MB | 30 jours | 1000 FCFA | **\*909\*61222#** |

### 7. Services Mixx by Yas (anciennement T-Money)

| Service | Code USSD | Description |
|---------|-----------|-------------|
| Menu principal | **\*145#** | Accéder au menu principal de Mixx by Yas |
| Transfert d'argent | **\*145\*1#** | Transférer de l'argent |
| Retrait d'argent | **\*145\*2#** | Retirer de l'argent |
| Achat de crédit/forfait | **\*145\*3#** | Acheter du crédit ou des forfaits |
| Paiement de factures | **\*145\*4#** | Payer des factures (électricité, eau, TV) |
| Paiement Marchand | **\*145\*5#** | Payer chez un commerçant |
| Menu Selfcare | **\*145\*8#** | Réinitialisation du code secret, récupération des codes LAFIA, etc. |

### 8. Forfaits SoWe

| Forfait | Internet jour | Internet nuit | Bonus voix | Validité | Prix | Code USSD |
|---------|---------------|---------------|------------|----------|------|-----------|
| SoWe 300 | 150 Mo | 150 Mo (22h-5h) | 1200F (22h-5h) | 1 jour | 300 FCFA | **\*909\*8\*1#** |
| SoWe 500 | 250 Mo | 250 Mo (22h-5h) | 2500F (22h-5h) | 2 jours | 500 FCFA | **\*909\*8\*2#** |
| SoWe 1000 | 500 Mo | 500 Mo (22h-5h) | 5000F (22h-5h) | 7 jours | 1000 FCFA | **\*909\*8\*3#** |
| SoWe 3500 | 2048 Mo | 2048 Mo (22h-5h) | 7000F (22h-5h) | 30 jours | 3500 FCFA | **\*909\*8\*4#** |

### 9. Services et divertissements

| Service | Code USSD | Description |
|---------|-----------|-------------|
| SOS Crédit | **\*445#** ou **\*909\*5\*1#** | Emprunter du crédit ou des forfaits |
| Transfert de crédit | **\*909\*5\*2#** | Transférer du crédit à un autre numéro |
| MC+ (Infos et détente) | **\*909\*5\*3#** | Actualités, infos sportives, économiques et culturelles |
| Afreekaplay (Musique) | **\*909\*541#** | Service de streaming musical africain |
| MyZik (Tonalités d'appel) | **\*909\*5\*5#** | Personnaliser sa tonalité d'attente |
| Portail religieux | **\*90956#** | Contenus religieux (christianisme ou islam) |
| Consultation numéro | **\*555#** | Connaître son numéro de téléphone |
| Activation Roaming | **\*909\*611#** | Activer le service Roaming |
| Désactivation Roaming | **\*909\*613#** | Désactiver le service Roaming |
