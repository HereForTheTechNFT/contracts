# Hop Protocol : transferts et règlement

Un utilisateur peut envoyer un actif depuis L1 ou une L2, puis demander une conversion et un envoi vers la chaîne cible. Sur le chemin rapide, un bonder appelle le retrait sur la destination et avance les fonds.

Les transferts sont regroupés en TransferRoot. Le bonder engage une garantie, les messages de la chaîne d’origine sont relayés, puis la racine est confirmée après la période de finalité. La comptabilité restaure alors le crédit du bonder.

Toute personne peut contester une racine en immobilisant une mise. Le mécanisme récompense une contestation correcte et protège le système contre une racine invalide.

[Chapitre suivant : limites](04-limites.md)
