---
template: home.html
title: Comunicazione
---

# Comunicazione e Radiofonia

## La mod radio

Il Network Bagigi si è standardizzato sulla mod [ACRE2 - Bagigi Fork](https://steamcommunity.com/sharedfiles/filedetails/?id=3012268676) come mod radio per le operazioni Arma 3.<br>
Essa ci permette di parlare con gli altri giocatori in missione mediante un plugin di [TeamSpeak3](https://teamspeak.com/en/downloads/#ts3client), che viene auto-installato durante l'avvio di Arma 3, se la mod è stata attivata.

Le informazioni in questa guida fanno riferimento alla [wiki di ACRE2](https://acre2.idi-systems.com/wiki/user/overview). La lettura è consigliata in particolare per argomenti non trattati su questa pagina, come [i GUI delle radio](https://acre2.idi-systems.com/wiki/radios/overview).

Mod utili compatibili con questo Fork sono:

- [ACRE2 Bagigi Animations](https://steamcommunity.com/sharedfiles/filedetails/?id=3126781754) per le animazioni delle mani che interagiscono con le varie radio.
- [ILBE Pack for ACRE2 - Bagigi Repack](https://steamcommunity.com/sharedfiles/filedetails/?id=3065316263) che aggiunge vari modelli e mimetiche di zaini radio con antenne sporgenti, di capienza sufficiente per contenere una qualsiasi radio da zaino.

### La voce diretta

La simulazione della voce ci permette di sentire gli altri giocatori **direzionalmente**, con un volume nelle nostre orecchie che dipende dai seguenti fattori:

- La distanza tra di noi.
- La presenza di compartimenti veicolari o terreno/muri tra di noi.
- Il volume con cui stanno parlando.

Questo ultimo fattore si riferisce alla funzionalità di ACRE2 che ci permette di modificare il "volume" della nostra voce, dal bisbiglio al grido.

Tenendo premuto <kbd>Tab&nbsp;⇥</kbd> e girando la rotellina del mouse possiamo selezionare velocemente l'impostazione desiderata o semplicemente controllare quella attuale.

!!! warning "Parlare a voce troppo alta rivela la nostra presenza anche ai Bot nemici"

La seguente tabella elenca i 5 volumi di voce disponibili, con le relative distanze massime udibili e le situazioni più adatte all'utilizzo.

| Volume della voce | Alto (m)| Basso (m) | Quasi impercettibile (m) | Quando usarlo? |
| -------- | -------- | -------- | -------- | -------- |
| `1/5` | 1 | 2 | 13 | Comunicazione a singoli durante briefing o CQB con nemici vicinissimi |
| `2/5` | 3 | 15 | 55 | Comunicazione con i propri buddy senza intralciare il resto del gruppo, oppure con il proprio gruppo se c'è possibile presenza nemica nelle vicinanze |
| `3/5` | 8 | 30 | 100 | Adatto al 90% delle situazioni sul campo, buona via di mezzo tra non intralciare/svelarsi e essere sentiti dal proprio gruppo |
| `4/5` | 12 | 45 | 145 | Situazioni di combattimento in cui dobbiamo farci sentire da tutta una squadra, con buddy-team distribuiti a >15m di distanza |
| `5/5` | 15 | 55 | 195 | Comunicazione chiara con un gruppo distaccato o altre squadre, specialmente in scenari senza radio personali |

!!! note "Mentre trasmettiamo in radio, il volume parlato (indipendente da quello trasmesso) viene ridotto di un singolo livello."

### La propagazione delle onde radio

La propagazione delle onde radio di banda [VHF](https://it.wikipedia.org/wiki/Very_high_frequency)/[UHF](https://it.wikipedia.org/wiki/Ultra_high_frequency) viene simulata da ACRE2 con un elevato livello di realismo, secondo il modello reale comunemente noto come [multipath](https://it.wikipedia.org/wiki/Multipath_fading), che si comporta secondo i seguenti criteri:

- Propagazione LOS con [attenuazione di spazio libero](https://it.wikipedia.org/wiki/Attenuazione_di_spazio_libero).
- Propagazione mediante riflessioni di onde sul terreno circostante.
- Riflessioni di onde dal terreno circostante interferiscono con l'onda LOS o altre riflessioni e possono degradare il segnale ricevuto.
- Se non si è in LOS e non c'è terreno circostante su cui il segnale può riflettere per giungere al destinatario, non ci sarà collegamento anche se la distanza tra i due è di <100 metri.

Visto che non esistono ancora radio subacquee (per i sub), ma nella realtà è più facile comunicare a gesti sott'acqua, il compromesso attuale attuato dall'ACRE2 è che la voce diretta viene bloccata, mentre le radio funzionano normalmente.

### Le radio personali

Le radio di ACRE2 non utilizzano lo slot della radio nel proprio inventario come forse avete visto dalla TFAR. Invece devono essere messe in un qualsiasi contenitore, l'uniforme, il corpetto o lo zaino stesso. Alcune radio "da zaino" possono essere portate *(sorpresa!)* solo in uno zaino.

| Nome Radio | Descrizione | Potenza di Trasmissione | Portata urbana / ideale |
| ---------- | ----------- | ----------------------- | ----------------------- |
| [AN/PRC-343](https://acre2.idi-systems.com/wiki/radios/an-prc-343) | Una piccola radio tascabile di portata molto limitata, i suoi blocchi/canali sono compatibili solo con altre PRC-343.<br>In dotazione a tutti i fanti in scenari moderni per comunicazioni a livello di gruppo/squadra. | 100 mW | 400 / 850 m |
| [AN/PRC-148](https://acre2.idi-systems.com/wiki/radios/an-prc-148) | Una radio a medio raggio, usa gli stessi canali delle PRC-152/117F.<br>Viene usata dai TL/SL per comunicazioni a livello di squadra/plotone. | 5 W | 4 / 6 km |
| [AN/PRC-152&#40;c&#41;](https://acre2.idi-systems.com/wiki/radios/an-prc-152) | Una radio a medio raggio, usa gli stessi canali delle PRC-148/117F.<br>Viene usata dai TL/SL per comunicazioni a livello di squadra/plotone. | 5 W | 4 / 6 km |
| [AN/PRC-117F](https://acre2.idi-systems.com/wiki/radios/an-prc-117f) | Una radio a lungo raggio, trasportabile solo negli zaini, usa gli stessi canali delle PRC-148/152.<br>Viene usata dai SL / PL e JTAC per comunicazioni a lungo raggio, a livello di plotone/compagnia | 20 W | 10 / 20 km |
| [AN/PRC-77](https://acre2.idi-systems.com/wiki/radios/an-prc-77) | Una radio da zaino degli anni '60, usata in epoca Vietnam. Viene impostata con varie frequenze, compatibili solo con altre PRC-77.<br>Utilizzata principalmente a livello di plotone/compagnia. | 4 W | 2 / 4 km |
| [SEM 52 SL](https://acre2.idi-systems.com/wiki/radios/sem-52-sl) | Una radio dell'esercito tedesco, compatibile solo con altre SEM 52SL/70.<br>Utilizzata a livello di squadra. | 1 W | 1 / 3 km |
| [SEM 70](https://acre2.idi-systems.com/wiki/radios/sem-70) | Una radio da zaino dell'esercito tedesco, compatibile solo con altre SEM 52SL/70.<br>Ulizzata a livello di plotone. | 4 W | 2 / 4 km |
| [Baofeng BF-888S](https://acre2.idi-systems.com/wiki/radios/bf-888s) | Una radio civile a medio raggio, con canali compatibili solo con altre Baofeng.<br>Utile a forze paramilitari o eserciti meno equipaggiati. | 5 W | 3 / 5 km |

### Keybind e concetti utili

In ACRE2 tutte le radio personali sono equivalenti in termini di UI, non esiste distinzione tra SR e LR per i keybind come sulla TFAR. Questo comporta un modo particolare di gestire le proprie radio, che offre però alcuni vantaggi.

#### I tasti PTT

Con "Push To Talk" si intende un tasto che premiamo per trasmettere con una determinata radio. ACRE2 permette l'assegnazione di 3 tasti, identificati nel GUI sempre con il rispettivo numero:

1. <kbd>CapsLock</kbd>
2. <kbd>Ctrl</kbd> + <kbd>CapsLock</kbd>
3. <kbd>Alt</kbd> + <kbd>CapsLock</kbd>

Quando equipaggiamo una radio, essa verrà assegnata al primo PTT libero. Se ne equipaggiamo più di 3, quelle in eccesso saranno comunque udibili, ma non ci potremo trasmettere senza assegnarle un PTT.

Possiamo in un qualsiasi momento modificare l'assegnazione dei PTT, mediante opportune auto-interazioni ACE3 sulla radio desiderata.<br>
Questa funzione diventa utile nel caso in cui siamo parte di un elemento di comando più lontano dal combattimento, dove ci torna più comodo avere la nostra `AN/PRC-152/117F` più usata su PTT1, relegando la `AN/PRC-343` al PTT2-3.

#### La radio "attiva"

Siccome possiamo equipaggiare molte radio, serve un modo per determinare su quale avranno effetto i nostri keybind di manipolazione. Qui subentra il concetto di radio "attiva" dell'ACRE2.

La nostra radio "attiva" è **sempre** l'ultima radio su cui abbiamo trasmesso. Possiamo però anche determinarla manualmente (fino alla prossima trasmissione), sia mediante l'opportuna autointerazione, che ciclandola tra le radio che abbiamo appresso con <kbd>Alt</kbd> + <kbd>⇧&nbsp;Shift</kbd> + <kbd>CapsLock</kbd>.

Così potremo usare i seguenti comandi per manipolare velocemente l'attuale radio "attiva", senza dover ricorrere alla relativa autointerazione o manipolazione del GUI:

- <kbd>Ctrl</kbd> + <kbd>&uarr;</kbd> / <kbd>&darr;</kbd> per cambiare il canale della radio.
- <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>CapsLock</kbd> per aprire il GUI della radio.
- <kbd>Ctrl</kbd> + <kbd>⇧&nbsp;Shift</kbd> + <kbd>&larr;</kbd> / <kbd>&uarr;</kbd> / <kbd>&rarr;</kbd> per impostare l'orecchio da cui sentiamo la radio su sinistro/entrambi/destro.

#### Abbassare la cuffia

Esistono situazioni, in particolare nel ruolo di caposquadra o superiori, in cui comunicazioni radio ostacolano una contemporanea conversazione a voce di maggiore importanza.

Con <kbd>Ctrl</kbd> + <kbd>⇧&nbsp;Shift</kbd> + <kbd>&darr;</kbd> (o la relativa autointerazione) possiamo abbassare/indossare la "cuffia". Il risultato è una immediata riduzione del volume di tutte le nostre radio, abbastanza da non ostacolare alcuna comunicazione a voce, senza però mutarle del tutto.

### Interfono e radio veicolari

#### L'Interfono/Intercom

Velivoli e veicoli corrazzati montano quasi sempre un "interfono" che ci permette di comunicare in modo chiaro con altri membri dell'equipaggio e passeggeri imbarcati, senza essere ostacolati dal rumore generato dal veicolo o la distanza tra i nostri sedili.

Su praticamente tutti i veicoli con interfono, esso si suddivide in uno o due canali:

- ^^Crew/Equipaggio:^^<br>
  Viene collegato in automatico quando si entra su posti di pilota, artigliere o comandante.<br>
  I passeggeri possono collegarsi a questo canale solo in 1-2 contemporaneamente, al fine di non disturbare l'equipaggio (lasciatele quindi libere per i leader imbarcati). Inoltre il collegamento userà la modalità PTT, richiedendo l'assegnazione e utilizzo del rispettivo keybind per trasmettere sul canale.
- ^^Pax/Passeggeri:^^<br>
  Canale di libera comunicazione per tutto il personale imbarcato, sia per l'equipaggio che i passeggeri. Questo non significa però che conviene collegarsi tutti. Specialmente su velivoli con >12 posti conviene collegarsi solo da SL/TL e rispettivi vice, in modo da lasciare il canale libero per il coordinamento tra leader.

L'interfaccia dell'intercom è apribile mediante interazioni ACE3 su veicolo>intercom>canale, oppure il keybind <kbd>Ctrl</kbd> + <kbd>⇧&nbsp;Shift</kbd> + <kbd>Tab&nbsp;⇥</kbd>. Essa è modellata secondo il reale sistema ["Full Function Crew Station"](https://chelton.com/media/51ajstyf/lv2-brochure.pdf), permettendoci di impostare ogni canale intercom con una modalità adatta alle nostre esigenze.

Per una spiegazione più approfondita dell'interfaccia e gli utilizzi delle 4 manopole, leggete la [guida ufficiale di ACRE2 sull'intercom](https://acre2.idi-systems.com/wiki/user/vehicle-intercom).

#### Telefono fanteria

Alcuni veicoli corrazzati permettono ad un fante sbarcato di collegarsi all'interfono dall'esterno, per comunicare con l'equipaggio senza richiedere l'utilizzo di radio o lo sporgimento del comandante dalla botola.

Possiamo utilizzarlo (se disponibile) mediante l'opportuna interazione ACE3 al centro o sul retro del veicolo. Successivamente trasmetteremo di continuo sul canale intercom scelto, finché rimaniamo consci ed entro la distanza massima di ~3m dal veicolo.

Sempre sul veicolo potremo trovare interazioni per riporre il telefono fanteria o cambiare il canale. Possiamo inoltre passare il telefono ad un altro fante vicino, mediante l'opportuna interazione sul suo bacino.

#### Radio "rack" veicolari

Veicoli e velivoli hanno dei "rack" radio propri con ampia potenza di trasmissione. Si differenziano principalmente in due tipologie:

- ^^Rack con radio non rimovibili:^^<br>
  Sono quelli più comunemente usati, praticamente sempre presenti su veicoli pesanti e velivoli. Possiamo "usarli" con l'apposita interazione (o con la manopola Work dell'intercom, sui veicoli corrazzati), così verranno aggiunti alla nostra lista di radio personali.
    - `AN/VRC-103`: monta una `AN/PRC-117F` con potenza aumentata da 20W a 50W;
    - `AN/VRC-64`: monta una `AN/PRC-77` con potenza aumentata da 4W a 50W;
    - `SEM 90`: monta una `SEM 70` con potenza selezionabile di 4W o 40W;
- ^^Rack per radio montabili:^^<br>
  Possiamo trovarli principalmente su veicoli leggeri come macchine/MRAP. Permettono il collegamento di una radio tascabile a medio raggio come la PRC-148 o PRC-152 (che rimarrà sul mezzo finché disconnessa), al fine di utilizzare la più prestante antenna del veicolo.
    - `AN/VRC-110`: può montare una `AN/PRC-152`, aumentando la sua potenza da 5W a 20W;
    - `AN/VRC-111`: può montare una `AN/PRC-148`, aumentando la sua potenza da 5W a 20W;

### Antenne piazzabili

Antenne montabili che possono essere piazzate al suolo e collegate ad una nostra radio per aumentare la sua potenza di trasmissione, e di conseguenza la portata del segnale.

Qui sotto sono elencati i vari oggetti di inventario che possiamo montare, mediante auto-interazioni ACE3, in due tipologie di antenne:

- ^^Antenne convenzionali:^^<br>
  Esse migliorano la portata della radio collegata aumentando la potenza di trasmissione, ma anche elevando l'antenna sopra il terreno bloccante. La propagazione rimane comunque LOS, però la potenza maggiore aumenta l'efficacia di riflessioni contro il terreno.
    - `VHF30108 GS`: l'antenna "Ground Spike" montabile, alta circa 2.4m, compatibile con `AN/PRC-148`, `-152`, `-117F`, `-77` e `SEM 70`;
    - `VHF30108 Mast`: oggetto di "albero", montabile su un GS per estenderlo in GSM;
    - `VHF30108 GSM`: oggetto antenna + albero per 6.4m di altezza, smontabile in GS per separare l'oggetto Mast;
- ^^Antenne SATCOM:^^<br>
  Questo tipo di antenna permette la comunicazione radio con protocolli di comunicazione particolari, utilizzando un satellite geosincrono come relay. La portata viene così estesa effettivamente su tutto il pianeta, l'unico requisito è che sia l'antenna trasmettente che quella ricevente devono avere una LOS libera verso il cielo.
    - `RF-3080`: antenna SATCOM piazzabile, compatibile solo con `AN/PRC-152` e `-117F`;

### Radio "esterne"

Come usare le radio di altri operatori.

## La radiofonia

Come comunicare via radio in modo chiaro ed efficente.

### Fraseologia fondamentale

Esempi di comunicazioni corrette.
- "Passo" e "Chiudo"/"Fine"
Tabella con le brevity principali.

### Procedure utili

Esempi di procedure di comunicazione come "esecutivo all'ordine", "esecutivo immediato" o "assicuro".

### Una maglia radio

Come assegnare i canali/frequenze delle radio a disposizione dell'unità, al fine di ottimizzare il coordinamento tra elementi di fanteria ed eventuali assetti.
