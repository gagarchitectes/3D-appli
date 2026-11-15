# GAGA Geometry Engine V1 — Test iPhone

Branche isolée : `feature/gaga-geometry-engine-v1`. Aucun changement sur `main`.

## Ouvrir le prototype dans Safari

[Ouvrir GAGA Geometry Engine V1](https://raw.githack.com/gagarchitectes/3D-appli/feature/gaga-geometry-engine-v1/engine-v1.html)

Le lien utilise le service tiers RawGitHack (prévisualisation HTML depuis un dépôt public GitHub). Il ne constitue pas un déploiement GitHub Pages, et sa disponibilité n'est pas garantie.

## Tests à réaliser

1. Ouvrir le lien dans Safari sur iPhone.
2. Vérifier que le modèle A présente 175 commerces et que les contrôles de surface passent.
3. Faire tourner la vue 3D au doigt et zoomer avec deux doigts.
4. Modifier hauteur d'égout, faîtage et débord; activer la toiture.
5. Masquer/afficher P01, puis essayer « Tout cacher » et « Tout voir ».
6. Passer au concept B et ajuster la largeur de la bande vitrée.
7. Tester l'export JSON puis GLB dans l'app Fichiers.

## Limites

- Le moteur ne lance pas des scripts Rhino Python génériques.
- Pas encore de création ou de sauvegarde de GH / GHX.
- Toitures = surfaces schématiques sans épaisseur.
- Aucune implantation DWG ni conformité réglementaire validée.
- Le lien tiers ne doit pas être utilisé pour des documents ou modèles confidentiels.
- La présence du code dans GitHub a été vérifiée, mais le comportement dans Safari nécessite un essai réel.
