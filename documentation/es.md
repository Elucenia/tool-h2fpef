<!-- ELUCENIA technical documentation · h2fpef · es · no clinical/professional/rights approval -->

# Puntuación H₂FPEF

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/h2fpef)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Heavy: IMC \> 30 kg/m² (2)

`obesidade`

### Hypertensive: 2 o más antihipertensivos (1)

`anti`

### Fibrilación auricular paroxística o persistente (3)

`fa`

### Pulmonar: presión sistólica de la arteria pulmonar \> 35 mmHg en el ecocardiograma (1)

`hp`

### Elder: edad \> 60 años (1)

`idade`

### Filling: E/e' \> 9 en el ecocardiograma (1)

`ee`

## Edición del método

H2FPEF/Reddy 2018: 6 factores, 0–9; 2 IMC/3 FA

## Fórmula documentada

Obesidad (IMC \> 30) = 2 · ≥ 2 antihipertensivos = 1 · fibrilación auricular = 3 · PSAP \> 35 mmHg = 1 · edad \> 60 = 1 · E/e' \> 9 = 1. Total de 0 a 9.

## Límites y población

El H2FPEF se desarrolló en personas con disnea inexplicada remitidas para evaluación hemodinámica invasiva de esfuerzo, comparando IC con fracción de eyección preservada y causas no cardíacas. La puntuación ayuda a decidir investigaciones adicionales; no confirma por sí sola esa insuficiencia cardíaca ni debe extrapolarse automáticamente a todas las causas de disnea. La población, la fracción de eyección y las definiciones ecocardiográficas deben corresponder al método.

## Referencias

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Baja probabilidad de ICFEp (0 a 1)

Investigar causas no cardíacas de la disnea.


### 2

Probabilidad intermedia (2 a 5)

Complementar con ecocardiograma de esfuerzo (diastólico) o cateterismo con ejercicio; los péptidos natriuréticos ayudan.


### 3

Probabilidad intermedia (2 a 5)

Complementar con ecocardiograma de esfuerzo (diastólico) o cateterismo con ejercicio; los péptidos natriuréticos ayudan.


### 4

Alta probabilidad de ICFEp (6 a 9)

ICFEp probable: tratar e investigar etiologías específicas (amiloidosis, miocardiopatía hipertrófica).

