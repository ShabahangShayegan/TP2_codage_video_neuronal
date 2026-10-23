# TP2 — Neural Video Coding

Projet EPITA sur la compression vidéo neuronale : comparaison de méthodes classiques et neuronales.

## Objectifs
- Étudier le block matching et RAFT.
- Explorer ScaleSpaceFlow.
- Comparer les codecs x265, VVenC, ScaleSpaceFlow et DCVC-RT.
- Évaluer la qualité vidéo, le débit et la complexité.

## Exécution
Le notebook est conçu pour être exécuté sur Google Colab, avec GPU recommandé.

Deux modes sont disponibles :
- **FAST** : exécution rapide pour tester le pipeline.
- **FULL** : expériences complètes.

## Résultats
Les résultats incluent notamment :
- PSNR et débit en bits par pixel (bpp).
- Comparaisons débit-distorsion et BD-rate.
- Temps d'exécution et complexité des méthodes.

Les fichiers générés sont enregistrés dans les répertoires de sortie définis dans le notebook.

## Contenu
Le projet couvre l'estimation de mouvement, la compression vidéo neuronale et la comparaison avec des codecs traditionnels.
