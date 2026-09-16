# 5. Upgradeabilité, sécurité et limites

Les contrats Across combinent plusieurs environnements : EVM, variantes de chaînes, composants Rust et programme SVM. Les contrôles d’administration, les adaptateurs et la gestion des layouts de stockage sont donc des éléments centraux du périmètre de sécurité.

Les SpokePool étant upgradeables, l’identité de l’administrateur et la construction des messages d’exécution cross-chain doivent être suivies avec soin. Les délais de dépôt, de remplissage et de contestation protègent les transitions, mais ne remplacent pas la qualité des relayers ni des composants de messagerie.

Ce parcours décrit l’architecture, les flux de dépôt, le règlement Merkle et les garde-fous visibles dans le code. Il ne déclare aucun test exécuté : les suites présentes dans test/ constituent la référence pour une vérification ultérieure.

Fin du parcours.
