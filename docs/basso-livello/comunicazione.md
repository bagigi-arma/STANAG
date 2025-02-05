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

La simulazione della voce mediante cui possiamo parlare con i giocatori in prossimità.

> ACRE2 has a built in direct speech slider allowing you to determine how far your voice in direct speech should travel. The system has five states and by default starts in the middle state. The below table contains an approximated table with empirical testing by Bullhorn.

| Volume state | Loud (m)| Quiet (m)| Barely audible (m)|
| -------- | -------- | -------- | -------- |
| 1/5 | 1 | 2 | 13 |
| 2/5 | 3 | 15 | 55 |
| 3/5 | 8 | 30 | 100 |
| 4/5 | 12 | 45 | 145 |
| 5/5 | 15 | 55 | 195 |

### Le radio personali

Le radio di ACRE2 non utilizzano lo slot della radio nel proprio inventario come forse avete visto dalla TFAR. Invece devono essere messe in un qualsiasi contenitore, l'uniforme, il corpetto o lo zaino stesso.<br>
Alcune radio "da zaino" possono essere portate *(sorpresa!)* solo in uno zaino.

La propagazione delle onde radio di banda [VHF](https://it.wikipedia.org/wiki/Very_high_frequency)/[UHF](https://it.wikipedia.org/wiki/Ultra_high_frequency) viene simulata con un elevato livello di realismo.<br>
Il modello di propagazione è comunemente noto come [multipath](https://it.wikipedia.org/wiki/Multipath_fading) e si comporta secondo i seguenti criteri:

- Propagazione LOS con attenuazione su distanza.
- Propagazione mediante riflessioni di onde sul terreno circostante.
- Riflessioni di onde dal terreno circostante interferiscono con l'onda LOS o altre riflessioni e possono degradare il segnale.
- Se non si è in LOS e non c'è terreno circostante su cui il segnale può riflettere per giungere al destinatario, non ci sarà collegamento anche se la distanza tra i 2 è di <100 metri.

| Nome Radio | Descrizione | Potenza di Trasmissione | Portata urbana/ideale |
| ---------- | ----------- | ----------------------- | -------------- |
| [AN/PRC-343](https://acre2.idi-systems.com/wiki/radios/an-prc-343) | Una piccola radio tascabile di portata molto limitata, i suoi blocchi/canali sono compatibili solo con altre PRC-343.<br>In dotazione a tutti i fanti in scenari moderni per comunicazioni a livello di gruppo/squadra. | 100 mW | 400/850 m |
| [AN/PRC-148](https://acre2.idi-systems.com/wiki/radios/an-prc-148) | Una radio a medio raggio, usa gli stessi canali delle PRC-152/117F.<br>Viene usata dai TL/SL per comunicazioni a livello di squadra/plotone. | 5 W | 4/6 km |
| [AN/PRC-152&#40;c&#41;](https://acre2.idi-systems.com/wiki/radios/an-prc-152) | Una radio a medio raggio, usa gli stessi canali delle PRC-148/117F.<br>Viene usata dai TL/SL per comunicazioni a livello di squadra/plotone. | 5 W | 4/6 km |
| [AN/PRC-117F](https://acre2.idi-systems.com/wiki/radios/an-prc-117f) | Una radio a lungo raggio, trasportabile solo negli zaini, usa gli stessi canali delle PRC-148/152.<br>Viene usata dai SL/PL e JTAC per comunicazioni a lungo raggio, a livello di plotone/compagnia | 20 W | 10-20 km |
| [AN/PRC-77](https://acre2.idi-systems.com/wiki/radios/an-prc-77) | Una radio da zaino degli anni '60, usata in Vietnam. Viene impostata con varie frequenze, compatibili solo con altre PRC-77.<br>Utilizzata principalmente a livello di plotone/compagnia. | 4 W | 2/4 km |
| [SEM 52 SL](https://acre2.idi-systems.com/wiki/radios/sem-52-sl) | Una radio dell'esercito tedesco, compatibile solo con altre SEM 52L/70.<br>Utilizzata a livello di squadra. | 1 W | 1/3 km |
| [SEM 70](https://acre2.idi-systems.com/wiki/radios/sem-70) | Una radio da zaino dell'esercito tedesco, compatibile solo con altre SEM 52L/70.<br>Ulizzata a livello di plotone. | 4 W | 2/4 km |
| [Baofeng BF-888S](https://acre2.idi-systems.com/wiki/radios/bf-888s) | Una radio civile a medio raggio, con canali compatibili solo con altre Baofeng.<br>Utile a forze paramilitari o eserciti meno equipaggiati. | 5 W | 3/5 km |

### Le antenne piazzabili

Antenne montabili che possono essere piazzate al suolo e collegate ad una nostra radio per aumentare la sua potenza di trasmissione, e di conseguenza la sua portata.

### Interfono e radio veicolari

Veicoli e velivoli hanno delle radio proprie con ampia potenza di trasmissione.

Il loro interfono ci permette di comunicare in modo chiaro con altri membri dell'equipaggio e passeggeri imbarcati, senza essere ostacolati dal rumore generato dal veicolo e la distanza tra i nostri sedili.

### Keybind e concetti utili

#### La radio "attiva"

Concetto di radio "attiva" dell'ACRE2, <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>CapsLock</kbd>.

#### I tasti PTT

Concetto di PTT e come riassegnarli.

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
