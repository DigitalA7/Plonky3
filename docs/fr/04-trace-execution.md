# Trace d'exécution

La trace est une matrice : les lignes représentent le temps et les colonnes représentent l'état nécessaire aux contraintes.
Les modules `matrix` fournissent des vues denses, transposées ou tronquées utilisées sans figer le stockage.
La génération de trace doit produire exactement les témoins attendus par l'AIR.
Le remplissage jusqu'à une taille de domaine valide doit rester compatible avec les sélecteurs de bord et de transition.
Les colonnes auxiliaires rendent explicites des calculs qui seraient coûteux à contraindre directement.
Les entrées publiques ne doivent pas être confondues avec les colonnes privées de la trace.
Dans un système zero knowledge, le masquage de la trace ou du protocole d'ouverture doit empêcher les fuites du témoin.

[Chapitre suivant : engagements Merkle](05-engagements-merkle.md)
