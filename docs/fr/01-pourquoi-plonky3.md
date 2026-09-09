# Plonky3 et les preuves STARK

Plonky3 est une boîte à outils Rust pour construire des IOP polynomiaux, principalement des zkVM fondées sur les STARK.
Le dépôt sépare les champs, transformations, engagements, transcriptions et protocoles afin de rendre chaque choix remplaçable.
Le crate `p3-uni-stark` assemble ces briques autour d'une AIR et d'une trace d'exécution.
Cette modularité permet de comparer plusieurs champs, fonctions de hachage et schémas d'engagement.
Un STARK ne dépend pas d'une cérémonie de confiance, mais sa sécurité dépend étroitement des paramètres choisis.
Le parcours suit le chemin des données depuis la trace jusqu'à la vérification.
Il décrit le comportement visible dans le code sans prétendre valider ses garanties cryptographiques.

[Chapitre suivant : champs et extensions](02-champs-et-extensions.md)
