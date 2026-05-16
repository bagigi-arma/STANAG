---
template: home.html
title: Artiglieria
---

# Supporto di fuoco da artiglieria

In questo documento vengono riassunte le procedure per chiamare, con precisione e sicurezza, una missione di fuoco d'artiglieria (quindi non eseguita da ala rotante né ala statica, ma obici, e mortai).

## Le categorie di supporti

- **Mortaio:**<br>
  Un pezzo di artiglieria leggero, trasportabile da un gruppo di fanti in maniera furtiva. Viene generalmente impiegato dalle prossimità del fronte, supportando forze alleate con colpi esplosivi/fumogeni/illuminanti che possono giungere sul bersaglio entro un minuto, fino ad una distanza massima di circa 4 km per mortai da 82mm, o fino a 10 km per mortai da 120mm.<br>
  Esempi: [M252](https://en.wikipedia.org/wiki/M252_mortar), [2B14 Podnos](https://en.wikipedia.org/wiki/2B14_Podnos).
- **Obice:**<br>
  Un pezzo di artiglieria più pesante, che può essere statico (rimorchiabile da camion) o semovente su telaio cingolato. Il suo scopo è rimanere ben dietro le linee alleate per prestare supporto di fuoco **indiretto**, sparando proiettili esplosivi/fumogeni/illuminanti di 155mm per decine di chilometri. In caso di scontri ravvicinati può effettuare fuoco **diretto**, come un carro armato, anche se le prestazioni balistiche del cannone e il sistema di controllo del tiro meno adatto risultano in ingaggi più lenti.<br>
  Esempi: [M109 Paladin](https://en.wikipedia.org/wiki/M109_howitzer), [2S3 Akatsiya](https://en.wikipedia.org/wiki/2S3_Akatsiya).
- **Lanciarazzi Multiplo:**<br>
  Un pezzo di artiglieria capace di sparare razzi, che gli permettono mandare più massa esplosiva sul bersaglio rispetto agli obici su distanze paragonabili. Anche esso rimane dietro il fronte, per sparare anche su obiettivi strategici nella profondità del territorio nemico, a decine ([o centinaia](https://en.wikipedia.org/wiki/Precision_Strike_Missile)) di km.<br>
  Esempi: [M142 HIMARS](https://en.wikipedia.org/wiki/M142_HIMARS), [BM-21 Grad](https://en.wikipedia.org/wiki/BM-21_Grad).
- **Cannone navale:**<br>
  Un cannone di alto calibro montato su navi, nel caso di fregate/cacciatorpedinieri moderni generalmente usa un calibro di 76-127mm. Può essere usato dalla marina per prestare supporto di fuoco sulla terraferma.
- **Missili da crociera:**<br>
  Sono missili guidati, generalmente lanciati da navi da guerra, che volano a bassa quota e alte velocità. Permettono attacchi di precisione con grandi carichi esplosivi nel profondo territorio nemico, su bersagli strategici di altissimo valore. Le loro dimensioni li rendono vulnerabili all'acquisizione e abbattimento da parte di contraeree nemiche, se si ritrovano esposti ad esse sopra terreno pianeggiante.<br>
  Esempi: [BGM-109 Tomahawk](https://it.wikipedia.org/wiki/BGM-109_Tomahawk), [3M-14 Kalibr](https://en.wikipedia.org/wiki/Kalibr_(missile_family)).

## La richiesta (Call for Fire)

La richiesta per supporto di artiglieria (in inglese **"Call for fire"**) viene comunicata dall'osservatore (**"Forward Observer"**) all'elemento che coordina il fuoco di artiglieria (**"Fire Direction Center"**).

Il **FO** può essere un operatore designato specificatamente in missione per ricoprire questo ruolo, ma generalmente verrà eseguito in caso di necessità dalla figura di comando (PL, SL, TL), radiofonista (RTO) o JTAC presente, a condizione che sia pratico nella procedura **Call For Fire**.

Il **FDC** solitamente coincide in missione con il Team Leader a capo di uno o più mortai/obici/lanciarazzi.

La chiamata è composta da 6 elementi, trattati nel dettaglio di seguito:

1. Identificazione dell'osservatore
2. WARNO (Warning Order), che riassume il tipo di ingaggio che stiamo richiedendo
3. Posizione del bersaglio
4. Descrizione del bersaglio
5. Metodo d'ingaggio
6. Controllo/Remarks

Ogni qual volta che il **FO** comunica, il **FDC** risponde con un readback per verificare che le informazioni comprese siano corrette.

Quando vengono sparati i colpi richiesti, il **FDC** può comunicare al **FO** che i colpi sono partiti con la brevity ^^"SHOT"^^, e può aggiungere come informazione il tempo di volata dei colpi. <!-- verificare se vogliamo aggiungere tale brevity o lasciarla implicita e meno precisa con la conferma dell'ordine di fuoco -->

E' invece obbligatorio, quando mancano circa 10 secondi all'impatto del primo colpo, che il **FDC** avvisi dell'arrivo imminente del proittile il **FO** con la brevity ^^"SPLASH"^^, in modo che quest'ultimo possa avvisare (se non lo ha già fatto) gli alleati vicini di rimanere in copertura, di fronte al rischio di frammentazione.

Dopo aver valutato l'effetto della salva, il **FO** comunica i danni inflitti al **FDC**, chiedendo correzioni o confermando la neutralizzazione del bersaglio.

### Elementi della Call for Fire

#### 1 - Identificazione dell'osservatore

Il FO chiama il FDC e si identifica con il suo callsign (o altro metodo di identificazione in missione), prima di procedere con la richiesta.

#### 2 - WARNO

Il WARNO può essere di due tipi:

- ^^ADJUST FIRE^^ quando l'osservatore stima che serviranno diversi colpi prima di centrare il bersaglio, richiedendo aggiustamenti del tiro;
- ^^FIRE FOR EFFECT^^ quando le coordinate sono precise e ci si aspetta che la salva di colpi abbia effetto senza necessità di aggiustamenti.

??? note
    Nella dottrina militare USA esistono anche le altri tipo di WARNO come SUPPRESSION, IMMEDIATE SUPPRESSION, IMMEDIATE SMOKE, che nelle nostre partite di Arma rimangono però di limitato utilizzo. Per approfondire potete leggere questo [manuale USA](https://www.marines.mil/Portals/1/Publications/FM%206-30.pdf).

#### 3 - Posizione del bersaglio

La posizione del bersaglio può essere comunicata in modi diversi dal FO al FDC.

Come convenzione preferiamo sempre utilizzare le coordinate della griglia in mappa di gioco, la minima precisione accettabile è la 6 digit grid, es: 1-2-3, 4-5-6.

??? note
    Nella dottrina militare USA si utilizzano anche altri modi per comunicare la posizione dei bersagli, come il POLAR o SHIFT FROM A KNOWN POINT, che nelle nostre partite di Arma rimangono però di limitato utilizzo. Per approfondire potete leggere questo [manuale USA](https://www.marines.mil/Portals/1/Publications/FM%206-30.pdf).

#### 4 - Descrizione del bersaglio

La descrizione del bersaglio include cosa è il bersaglio, cosa sta facendo, se dispone di coperture, di quante unità è composto e ulteriori informazioni, se necessarie.

Per esempio:

> squadra di fanteria, 9 unità, stazionarie, checkpoint su strada.

#### 5 - Metodo d'ingaggio

Nel metodo di ingaggio, l'osservatore specifica al FDC come vorrebbe ingaggiare il bersaglio:

- ^^AREA FIRE:^^ utilizzato per attaccare un'area (es: un checkpoint con coperture che separano le unità), facendo sparare all'artiglieria dei colpi dispersi su qualche decina di metri;
- ^^PRECISION FIRE:^^ utilizzato per attaccare uno bersaglio specifico (es: camion fermo su strada), che richiede impatti il più possibile vicini al ad esso, senza ulteriore dispersione da parte dell'artiglieria;
- ^^indicazione "DANGER CLOSE":^^ indica che vi sono unità alleate nel raggio di 600 metri dal bersaglio;
- ^^TIPO E NUMERO MUNIZIONI^^, ad esempio l'osservatore specifica tipo di munizione (es. richiede HE oppure colpi fumogeni) e numero. In caso di mancata indicazione, il FDC decide in autonomia.

#### 6 - Controllo/Remarks ed altre brevity per indicazioni sul fuoco di artiglieria

Nel controllo/remarks l'osservatore specifica informazioni aggiuntive al FDC per completare la richiesta di fuoco, come:

| Brevity inglese | Brevity Italiana | Significato |
| --- | --- | --- |
| FIRE WHEN READY | FUOCO APPENA PRONTO | il FDC spara (o ordina di sparare all'operatore) appena il colpo è pronto |
| AT MY COMMAND | AL MIO COMANDO | il FDC carica ed aspetta il via libera dell'osservatore prima di sparare |
| CANNOT OBSERVE | IMPOSSIBILE CONFERMARE | l'osservatore non riesce a verificare l'efficacia dei colpi |
| CONTINUOUS FIRE | FUOCO A VOLONTÀ | fuoco continuo fino a comunicazione di cessate il fuoco |
| CHECK FIRE | CESSATE IL FUOCO | stop immediato al fuoco |
| CEASE LOADING | CESSATE IL CARICAMENTO | stop al caricamento dei pezzi (con eventuale fuoco degli ultimi colpi precedentemente caricati) |
| REPEAT | RIPETERE SALVA | richiesta di sparare una nuova salva |

#### 7 - Aggiustamenti del tiro

Qualora servisse correggere il fuoco di artiglieria, le parole da utilizzare sono:

- ^^LEFT/RIGHT^^ (aggiustamento distanza orizzontale)
- ^^ADD/DROP^^ (aggiustamento di tiro troppo lungo/troppo corto)
- si utilizza raramente UP/DOWN (aggiustamento di altezza, quindi quota)

Le brevity sono seguite dalla quantità in metri. Ad esempio, se un colpo cadesse **200 metri lungo** e **100 metri a destra** del bersaglio, la correzione da richiedere al FDC sarebbe ^^"DROP 200, LEFT 100"^^.

!!! info "La direzione di riferimento per le chiamate è quella di fuoco del FDC interessato. Il FO deve quindi tenere in mente all'incirca da dove proviene il fuoco alleato."

### Esempio di una Call for Fire

Un osservatore (callsign **"WOLF"**) identifica una posizione nemica e vuole chiedere ai mortai (callsign **"DORA"**) supporto di artiglieria.

> [FO] Dora, qui Wolf, adjust fire, 6 digit grid, passo.

> [FDC] Wolf, qui Dora, adjust fire, 6 digit grid, fine.

> [FO] Griglia 1-0-2 -- 0-3-6, elevazione 5-0-0 metri s.l.m., passo.

> [FDC] Griglia 1-0-2 -- 0-3-6, elevazione 5-0-0 metri s.l.m., fine.

> [FO] Squadra di fanti, 10 unità in campo aperto, 2 proiettili HE, danger close, al mio comando, passo.

> [FDC] Squadra di fanti, 10 unità in campo aperto, 3 proiettili HE, danger close, fuoco quando pronti, fine.

> [FO] Dora qui Wolf, readback non corretto: 2 proiettili HE, al mio comando, passo. 

> [FDC] Wolf qui Dora, correggo: 2 proiettili HE, al mio comando, fine. 

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

### Template PDF della Call for Fire

<div class="grid cards" markdown>
- :material-clipboard-text: [__PDF Call for Fire__](../assets/procedure_templates/CALL_FOR_FIRE.pdf)<br>
  Template PDF stampabile per la procedura Call for Fire.
</div>
