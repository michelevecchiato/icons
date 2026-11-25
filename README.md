# icons

Raccolta di icone grafiche in formato PNG: loghi di social network e servizi di messaggistica in stile uniforme (cerchio blu con simbolo interno), icone di utilità generiche e immagini di profilo.

Repository: https://github.com/michelevecchiato/icons

## Indice

- [Caratteristiche](#caratteristiche)
- [Requisiti](#requisiti)
- [Installazione](#installazione)
- [Configurazione](#configurazione)
- [Opzioni CLI](#opzioni-cli)
- [Esempi d'uso](#esempi-duso)
- [Come funziona](#come-funziona)
- [Output e reportistica](#output-e-reportistica)
- [Struttura del repository](#struttura-del-repository)
- [Risoluzione problemi](#risoluzione-problemi)
- [Autore e contatti](#autore-e-contatti)
- [Licenza](#licenza)

## Caratteristiche

- 17 file immagine in formato PNG, tutti nella radice del repository.
- 9 loghi di social network e app di messaggistica: Facebook, Instagram, LinkedIn, Mastodon, Signal, Telegram, WhatsApp, X e YouTube.
- 4 icone generiche in stile coerente con i loghi (cerchio blu con simbolo interno): distintivo/rosetta, calendario, chiave e simbolo "@" per il Fediverso.
- 3 immagini di profilo (`micheleicon.png`, `micheleicon1.png`, `micheleicon2.png`) e 1 icona aziendale (`timicon.png`).
- Le icone in stile uniforme (cerchio blu con simbolo interno) hanno dimensione 551 x 551 pixel, con le eccezioni elencate nella tabella dei file.
- Distribuzione sotto licenza MIT.

### Elenco dei file

| File | Contenuto | Dimensioni (px) |
|------|-----------|-----------------|
| `logobadge.png` | Distintivo / rosetta | 551 x 551 |
| `logocalendar.png` | Calendario | 551 x 551 |
| `logof.png` | Facebook | 551 x 551 |
| `logofediverse.png` | Simbolo "@" (Fediverso) | 551 x 551 |
| `logoin.png` | LinkedIn | 551 x 551 |
| `logoins.png` | Instagram | 551 x 551 |
| `logokey.png` | Chiave | 551 x 551 |
| `logomastodon.png` | Mastodon | 200 x 200 |
| `logosignal.png` | Signal | 551 x 551 |
| `logotelegram.png` | Telegram | 200 x 200 |
| `logowa.png` | WhatsApp | 551 x 551 |
| `logox.png` | X | 551 x 551 |
| `logoy.png` | YouTube | 551 x 551 |
| `micheleicon.png` | Immagine di profilo (fotografia) | 480 x 401 |
| `micheleicon1.png` | Immagine di profilo (illustrazione) | 480 x 401 |
| `micheleicon2.png` | Immagine di profilo (illustrazione, variante) | 480 x 401 |
| `timicon.png` | Icona TIM | 887 x 741 |

## Requisiti

- Nessun linguaggio di programmazione, runtime o dipendenza software.
- Git, solo se si desidera clonare il repository.
- Un qualsiasi visualizzatore o editor di immagini compatibile con il formato PNG.

## Installazione

Il progetto non richiede installazione: le icone sono file statici. Per ottenerle in locale è sufficiente clonare il repository:

```
git clone https://github.com/michelevecchiato/icons.git
```

In alternativa, è possibile scaricare i singoli file PNG direttamente dalla pagina GitHub del repository.

## Configurazione

Il progetto non prevede file di configurazione, variabili d'ambiente o parametri.

## Opzioni CLI

Il progetto non fornisce alcuno script né interfaccia a riga di comando, quindi non esistono opzioni CLI.

## Esempi d'uso

Inserimento di un'icona in un documento Markdown (percorso relativo al repository):

`![X](logox.png)`

Inserimento in una pagina HTML con dimensione personalizzata:

`<img src="logox.png" alt="X" width="48" height="48">`

Riferimento a un'icona tramite URL diretto al file nel ramo `main`:

`https://raw.githubusercontent.com/michelevecchiato/icons/main/logox.png`

## Come funziona

Il repository contiene esclusivamente file immagine, senza codice sorgente. Ogni file PNG si utilizza così com'è, copiandolo o referenziandolo dove serve (documenti, pagine web, profili, firme email, presentazioni).

Le icone dei loghi e le icone generiche condividono lo stesso stile: cerchio blu con simbolo interno su sfondo chiaro, per ottenere un aspetto coerente quando vengono accostate.

## Output e reportistica

Il progetto non genera alcun output né report: l'unico contenuto sono i file PNG elencati nella sezione "Caratteristiche".

## Struttura del repository

```
icons/
├── LICENSE
├── logobadge.png
├── logocalendar.png
├── logof.png
├── logofediverse.png
├── logoin.png
├── logoins.png
├── logokey.png
├── logomastodon.png
├── logosignal.png
├── logotelegram.png
├── logowa.png
├── logox.png
├── logoy.png
├── micheleicon.png
├── micheleicon1.png
├── micheleicon2.png
└── timicon.png
```

## Risoluzione problemi

| Problema | Possibile causa | Soluzione |
|----------|-----------------|-----------|
| L'immagine non viene mostrata in Markdown | Percorso o nome file errato | Verificare che il nome corrisponda esattamente a quello del file (es. `logox.png`), rispettando le minuscole |
| Il file scaricato dalla pagina GitHub non si apre | È stata salvata la pagina HTML invece dell'immagine | Usare il pulsante di download del file oppure l'URL `raw.githubusercontent.com` |
| `logomastodon.png` e `logotelegram.png` risultano meno nitide delle altre | Hanno dimensione 200 x 200 pixel, inferiore ai 551 x 551 delle altre icone | Usarle a dimensioni contenute |
| Le icone appaiono sfocate dopo un ingrandimento | Sono immagini raster (PNG), non vettoriali | Usarle alle dimensioni originali o inferiori |

## Autore e contatti

- Autore: Michele Vecchiato
- GitHub: https://github.com/michelevecchiato
- Email: michele.vecchiato@gmail.com

## Licenza

Distribuito sotto licenza MIT. Copyright (c) 2026 Michele Vecchiato. Il testo completo è nel file `LICENSE`.