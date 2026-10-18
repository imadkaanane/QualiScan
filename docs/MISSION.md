# Mission

24 000 pièces sont mesurées dans 480 lots de fabrication. Six dimensions physiques et une étiquette de défaut sont disponibles. Certains relevés sont absents ou invalides. Les pièces d’un même lot partagent une dérive ; les erreurs de détection ont des coûts asymétriques.

## Contraintes

- Aucun lot commun aux trois partitions ; aucune sélection du seuil sur le test.
- Pas d’étiquette est_defaut parmi les variables de régression ou de clustering.
- Documenter la classe positive, les dénominateurs et les coûts ; ne pas assimiler AUC et précision.
- Fournir une inférence reproductible sur données synthétiques et ne pas revendiquer une détection opérationnelle réelle.