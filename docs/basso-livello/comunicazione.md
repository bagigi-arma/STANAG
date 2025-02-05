---
template: home.html
title: Comunicazione
---

# Comunicazione e Radiofonia

## La mod radio

Il Network Bagigi si è standardizzato sulla mod [ACRE2 - Bagigi Fork](https://steamcommunity.com/sharedfiles/filedetails/?id=3012268676) come mod radio per le operazioni Arma 3.<br>
Essa ci permette di parlare con gli altri giocatori in missione mediante un plugin di [TeamSpeak3](https://teamspeak.com/en/downloads/#ts3client), che viene auto-installato durante l'avvio di Arma 3, se la mod è stata attivata.

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
| `1/5` | 1 | 2 | 13 | Comunicazioni a singoli durante briefing o CQB con nemici vicinissimi |
| `2/5` | 3 | 15 | 55 | Comunicazione con il proprio buddy senza intralciare il resto del gruppo, oppure con il proprio gruppo se c'è possibile presenza nemica nelle vicinanze |
| `3/5` | 8 | 30 | 100 | Adatto al 90% delle situazioni sul campo, buona via di mezzo tra non intralciare/svelarsi e essere sentiti dal proprio gruppo |
| `4/5` | 12 | 45 | 145 | Situazioni di combattimento in cui dobbiamo farci sentire da tutta una squadra, con buddy-team distribuiti a >15m di distanza |
| `5/5` | 15 | 55 | 195 | Comunicazione chiara con un gruppo distaccato o altre squadre, specialmente in scenari senza radio personali |

!!! note "Mentre trasmettiamo in radio, il volume parlato (indipendente da quello trasmesso) viene ridotto di un singolo livello."

### La propagazione delle onde radio

La propagazione delle onde radio di banda [VHF](https://it.wikipedia.org/wiki/Very_high_frequency)/[UHF](https://it.wikipedia.org/wiki/Ultra_high_frequency) viene simulata da ACRE2 con un elevato livello di realismo, secondo il modello reale comunemente noto come [multipath](https://it.wikipedia.org/wiki/Multipath_fading), che si comporta secondo i seguenti criteri:

- Propagazione LOS con attenuazione su distanza.
- Propagazione mediante riflessioni di onde sul terreno circostante.
- Riflessioni di onde dal terreno circostante interferiscono con l'onda LOS o altre riflessioni e possono degradare il segnale ricevuto.
- Se non si è in LOS e non c'è terreno circostante su cui il segnale può riflettere per giungere al destinatario, non ci sarà collegamento anche se la distanza tra i due è di <100 metri.

### Le radio personali

Le radio di ACRE2 non utilizzano lo slot della radio nel proprio inventario come forse avete visto dalla TFAR. Invece devono essere messe in un qualsiasi contenitore, l'uniforme, il corpetto o lo zaino stesso.<br>
Alcune radio "da zaino" possono essere portate *(sorpresa!)* solo in uno zaino.

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

#### La radio "attiva"

Concetto di radio "attiva" dell'ACRE2, <kbd>Alt</kbd>+<kbd>⇧&nbsp;Shift</kbd>+<kbd>CapsLock</kbd>.

#### I tasti PTT

Concetto di PTT e come riassegnarli.

### Interfono e radio veicolari

#### L'Interfono/Intercom

Velivoli e veicoli corrazzati montano quasi sempre un "interfono" che ci permette di comunicare in modo chiaro con altri membri dell'equipaggio e passeggeri imbarcati, senza essere ostacolati dal rumore generato dal veicolo e la distanza tra i nostri sedili.

#### Radio "rack" veicolari

Veicoli e velivoli hanno delle radio proprie con ampia potenza di trasmissione. Si differenziano principalmente in 2 tipologie:

- ^^Rack con radio non rimovibili:^^<br>
  Sono quelli più comunemente usati, praticamente sempre presenti su veicoli pesanti e velivoli. Possiamo "usarli" con l'apposita interazione (o con la manopola Work dell'intercom, sui veicoli corrazzati), così diventeranno parte della nostra radio personale 
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
    - VHF30108 GS: l'antenna "Ground Spike" montabile, alta circa 2.4m, compatibile con `AN/PRC-148/152/117F/77` e `SEM 70`;
    - VHF30108 GSM: antenna + albero per 6.4m di altezza, smontabile in GS per separare l'oggetto Mast;
    - VHF30108 Mast: oggetto di "albero", montabile su un GS per estenderlo in GSM;
- ^^Antenne SATCOM:^^<br>
  Questo tipo di antenna permette la comunicazione radio con protocolli di comunicazione particolari, utilizzando un satellite geosincrono come relay. La portata viene così estesa effettivamente su tutto il pianeta, l'unico requisito è che sia l'antenna trasmettente che quella ricevente devono avere una LOS libera verso il cielo.
    - RF-3080: antenna SATCOM piazzabile, compatibile con `AN/PRC-152/117F`;

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
