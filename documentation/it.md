<!-- ELUCENIA technical documentation · h2fpef · it · no clinical/professional/rights approval -->

# Punteggio H₂FPEF

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/h2fpef)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Heavy: IMC \> 30 kg/m² (2)

`obesidade`

### Hypertensive: 2 o più antipertensivi (1)

`anti`

### Fibrillazione atriale parossistica o persistente (3)

`fa`

### Polmonare: pressione arteriosa polmonare sistolica \> 35 mmHg all’ecocardiogramma (1)

`hp`

### Elder: età \> 60 anni (1)

`idade`

### Filling: E/e' \> 9 all’ecocardiogramma (1)

`ee`

## Edizione del metodo

H2FPEF/Reddy 2018: 6 fattori, 0–9; 2 IMC/3 FA

## Formula documentata

Obesità (IMC \> 30) = 2 · ≥ 2 antipertensivi = 1 · fibrillazione atriale = 3 · PAPs \> 35 mmHg = 1 · età \> 60 = 1 · E/e' \> 9 = 1. Totale da 0 a 9.

## Limiti e popolazione

L’H2FPEF è stato sviluppato in persone con dispnea inspiegata inviate per valutazione emodinamica invasiva da sforzo, confrontando lo scompenso cardiaco con frazione di eiezione preservata e le cause non cardiache. Il punteggio aiuta a decidere ulteriori indagini; da solo non conferma tale scompenso e non deve essere estrapolato automaticamente a ogni causa di dispnea. Popolazione, frazione di eiezione e definizioni ecocardiografiche devono corrispondere al metodo.

## Riferimenti

- [Reddy YNV et al. A simple, evidence-based approach to help guide diagnosis of heart failure with preserved ejection fraction. Circulation, 2018.](https://doi.org/10.1161/CIRCULATIONAHA.118.034646)

- [McDonagh TA et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. Eur Heart J, 2021.](https://doi.org/10.1093/eurheartj/ehab368)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
