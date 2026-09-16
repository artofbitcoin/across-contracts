# 3. Dépôt, cotation et remplissage

Un utilisateur initie un dépôt sur un SpokePool avec un actif, une destination, un bénéficiaire et des paramètres de délai. Le dépôt émet les informations nécessaires pour qu’un relayer puisse proposer un remplissage sur le réseau cible.

Le relayer avance l’actif de destination et reçoit le droit économique de récupérer les fonds correspondants lors du règlement. Les frais et la tolérance de prix sont intégrés dans les paramètres signés afin que le remplissage respecte le devis accepté.

Les fonctions de dépôt et de remplissage vérifient les deadlines, les montants, les tokens et l’unicité de l’opération. Les événements servent ensuite à reconstruire le parcours depuis la demande initiale jusqu’au règlement.

Suite : [lots, racines et règlement](04-reglement.md).
