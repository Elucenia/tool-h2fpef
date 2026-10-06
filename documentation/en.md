<!-- ELUCENIA technical documentation · h2fpef · en · no clinical/professional/rights approval -->

# H₂FPEF score

[conditions, sources and permissions](https://elucenia.org/en/tools/h2fpef)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Heavy: BMI \> 30 kg/m² (2)

`obesidade`

### Hypertensive: 2 or more antihypertensives (1)

`anti`

### Fibrillation: paroxysmal or persistent atrial fibrillation (3)

`fa`

### Pulmonary: pulmonary artery systolic pressure \> 35 mmHg on echocardiography (1)

`hp`

### Elder: age \> 60 years (1)

`idade`

### Filling: E/e' \> 9 on echocardiography (1)

`ee`

## Method edition

H2FPEF/Reddy 2018: 6 factors, 0–9; 2 for BMI/3 for AF

## Documented formula

Obesity (BMI \> 30) = 2 · ≥ 2 antihypertensives = 1 · atrial fibrillation = 3 · PASP \> 35 mmHg = 1 · age \> 60 = 1 · E/e' \> 9 = 1. Total 0 to 9.

## Limits and population

H2FPEF was developed in people with unexplained dyspnea referred for invasive exercise hemodynamic assessment, comparing HFpEF with noncardiac causes. The score helps decide on further investigation; it does not alone confirm HFpEF and must not be automatically extrapolated to every cause of dyspnea. Population, ejection fraction and echocardiographic definitions must match the method.

## References

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Low probability of HFpEF (0 to 1)

Investigate non-cardiac causes of dyspnea.


### 2

Intermediate probability (2 to 5)

Complement with stress echocardiography (diastolic) or exercise catheterization; natriuretic peptides help.


### 3

Intermediate probability (2 to 5)

Complement with stress echocardiography (diastolic) or exercise catheterization; natriuretic peptides help.


### 4

High probability of HFpEF (6 to 9)

HFpEF likely: treat and investigate specific etiologies (amyloidosis, hypertrophic cardiomyopathy).

