[[OCP-1]]
#OCP1 
	IDENTIFICATION DU CONTRAT :
		COnditions d'existence de contrats :
			capacite
			consentement
			objet licite dans le commerce
			contrepartie approuver par les deux parties
			probabiliter de recouverement
	IDENTIFICATION DES OBLIGATIONS DE PERFORMANCE :
		Promesse de livrer des biens
		Comptabilisation distinctes des beins et des livraisons
	DETERMINATION DES PRIX 
		Significant financing components : la partie financement est mise a part
		Partie variable par rapport a une utilisation du service a part le prix 
	PRIX DE TRANSACTION SUR LES OBLIGATIONS DE PERFORMANCES: 
		Prix est baser a la performance separer des obligations 
	RECOGNITION OF REVENUE : 
		Terme de transfert de propriete : quand est ce qu'il nous appartient 
Credit Bail 2025-08-21 09:42

Comptabilisation de la location financement selon IAS 17/PCG 2005
Preneur :

| Debit | Credit | Libelle                                           |
| ----- | ------ | ------------------------------------------------- |
|       |        | A la signature du contrat                         |
| 2     |        | Droit d'utilisation                               |
|       | 16     | Emrpunts et dettes assimiles                      |
|       |        | Remboursement K ou Paiement des loyers du contrat |
| 16    |        | Remboursement ou Loyer                            |
| 66    |        | Charges Financieres                               |
|       | 512    | Banque                                            |
|       |        | Amortissement de l'actif (droit d'utilisation)    |
| 68    |        |                                                   |
|       | 28     | Droit d'utilisation                               |

Bailleur

| Debit | Credit | Libelle                                        |
| ----- | ------ | ---------------------------------------------- |
|       |        | A la signature du contrat                      |
| 27    |        | Prets                                          |
|       | 2XX    | Immobililsation offert en location-financement |
|       |        | Remboursement Capital ou Loyer                 |
| 5xxx  |        |                                                |
|       | 27     | Capital                                        |
|       | 76     | Produits Financier                             |

Taux Implicite du contrat : 
Duree contrat
Amortissement
Versement Annuel 
Option achat

> TAUX IMPLICITE :
> $V0 = VA* (1-(1+I)^-N)/I + OPTIONACHAT(1+I)^-N$
[[Retour sur Mathematiques Financieres]]
Calcul en utilisant une interpollation lineaire : 
Si le guess < V0 alors le taux est trop eleve
Si le Guess > V0 alors le taux est trop bas 

Interpollation lINEAIRE : 
$I-I1/I2-I1 = V0-V1/V2-V1$
$I = I1 + (V0-VA/V2-V1) * I2-I1$

