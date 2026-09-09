# Fiat–Shamir et challenger

Le challenger transforme l'interaction entre prouveur et vérificateur en une transcription non interactive.
Chaque engagement et donnée publique est observé avant de tirer le défi suivant.
Cet ordre empêche le prouveur d'adapter rétroactivement une valeur déjà engagée.
Les crates `challenger` et `symmetric` séparent la logique de transcription de la permutation cryptographique.
Les configurations peuvent employer Poseidon, Poseidon2 ou une construction de type duplex adaptée au champ.
Le prouveur et le vérificateur doivent absorber exactement les mêmes éléments, dans le même ordre et avec le même encodage.
Toute divergence de domaine ou omission dans la transcription fragilise la propriété Fiat–Shamir.

[Chapitre suivant : preuve et vérification](08-preuve-verification-limites.md)
