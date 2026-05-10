---
template: home.html
title: Artiglieria
---

# Supporto di fuoco da artiglieria

In questo documento vengono riassunte le procedure per chiamare, con precisione e sicurezza, una missione di fuoco d'artiglieria (quindi non eseguita da ala rotante né ala statica, ma obici, e mortai).

## La richiesta (Call for Fire)

La richiesta per supporto di artiglieria (in inglese "Call for fire") viene tramessa dall'osservatore (colui che richiede supporto) all'elemento che coordina il fuoco di artiglieria.

Generalmente, l'osservatore può essere un operatore designato specificatamente in missione per ricoprire questo ruolo (si parla in questo caso di "Forward Observer"), ma può accadere anche che sia una figura di comando (Team Leader, Squad Leader), oppure un RTO.<br>
Qualora, per qualsiasi motivo (come la distanza) l'osservatore non riuscisse a comunicare con chi coordina il fuoco di artiglieria, se ne occuperà il suo superiore o altra figura designata al momento.

L'elemento che effettua il fuoco di artiglieria è il FDC (Fire Direction Center), che solitamente coincide in missione con il leader a capo di uno o più mortai/obici/lanciarazzi.

La chiamata è composta da 6 elementi:

1. Identificazione dell'osservatore
2. WARNO (Warning Order), che riassume il tipo di ingaggio che stiamo richiedendo
3. Posizione del bersaglio
4. Descrizione del bersaglio
5. Metodo d'ingaggio
6. Controllo/Remarks

<!-- precedente elenco e successivo blocco di testo da ripensare, sembrano un po' ridondanti visto che nella prossima sezione vengono spiegati nel dettaglio -->
Similmente a quanto accade fra JTAC e Pilota per le richieste CAS, così FO ed FDC si coordinano per elaborare la richiesta e supportare le unità con fuoco di artiglieria.<br>
Ogni qual volta che il FO comunica, il FDC risponde con un readback per verificare che le informazioni comprese siano corrette.
Una volta sparati i colpi, il FDC comunica al FO il momento dell'impatto dei colpi con **"SPLASH"**. Il FO comunica poi i danni della salva di artiglieria al FDC, chiedendo correzioni o confermando la neutralizzazione del bersaglio.

## Elementi della Call for Fire nel dettaglio

### 1 - Identificazione dell'osservatore

Il FO chiama il FDC e si identifica con il suo callsign (o altro metodo di identificazione in missione), prima di procedere con la richiesta.

### 2 - WARNO

Il WARNO può essere di due tipi:

- ^^ADJUST FIRE^^ quando l'osservatore stima che serviranno diversi colpi prima di centrare il bersaglio, richiedendo aggiustamenti del tiro;
- ^^FIRE FOR EFFECT^^ quando le coordinate sono precise e ci si aspetta che la salva di colpi abbia effetto senza necessità di aggiustamenti.

