# 5. ABIs et intégration TypeScript

Le package expose des ABIs TypeScript pour créer des clients avec viem ou wagmi. Les exports mentionnés dans le README couvrent notamment ImmutableERC721, ImmutableERC721MintById, ImmutableERC1155, GuardedMulticaller2 et PaymentSplitter.

Des constantes d’adresses déployées, comme IMMUTABLE_SEAPORT et CHAIN_ID, complètent cette surface d’intégration. Elles réduisent les erreurs de configuration mais doivent toujours être rapprochées du réseau choisi.

La version 3 change la surface npm : noms d’ABIs, organisation du package et absence de clients ethers ou de typechain embarqués. Une migration doit donc être traitée comme une rupture contrôlée et non comme une simple mise à jour.

[Chapitre suivant : sécurité et limites](06-securite-limites.md)
