# Preuve, vérification et limites

`p3-uni-stark` combine les contraintes AIR, les engagements, la composition polynomiale et les ouvertures PCS.
Le prouveur produit une preuve à partir de la configuration, de la trace et des valeurs publiques.
Le vérificateur reconstruit la transcription, contrôle les engagements et refuse les relations incohérentes.
Le README amont avertit que certaines preuves malformées peuvent provoquer un panic ; une intégration exposée doit donc isoler cette surface.
Ce parcours ne couvre pas les preuves multivariées, STIR, WHIR, Sumcheck ni toutes les optimisations SIMD du dépôt.
Il s'agit d'une lecture documentaire du code : aucune installation, compilation ou exécution nouvelle n'a été réalisée.
La suite de tests et `scripts/check.py` constituent les références pour vérifier une modification technique.

[Retour au sommaire](README.md)
