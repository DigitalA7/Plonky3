# Champs et extensions

Les calculs d'une preuve sont effectués dans un corps fini fourni par les crates `field`, `baby-bear`, `koala-bear`, `goldilocks` ou `mersenne-31`.
Les traits du module `field` définissent les opérations dont les protocoles ont besoin sans imposer une représentation unique.
Les champs d'extension servent notamment à obtenir un espace de défis suffisamment grand pour le niveau de sécurité visé.
Le choix du champ influence les FFT, la vectorisation et le coût des contraintes.
Plonky3 propose aussi des champs binaires et des domaines adaptés à des protocoles multivariés.
Cette abstraction explique pourquoi une configuration STARK assemble plusieurs types génériques.
Une intégration doit conserver la cohérence entre champ de base, champ d'extension et domaine polynomial.

[Chapitre suivant : AIR et contraintes](03-air-et-contraintes.md)
