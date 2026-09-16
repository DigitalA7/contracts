# 2. Presets de tokens

Les presets constituent le point d’entrée le plus direct pour une DApp NFT ou tokenisée. Le dépôt référence notamment ImmutableERC721, ImmutableERC721MintByID, ImmutableERC1155 et plusieurs variantes ERC20.

Ces contrats préconfigurent des comportements attendus par l’écosystème : propriété, mint, supply, permissions, métadonnées et parfois royalties ou allowlist d’opérateurs. Le constructeur reçoit donc des paramètres métier qui doivent être gouvernés par l’application.

Le choix ERC721 ou ERC1155 dépend du modèle d’actifs : pièce unique, série, items fongibles ou semi-fongibles. Les noms des presets rendent cette décision lisible dans le code d’intégration.

[Chapitre suivant : marketplaces et AMM](03-marketplace-amm.md)
