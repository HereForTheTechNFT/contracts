# Hop Protocol : architecture

Les contrats L1 et L2 partagent une base de bridge et une comptabilité des crédits et débits des bonders. Les implémentations spécialisées adaptent ensuite les messages et la finalisation aux rollups ciblés.

Les AMM relient le hToken au token canonique de chaque réseau. Le bonder fournit la liquidité avancée à l’arrivée, tandis que les racines de transferts regroupent les opérations avant leur confirmation sur Ethereum.

Cette séparation rend visibles les responsabilités : bridge pour les transferts, token pour la représentation, AMM pour la conversion et gouvernance pour les paramètres.

[Chapitre suivant : transferts et règlement](03-transferts-reglement.md)
