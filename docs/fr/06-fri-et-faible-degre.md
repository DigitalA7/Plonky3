# FRI et test de faible degré

FRI sert à convaincre que les valeurs engagées correspondent à un polynôme de degré suffisamment faible.
Le protocole replie successivement le domaine en combinant des valeurs avec des défis aléatoires.
Chaque tour réduit la taille du problème jusqu'à un polynôme final contrôlable directement.
Le vérificateur ouvre seulement un échantillon de positions et vérifie leur cohérence entre les couches.
Le facteur d'expansion, le nombre de requêtes et la stratégie de réduction déterminent coût et sécurité.
Dans Plonky3, la couche PCS relie FRI aux engagements de matrices et aux ouvertures demandées par le STARK.
Des paramètres incohérents peuvent donner une preuve rapide mais une marge de sécurité insuffisante.

[Chapitre suivant : Fiat-Shamir](07-fiat-shamir-et-challenger.md)
