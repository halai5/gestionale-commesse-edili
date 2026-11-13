# Gestionale Commesse

Applicazione web per il controllo di **commesse e cantieri edili**: budget, costi, avanzamento lavori, rendicontazione giornaliera, clienti, fatture e incassi, con vista su mappa. Realizzata con [Base44](https://base44.com).

> Questo repository contiene la **documentazione e gli screenshot** dell'applicazione. Non include il codice sorgente. Tutti i dati mostrati sono esempi fittizi e i riferimenti all'azienda sono stati rimossi.

## Funzionalità

- **Dashboard**: commesse attive, budget in gestione, costi dell'anno, commesse in sforo, fatturato, importi da incassare e scaduti; grafico delle commesse per stato, costi per categoria e prossime scadenze dei lavori.
- **Mappa commesse**: tutti i cantieri su mappa interattiva o in elenco, con filtri per stato, cliente, data e responsabile.
- **Nuova commessa**: form con nome, codice, cliente, indirizzo strutturato (via, civico, città, CAP) con geolocalizzazione, descrizione lavori, date, responsabile, stato, tipologia e budget.
- **Scheda commessa**: indicatori economici (preventivo, budget, costi sostenuti, margine residuo, consumo budget, fatturato), grafici budget contro costi per categoria e costi cumulati, meteo del cantiere a 5 giorni e sei schede di dettaglio:
  - *Riepilogo*: giorni lavorati, ore, addetti medi, margine e avanzamento di fasi, costi e tempi;
  - *Costi*: elenco dei costi per data, categoria, fornitore e importo;
  - *Fasi*: fasi di lavorazione con data e stato (da iniziare, in corso, completata) e percentuale di avanzamento;
  - *Rendicontazione*: registro giornaliero di addetti, ore e attività svolte;
  - *Documenti* e *Fatture* collegati alla commessa.
- **Clienti**: anagrafica dei committenti, aziende o privati.
- **Fatture e incassi**: elenco fatture con stato (incassata, parzialmente incassata, scaduta) e vista *Aging crediti* per fasce di ritardo.
- **Riepilogo commesse**: confronto tra tutte le commesse, con budget, costi, margine e avanzamento.
- **Funzioni intelligenti**: inserimento dei costi da foto di fattura o scontrino, confronto delle foto del cantiere nel tempo, previsioni meteo per cantiere.

## Screenshot

| | |
|---|---|
| ![Dashboard](screenshots/01-dashboard.png) **Dashboard** | ![Mappa commesse](screenshots/02-mappa-commesse-lista.png) **Mappa commesse (vista elenco)** |
| ![Clienti](screenshots/03-clienti.png) **Clienti** | ![Fatture e incassi](screenshots/04-fatture-e-incassi.png) **Fatture e incassi** |
| ![Aging crediti](screenshots/05-aging-crediti.png) **Aging crediti** | ![Riepilogo commesse](screenshots/06-riepilogo-commesse.png) **Riepilogo commesse** |
| ![Scheda commessa](screenshots/08-scheda-commessa.png) **Scheda commessa** | ![Grafici](screenshots/09-scheda-grafici.png) **Grafici della scheda** |
| ![Riepilogo scheda](screenshots/10-scheda-riepilogo.png) **Meteo e riepilogo** | ![Costi](screenshots/11-scheda-costi.png) **Costi sostenuti** |
| ![Fasi](screenshots/12-scheda-fasi.png) **Fasi di lavorazione** | ![Rendicontazione](screenshots/13-scheda-rendicontazione.png) **Rendicontazione giornaliera** |
| ![Nuova commessa](screenshots/14-nuova-commessa.png) **Nuova commessa** | ![Guida](screenshots/07-guida.png) **Guida integrata** |

## Tecnologia

Applicazione creata e pubblicata con Base44 (frontend React, backend e database gestiti dalla piattaforma).

## Note

Gli screenshot sono stati ritoccati per rimuovere logo, nome dell'azienda, codici interni e dati di contatto. I nomi di clienti, fornitori e cantieri che compaiono sono esempi fittizi.
