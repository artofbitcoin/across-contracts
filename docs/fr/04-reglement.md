# 4. Lots, racines Merkle et règlement

Across regroupe les remplissages dans des lots. Une racine Merkle représente les remboursements ou les états proposés par l’administration du protocole. Les contrats stockent la racine et permettent à un appelant de fournir une preuve pour retirer ce qui lui est dû.

Le HubPool conserve les références des racines et applique les fenêtres de contestation prévues par le protocole. Les bibliothèques Merkle et les tests associés montrent comment les feuilles sont encodées et comment la preuve est vérifiée.

Ce modèle dissocie l’exécution rapide sur les SpokePool du règlement global. La sécurité dépend de l’exactitude des feuilles, de la synchronisation des chaînes et du respect des délais avant exécution.

Suite : [upgradeabilité, sécurité et limites](05-securite-limites.md).
