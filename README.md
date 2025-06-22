# Isvalidmove


Objectif
Redéfinir la méthode `isValidMove` dans la classe `Reine` pour valider les mouvements corrects selon les règles du jeu d’échecs.

Fonctionnement
- La reine peut se déplacer horizontalement, verticalement ou en diagonale.
- Utilisation de `super.isValidMove()` pour éviter les doublons et vérifier les règles générales de déplacement.

Exemple
```java
Reine r = new Reine(4, 4);
r.isValidMove(7, 7); // true
r.isValidMove(5, 6); // false
