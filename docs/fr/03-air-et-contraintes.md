# AIR et contraintes

Une AIR décrit les relations algébriques que chaque ligne de la trace doit respecter.
Le trait `Air` reçoit un constructeur qui expose les valeurs locales, les valeurs suivantes et les variables publiques.
Les contraintes de transition relient deux lignes consécutives, tandis que les contraintes de bord fixent des conditions initiales ou finales.
Les sélecteurs permettent de n'activer une relation que sur certaines lignes.
Les exemples SHA-256, Keccak et Poseidon montrent comment une primitive est traduite en colonnes et relations polynomiales.
Le prouveur évalue ces relations sur la trace ; le vérificateur contrôle ensuite leur composition à des points aléatoires.
Une contrainte oubliée peut accepter une exécution invalide même si le programme natif paraît correct.

[Chapitre suivant : trace d'exécution](04-trace-execution.md)
