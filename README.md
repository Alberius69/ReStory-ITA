# ReStory — Traduzione Italiana

Traduzione italiana completa di **ReStory: Chill Electronics Repairs** con installer/manager dedicato.

## Stato

- **Versione traduzione:** 1.0
- **Steam AppID:** 3812600
- **BuildID supportata:** 26253677
- **Piattaforma:** Windows x64
- **Stato:** Release finale 1.0

> **Importante:** la traduzione supporta esclusivamente la BuildID `26253677`. Se Steam aggiorna ReStory e la BuildID cambia, il manager blocca automaticamente l'installazione.

## Download

Scarica l'ultima versione dalla sezione **Releases** di questo repository.

File:

`ReStory_ITA_1.0_Build_26253677.zip`

SHA256:

`8D3DF4FEC827D077A9259620C4472EF2D561093B629683DD254CEC12CE92E950`

Manager `ReStory_ITA.exe` SHA256:

`1D2EDBEB45CA51ACEEE9037E71D7549F55DEADAFE3C07ED8EC50E4A61BEE2915`

## Cosa traduce

La versione 1.0 comprende la localizzazione italiana di:

- interfaccia e menu;
- impostazioni;
- dialoghi;
- missioni;
- ordini e marketplace;
- email e messaggi;
- descrizioni degli oggetti;
- componenti e strumenti di riparazione;
- obiettivi e notifiche;
- contenuti introdotti dagli aggiornamenti recenti;
- missione Patento;
- contenuti e missione Steam Deck.

L'audio originale rimane invariato.

## Installazione

1. Scarica `ReStory_ITA_1.0_Build_26253677.zip` dalla sezione **Releases**.
2. Estrai completamente lo ZIP in una cartella.
3. Assicurati che ReStory sia chiuso.
4. Avvia `ReStory_ITA.exe`.
5. Seleziona **Installa traduzione**.

Il manager:

- rileva automaticamente le librerie Steam;
- verifica la BuildID del gioco;
- verifica gli hash SHA256 dei file originali;
- verifica l'integrità delle patch;
- crea un backup locale prima dell'installazione;
- applica patch binarie differenziali;
- verifica gli hash finali;
- lascia `catalog.hash` invariato;
- rifiuta l'installazione su build non supportate.

## Disinstallazione

Avvia nuovamente `ReStory_ITA.exe` e scegli **Ripristina originale**.

Il manager ricostruisce e verifica automaticamente i file originali tramite patch inverse.

## Sicurezza della distribuzione

La release contiene esclusivamente patch differenziali e il manager.

Non vengono distribuiti:

- `resources.assets` originale completo;
- `catalog.bin` originale completo;
- bundle originale della storia;
- backup dei file originali del gioco.

## QA della versione 1.0

La release finale ha superato:

- Coverage linguistica: **PASS**
- Placeholder/tag: **PASS**
- Rebuild binario: **PASS**
- Addressables/catalog: **PASS**
- Runtime QA oltre 60 minuti: **PASS**
- Nuova partita: **PASS**
- Salvataggio avanzato: **PASS**
- Save/Load: **PASS**
- Missione Patento: **PASS**
- Missione Steam Deck: **PASS**
- Installazione tramite manager: **PASS**
- Disinstallazione tramite manager: **PASS**
- Reinstallazione: **PASS**
- Crash/blocchi nel QA finale: **0**

## Aggiornamenti del gioco

Se Steam aggiorna ReStory e cambia la BuildID, **non forzare l'installazione**.

Una nuova versione della traduzione verrà pubblicata dopo la verifica della nuova build.

## Changelog

Consulta [`CHANGELOG.md`](CHANGELOG.md).

## Crediti

Progetto indipendente di localizzazione italiana di **ReStory: Chill Electronics Repairs**.

La distribuzione utilizza patch binarie differenziali. Le informazioni sulle dipendenze di terze parti sono incluse nel pacchetto di release.
