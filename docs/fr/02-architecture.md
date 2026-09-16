# 2. HubPool, SpokePool et gouvernance croisée

Le HubPool conserve la liquidité de référence et sert d’administrateur cross-chain. Les SpokePool reçoivent les dépôts sur les réseaux d’origine ou de destination et sont gouvernés par le HubPool selon le mécanisme de propriété propre à chaque réseau.

Le dépôt décrit les SpokePool comme des proxies UUPS : l’adresse reste stable tandis que l’implémentation peut évoluer si l’administrateur autorisé appelle upgradeTo. Une mise à jour peut être préparée au hub puis exécutée à distance.

Les adaptateurs de chaîne isolent les différences de messagerie, de tokens et de finalité. La séparation entre contrats, scripts, déploiements et stockage permet de suivre la configuration sans confondre le code générique et les variantes réseau.

Suite : [dépôt et remplissage](03-depot-remplissage.md).
