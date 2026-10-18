# QualiScan — détection et coût des erreurs

Détecter les pièces suspectes en maîtrisant les erreurs et la fuite entre lots.

## Résultats
- 14400 apprentissage, 4780 validation et 4800 test, sans lot commun.
- Seuil sur validation : 0.04 ; AUC test 0.894, rappel 0.964.
- Régression sans étiquette : RMSE 0.549 mm, baseline 0.561 mm.

## Actions
- Conserver le test fermé lors du choix du seuil.
- Soumettre les pièces suspectes à expertise humaine ; surveiller dérive et prévalence.

## Limites
- Simulation physique, aucune capacité démontrée sur de vraies pièces.
- Coût 20:1 conventionnel, à revoir selon risque métier.
- Forêt évaluée séparément, pas de sélection après lecture du test.
- Bootstrap par lot ; régression évaluée sur valeurs observées, hypothèse de manque aléatoire.
