# Engagements et arbres de Merkle

Le prouveur engage des matrices avant de recevoir les défis qui serviront aux contrôles.
Les interfaces MMCS de `commit` abstraient cet engagement et les ouvertures de lignes.
Le crate `merkle-tree` fournit une construction basée sur un hachage des feuilles puis des nœuds.
Une racine compacte lie le prouveur à l'ensemble de la trace engagée.
Pour une requête, le prouveur fournit les valeurs ouvertes et un chemin d'authentification.
Le choix de Poseidon2, Keccak ou d'un autre hachage modifie les performances et les hypothèses.
La sérialisation et la vérification des dimensions font partie de la surface de sécurité face aux preuves malformées.

[Chapitre suivant : FRI](06-fri-et-faible-degre.md)