!!! note
    Nella dottrina militare USA esistono anche le altri tipo di WARNO come SUPPRESSION, IMMEDIATE SUPPRESSION, IMMEDIATE SMOKE, che nelle nostre partite di Arma rimangono però di limitato utilizzo. Per approfondire potete leggere questo [manuale USA](https://www.marines.mil/Portals/1/Publications/FM%206-30.pdf).

### 3 - Posizione del bersaglio

La posizione del bersaglio può essere comunicata in modi diversi dal FO al FDC.

Come convenzione preferiamo sempre utilizzare le coordinate della griglia in mappa di gioco, la minima precisione accettabile è la 6 digit grid, es: 1-2-3, 4-5-6.

!!! note
    Nella dottrina militare USA si utilizzano anche altri modi per comunicare la posizione dei bersagli, come il POLAR o SHIFT FROM A KNOWN POINT, che nelle nostre partite di Arma rimangono però di limitato utilizzo. Per approfondire potete leggere questo [manuale USA](https://www.marines.mil/Portals/1/Publications/FM%206-30.pdf).

### 4 - Descrizione del bersaglio

La descrizione del bersaglio include cosa è il bersaglio, cosa sta facendo, se dispone di coperture, di quante unità è composto e ulteriori informazioni, se necessarie.

Per esempio:

> squadra di fanteria, 9 unità, stazionarie, checkpoint su strada.

### 5 - Metodo d'ingaggio

Nel metodo di ingaggio, l'osservatore specifica al FDC come vorrebbe ingaggiare il bersaglio:

- ^^AREA FIRE:^^ utilizzato per attaccare un'area (es: un checkpoint con coperture che separano le unità), facendo sparare all'artiglieria dei colpi dispersi su qualche decina di metri;
- ^^PRECISION FIRE:^^ utilizzato per attaccare uno bersaglio specifico (es: camion fermo su strada), che richiede impatti il più possibile vicini al ad esso, senza ulteriore dispersione da parte dell'artiglieria;
- ^^indicazione "DANGER CLOSE":^^ indica che vi sono unità alleate nel raggio di 600 metri dal bersaglio;
- ^^TIPO E NUMERO MUNIZIONI^^, ad esempio l'osservatore specifica tipo di munizione (es. richiede HE oppure colpi fumogeni) e numero. In caso di mancata indicazione, il FDC decide in autonomia.

### 6 - Controllo/Remarks ed altre brevity per indicazioni sul fuoco di artiglieria

Nel controllo/remarks l'osservatore specifica informazioni aggiuntive al FDC per completare la richiesta di fuoco, come:

<!-- da convertire eventualmente in tabella di brevity -->
- ^^FIRE WHEN READY (FUOCO APPENA PRONTO):^^ il FDC spara (o ordina di sparare all'operatore) appena il colpo è pronto; 
- ^^AT MY COMMAND (AL MIO COMANDO):^^ il FDC carica ed aspetta il via libera dell'osservatore prima di sparare;
- ^^CANNOT OBSERVE (IMPOSSIBILE CONFERMARE):^^ l'osservatore non riesce a verificare l'efficacia dei colpi;
- ^^CONTINUOUS FIRE (FUOCO A VOLONTA'):^^ fuoco continuo fino a comunicazione di cessate il fuoco;
- ^^CHECK FIRE (CESSATE IL FUOCO):^^ stop immediato al fuoco;
- ^^CEASE LOADING:^^ stop al caricamento dei pezzi (con eventuale fuoco degli ultimi colpi precedentemente caricati);
- ^^REPEAT (RIPETI):^^ richiesta di sparare una nuova salva;

Tutte le brevity possono essere tradotte in italiano.

### 7 - Aggiustamenti del tiro

Qualora servisse correggere il fuoco di artiglieria, le parole da utilizzare sono:

- ^^LEFT/RIGHT^^ (a ggiustamento distanza orizzontale)
- ^^ADD/DROP^^ (aggiustamento di tiro troppo lungo/troppo corto)
- si utilizza raramente UP/DOWN (aggiustamento di altezza, quindi quota)

Le brevity sono seguite dalla quantità in metri. Ad esempio, se un colpo cadesse 200 metri lungo e 100 metri a destra del
bersaglio, la correzione da richiedere al FDC sarebbe "DROP 200, LEFT 100". 

## Esempio di una Call for Fire

Un osservatore (callsign "WOLF") identifica una posizione nemica e vuole chiedere ai mortai (callsign "DORA") supporto di artiglieria.

> [FO] Dora, qui Wolf, adjust fire, 6 digit grid, passo.

> [FDC] Wolf, qui Dora, adjust fire, 6 digit grid, fine.

> [FO] Griglia 1-0-2 -- 0-3-6, elevazione 5-0-0 metri s.l.m., passo.

> [FDC] Griglia 1-0-2 -- 0-3-6, elevazione 5-0-0 metri s.l.m., fine.

> [FO] Squadra di fanti, 10 unità in campo aperto, 2x proiettili HE, danger close, al mio comando, passo.

> [FDC] Squadra di fanti, 10 unità in campo aperto, 3x proiettili HE, danger close, fuoco quando pronti, fine.

> [FO] Dora qui Wolf, readback non corretto: 2x proiettili HE, al mio comando, passo. 

> [FDC] Wolf qui Dora, correggo: 2x proiettili HE, al mio comando, fine. 

> *(poco tempo dopo, preparando il colpo di artiglieria con i vari calcoli del cannoniere)*

> [FDC] Wolf qui Dora, pronti al fuoco, passo. 

> [FO] Dora qui Wolf, fuoco. 

> *(poco tempo dopo, quando il colpo sta per atterrare sul bersaglio)*

> [FDC] Wolf, Dora, splash.

> [FO] Dora, Wolf, add 200 left 50, ripeti, passo. 

> [FDC] add 200 left 50, ripeti, fine. 

> *(dopo aver corretto secondo le indicazioni)*

> [FDC] Wolf qui Dora, pronti al fuoco, passo. 

> [FO] Dora qui Wolf, fuoco.

> *(poco tempo dopo, quando il colpo sta per atterrare sul bersaglio)*

> [FDC] Wolf, Dora, splash.

> [FO] Dora, Wolf, bersaglio neutralizzato, passo. 

> [FDC] Wolf, Dora, ricevuto, richiesta di supporto completata, fine.

## Template PDF della Call for Fire

<div class="grid cards" markdown>
- :material-clipboard-text: [__PDF Call for Fire__](../assets/procedure_templates/CALL_FOR_FIRE.pdf)<br>
  Template PDF stampabile per la procedura Call for Fire.
</div>
