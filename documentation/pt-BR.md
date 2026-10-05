<!-- ELUCENIA technical documentation · h2fpef · pt-BR · no clinical/professional/rights approval -->

# Escore H₂FPEF

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/h2fpef)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Heavy: IMC \> 30 kg/m² (2)

`obesidade`

### Hypertensive: 2 ou mais anti-hipertensivos (1)

`anti`

### Fibrilação atrial paroxística ou persistente (3)

`fa`

### Pulmonar: PSAP \> 35 mmHg no eco (1)

`hp`

### Elder: idade \> 60 anos (1)

`idade`

### Filling: E/e' \> 9 no eco (1)

`ee`

## Edição do método

H 2 FPEF/Reddy 2018:6 fatores,0–9; 2 IMC/3 FA

## Fórmula documentada

Obesidade (IMC \> 30) = 2 · ≥ 2 anti-hipertensivos = 1 · fibrilação atrial = 3 · PSAP \> 35 mmHg = 1 · idade \> 60 = 1 · E/e' \> 9 = 1. Total de 0 a 9.

## Limites e população

O H2FPEF foi desenvolvido em pessoas com dispneia inexplicada encaminhadas para avaliação hemodinâmica invasiva de esforço, comparando ICFEp e causas não cardíacas. O escore auxilia a decidir investigação adicional; não confirma sozinho ICFEp nem deve ser extrapolado automaticamente a toda causa de dispneia. População, fração de ejeção e definições ecocardiográficas precisam corresponder ao método.

## Referências

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
