<!-- ELUCENIA technical documentation · h2fpef · fr · no clinical/professional/rights approval -->

# Score H₂FPEF

[conditions, sources et autorisations](https://elucenia.org/fr/outils/h2fpef)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Heavy : IMC \> 30 kg/m² (2)

`obesidade`

### Hypertensive : au moins 2 antihypertenseurs (1)

`anti`

### Fibrillation atriale paroxystique ou persistante (3)

`fa`

### Pulmonaire : pression artérielle pulmonaire systolique \> 35 mmHg à l’échocardiographie (1)

`hp`

### Elder : âge \> 60 ans (1)

`idade`

### Filling : E/e' \> 9 à l’échocardiographie (1)

`ee`

## Édition de la méthode

H2FPEF/Reddy 2018 : 6 facteurs, 0–9 ; 2 IMC/3 FA

## Formule documentée

Obésité (IMC \> 30) = 2 · ≥ 2 antihypertenseurs = 1 · fibrillation atriale = 3 · PAPS \> 35 mmHg = 1 · âge \> 60 = 1 · E/e' \> 9 = 1. Total de 0 à 9.

## Limites et population

Le H2FPEF a été développé chez des personnes ayant une dyspnée inexpliquée adressées pour une évaluation hémodynamique invasive à l’effort, comparant l’insuffisance cardiaque à fraction d’éjection préservée aux causes non cardiaques. Le score aide à décider d’investigations supplémentaires ; il ne confirme pas seul cette insuffisance cardiaque et ne doit pas être automatiquement extrapolé à toute cause de dyspnée. La population, la fraction d’éjection et les définitions échocardiographiques doivent correspondre à la méthode.

## Références

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
