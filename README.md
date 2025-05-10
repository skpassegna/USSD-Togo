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

### 7. Forfaits Internet 4G (Journalier et hebdomadaire)

| Forfait | Volume | Validité | Prix | Code USSD |
|---------|--------|----------|------|-----------|
| iZi'Free | 50 Mo | 1 Jour | 100 F | **\*400\*2\*1\*1#** |
| iZi'Cool | 120 Mo | 1 Jour | 200 F | **\*400\*2\*1\*2#** |
| iZi'Wik | 1,5 Go | 7 Jours | 1 000 F | **\*400\*2\*1\*3#** |
| iZi'Relax | 400 Mo | 3 Jours | 500 F | **\*400\*2\*1\*4#** |
| iZi'Kif | 180 Mo | 3 Jours | 300 F | **\*400\*2\*1\*5#** |
| iZi'Wik Plus | 4 Go | 7 Jours | 1 500 F | **\*400\*2\*1#** option 6 |
| iZi'Moon | 4 Go | 1 Nuit (22h-7h) | 500 F | **\*400\*2\*3\*1#** |
| Consultation solde Internet | - | - | - | **\*400\*4#** |
| Consultation solde iZi'Moon | - | - | - | **\*400\*2\*3\*3#** |

### 8. Forfaits Internet 4G (hebdomadaire/mensuel)

| Forfait | Volume | Validité | Prix | Code USSD |
|---------|--------|----------|------|-----------|
| iZi'Small 1 | 6 Go | 10 jours | 2 500 F | **\*400\*2\*2\*1#** |
| iZi'Small 2 | 6 Go | 30 jours | 4 500 F | **\*400\*2\*2\*2#** |
| iZi'Medium 1 | 15 Go | 15 jours | 5 000 F | **\*400\*2\*2\*3#** |
| iZi'Medium 2 | 30 Go | 30 jours | 9 000 F | **\*400\*2\*2\*4#** |
| iZi'Large | 75 Go | 30 jours | 15 000 F | **\*400\*2\*2\*5#** |

## Yas Togo (anciennement Togocom / Togocel / Togo Telecom)
[Site Officiel](https://yas.tg)

_Note: Les codes USSD pour Yas Togo seront mis à jour prochainement._
