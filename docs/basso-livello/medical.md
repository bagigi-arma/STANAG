---
template: home.html
title: Sistema Medico
---

# Sistema Medico

Questa sezione copre la standardizzazione del sistema medico usato dal Network Bagigi.

Le informazioni in questa guida fanno riferimento alle documentazioni delle mod [ACE Medical](https://ace3.acemod.org/wiki/feature/medical-system) e [KAT Advanced Medical](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit).

## Concetti generali

A prescindere dalle mod e i settaggi esatti in uso, esistono dei concetti generali utili a medicare altri giocatori in missione in maniera efficiente.

### Il personale medico

#### Il Fante

Un fante senza specializzazione può a volte stabilizzare un ferito senza richiedere l'intervento di un soccorritore o di un medico. Ma anche nei casi in cui questo non sia possibile, può comunque alleggerire il lavoro del personale medico.

Per questo è importante che ogni fante conosca le fondamenta del sistema medico e settaggi in uso, al fine di accorciare il più possibile i tempi di cura (propri e altrui) e snellire il flusso della missione.

#### Il Soccorritore

Un "mini-medico" a livello di gruppo/squadra, capace di stabilizzare autonomamente pazienti con condizioni lievi e in grado di fare affidamento sul supporto del medico per i casi più gravi.

#### Il Medico

Il medico totalmente formato a livello di squadra/plotone, che può supervisionare vari paramedici ai livelli sottostanti e supportarli con il suo equipaggiamento più specialistico. Inoltre potrà assumere la responsabilità in eventi di MCI e dirigere la triage di molteplici feriti, in attesa di un eventuale CASEVAC o MEDEVAC.

### L'ordine di cura

In entrambi livelli dello STANAG (e molte altre missioni impostate diversamente) i settaggi vigenti comportano un ordine di cura ottimale, che riduce la durata di rinvenimento del paziente e la probabilità del decesso ad un minimo.

#### 1. Ferma l'emorragia

L'azione di fermare il dissanguamento è praticamente sempre quella con priorità più alta. Più tempo trascorre e più si dovrà attendere per colmare il volume di fluidi perso mediante flebo. Inoltre, se la perdita di sangue diventa più grave del colore giallo (nel menu medico), sarà impossibile far rinvenire il paziente senza il supporto di personale medico.

Per fermare l'emorragia da arti (braccia/gambe) è spesso preferibile l'utilizzo di un laccio emostatico (anche chiamato "CAT") visto che il tempo di applicazione è molto minore di una qualsiasi benda.

Una ferita bendata può riaprirsi se non viene successivamente suturata da un soccorritore/medico. Alcuni tipi di bende sono più veloci nel tappare ampie ferite, altri sono più longevi prima di permettere la riapertura. [Qui potete trovare una tabella che elenca tali differenze](https://i.imgur.com/yr1hXT4.png).

#### 2. Ripristina il battito cardiaco

Emorragie e ferite gravi, in particolare alla testa, possono spesso causare un arresto cardiaco del paziente. Questa condizione può causare la morte entro pochi minuti, a prescindere dal dissanguamento o altre problematiche più apparenti.

Per questo motivo è importante ripristinare un ritmo normale appena possibile, prima di perdere tempo prezioso su azioni minori come la suturazione di ferite bendate.<br>
^^Nel caso specifico in cui un paziente potrebbe già essere in arresto da qualche minuto e la perdita di sangue non è ancora gravissima, il ripristino del ritmo normale diventa prioritario rispetto a fermare prima tutte le emorragie.^^

Tutti possono controllare il battito cardiaco mediante opportune interazioni su arti (senza CAT), petto o testa. È dunque la responsabilità del primo soccorritore, a prescindere dal livello di formazione medica, di controllare che il paziente abbia battito. In caso di assenza bisogna immediatamente avvisare tale condizione al proprio gruppo e cominciare (se tatticamente possibile) la RCP.
Un soccorritore/medico potrà poi arrivare per accelerare il ripristino di un ritmo normale con un defibrillatore, ma nella maggioranza dei casi dove il paziente riceve cure quasi subito anche la RCP da un fante normale può bastare.

#### 3. Controlla le vie aeree

Nel caso in cui [sono attivi i moduli KAM di vie aeree e respirazione](#vie-aeree) (airway e breathing), per stabilizzare un paziente bisognerà anche controllare che le vie aeree sono libere (prive di ostruzioni o occlusioni) e che i polmoni e la gabbia toracica del paziente sono integri.

Entrambe le meccaniche hanno a che fare con il sistema KAM di `SpO2`, ovvero l'ossigenazione del sangue del paziente, che idealmente è al 100%. A seconda dei settaggi, valori sotto al 90% possono impossibilitare il rinvenimento (come un volume di sangue ridotto) e valori critici sotto al 60% causano la morte immediata. Un basso livello di SpO2 persistente può prolungare notevolmente i tempi di rinvenimento.

Il valore esatto di SpO2 può essere stimato, mediante l'indicatore di `Cyanosis`/`Cianosi` su arti e testa del paziente, oppure ricavato esattamente mediante l'utilizzo di strumenti come il pulsossimetro o il `Vitals Monitor` integrato nel AED-X.

1. Le vie aeree possono essere:

    - ^^Ostruite/Obstructed^^ da una posizione del corpo stesso, es: la testa che in stato di svenimento si accascia. Tale condizione è **mitigabile** mediante `hyperextension`/`iperestensione` della testa (solo finché si rimane accanto al paziente) oppure risolvibile a tempo prolungato mediante l'utilizzo di `Guedel Tube`/`Canula Guedel` o `King LT`/`Tubo Laringeo` (solo da parte del medico).<br>
    In assenza di utensili (o al fine di non consumarli su lievi feriti) è validissima anche la `Recovery Position`/`Posizione di Sicurezza`, che risolve entrambe le problematiche finché il paziente non viene spostato o medicato con [interazioni che annullano la posizione](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.ch6nvx96t0nv).
    - ^^Occluse/Occluded^^ dalla presenza di fluidi, es: vomito (spesso collegato all'arresto cardiaco). Risolvibile mediante l'utilizzo di una `Manual Suction Pump` (monouso) o del `ACCUVAC` (multiuso più veloce ma anche pesante). In assenza di equipaggiamenti può anche essere effettuato il `Head Turning` per tentare ripetutamente di "scrollare fuori" l'occlusione (richiede più tempo).<br>
    Finché il paziente è svenuto la condizione si può ripetere, quindi conviene prevenirla mediante un `King LT`/`Tubo Laringeo` o la `Recovery Position`/`Posizione di Sicurezza` (che la può anche risolvere direttamente).

2. I polmoni di un paziente (anche conscio) possono presentare lesioni più subdule, diagnosticabili mediante `Inspect Chest` o `Auscultando` il torace con uno stetoscopio, [secondo criteri specifici spiegati nella documentazione](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.cgxm2eh7b3pw). Sono elencate in ordine decrescente di frequenza.

    - ^^Pneumothorax:^^ risolvibile mediante un `Chest Seal` che può applicare chiunque;
    - ^^Tension Pneumothorax:^^ risolvibile da un `Chest Seal` + decompressione con `NDC Kit` o `AAT Kit` da parte di un soccorritore/medico.
    - ^^Hemothorax:^^ risolvibile da un `Chest Seal` + `Drain Fluids`/`Drenare il liquido` mediante un `AAT Kit` da parte di un soccorritore/medico.

#### 4. Agevola il rinvenimento

Una volta stabilizzate le funzioni vitali in modo tale da escludere un eventuale decesso del paziente, si può passare a ridurre il tempo di rinvenimento il più possibile, per liberarsi della zavorra che rappresenta un fante privo di sensi.

Se il SpO2 è ancora molto inferiore alla soglia minima per rinvenire, conviene l'utilizzo del `BVM` (un [pallone AMBU](https://it.wikipedia.org/wiki/Pallone_autoespandibile)) per accelerare il recupero dell'ossigenazione. Esistono due varianti:

- Il `Pocket BVM`/`Maschera AMBU portatile` è una versione più leggera ma meno efficace, utile per i loadout più basilari dei soccorritori.
- Il `BVM`/`Maschera AMBU`, oltre ad essere più efficace, permette l'utilizzo di ossigeno supplementare per potenziare ulteriormente il recupero. Le fonti sono:
    - Bombole portatili di ossigeno (da 150/300l) nel proprio inventario (irrealistico per soccorritori/medici da campo, visto che IRL se colpiti possono detonare).
    - Veicoli/Edifici definiti da ACE3 o l'Editor della missione come medici. Un'interazione su di essi permette anche di riempire una propria bombola portatile.

??? warning "Attenti quando usate il BVM"
    Dato che l'utilizzo di un qualsiasi BVM annulla la posizione di sicurezza, durante l'applicazione può riformarsi un'ostruzione/occlusione se le vie aeree non sono state stabilizzate con un `King LT`/`Tubo Laringeo`. Così ci si accorgerebbe solo dopo aver interrotto l'applicazione che l'SpO2 è rimasto costante oppure calato ulteriormente.<br>
    Per evitare questo spreco di tempo è meglio stabilizzare sempre le vie aeree di pazienti che hanno l'SpO2 abbastanza basso da richiedere un utilizzo prolungato del BVM.

Appena i parametri vitali diventano "stabili" da permettere il rinvenimento, possiamo tentare alcune interazioni sulla testa per svegliare forzatamente il paziente. Altrimenti dovrebbe aspettare la probabilità randomica di rinvenimento.

- `Reorient Patient`/`Stimolare il paziente` effettua uno schiaffo in faccia, non richiede equipaggiamenti specifici.
- `Ammonium Carbonate`/`Carbonato d'ammonio` fa annusare al paziente dei sali da bagno, con probabilità di rinvenimento più alta della stimolazione.

Il soccorritore/medico deve quindi suturare le ferite del paziente in modo da completare la cura. Il paziente stesso è comunque responsabile di ^^verificare la suturazione^^ di tutte le sue ferite e richiederla altrimenti al personale medico più vicino.

Anche eventuali fratture possono essere risolte completamente da un soccorritore/medico, mentre lo `Splint`/`Gessatura` da parte di chiunque può solo ripristinare parzialmente la funzionalità dell'arto.

L'applicazione di antidolorifici ha solo senso se il paziente è conscio e ne ha bisogno, l'applicazione preventiva rischia il prolungamento del rinvenimento e l'eventuale overdose.<br>
Di solito quelli presenti nell'equipaggiamento da fante bastano e avanzano in tutte le situazioni, di conseguenza è meglio che il paziente se li somministri da solo.

!!! warning "Attenti a non andare in overdose da un antidolorifico iniettabile, controllate prima nella "triage card" di non aver già ricevuto uno entro gli ultimi 10 minuti."

## Lo STANAG Medico

Al fine di essere compatibile sia con piccole missioni improvvisate, che con grandi eventi con decine di giocatori, lo STANAG si suddivide in due livelli, uno Base e uno Avanzato.

Entrambi richiedono la combinazione di mod ACE Medical + KAT Medical. La differenza consiste solamente nel numero maggiore di moduli KAM abilitati nel sistema Avanzato rispetto a quello Base.

### Il Sistema Base

??? note "Impostazioni fondamentali in entrambi i livelli"
    Il timeout di decesso dall'arresto cardiaco è di 5 minuti.<br>Il sanguinamento è ridotto con un moltiplicatore del x0.4.<br>Sono abilitate le bende avanzate e la riapertura di ferite non suturate.<br>Le fratture gessate di una gamba ci limitano alla corsa, impedendo lo "scatto".

Per quanto riguarda il fante non-specialista, il sistema base non aggiunge alcun livello di difficoltà rispetto al solo ACE Medical, la presenza della KAM comporta solamente l'aggiunta di funzionalità utili come il risveglio assistito mediante `Reorient Patient`/`Stimolare il paziente` (schiaffo sulla guancia) e la meccanica di coagulazione.

Il personale medico invece può trarre beneficio dall'aggiunta di:

- Defibrillatori (AED e AED-X), utili per ripristinare un ritmo cardiaco normale più velocemente della sola CPR;
- Medicinali avanzati, come antidolorifici più variati e coagulanti (TXA e EACA);
- Feature QOL come la suturazione di tutto il corpo mediante una sola interazione;

Il personale medico deve però considerare anche le seguenti **difficoltà aggiunte**:

- Per iniettare fluidi o farmaci (eccetto autoiniettori) nel corpo del paziente, dovranno prima piazzare uno dei seguenti collegamenti:
    - un collegamento endovenoso in un arto, il `16g IV`;
    - un collegamento intraosseo nello sterno, il `Fast IO`;
- Il [sistema di coagulazione avanzata](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.kftfvmvzcnlk), che accelera la chiusura automatica di ferite (senza richiedere bendaggi). Questa meccanica consuma però certi "fattori coagulanti" nel sangue del paziente, [alcuni fluidi sono più efficaci di altri](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.brf4cmv3xjxe) nel ripristino di questi fattori.
- La somministrazione di coagulanti mediante IV può causare il blocco della cannula se non vengono preceduti da altri fluidi. In quel caso potrete somministrare soluzione salina e effettuare un `saline flush` dal tab "farmaci" per sbloccarla.

### Il Sistema Avanzato

??? note "Impostazioni fondamentali in entrambi i livelli"
    Il timeout di decesso dall'arresto cardiaco è di 5 minuti.<br>Il sanguinamento è ridotto con un moltiplicatore del x0.4.<br>Sono abilitate le bende avanzate e la riapertura di ferite non suturate.<br>Le fratture gessate di una gamba ci limitano alla corsa, impedendo lo "scatto".

I seguenti moduli KAM vengono abilitati dal sistema avanzato, senza modificare gli esistenti settaggi o altre meccaniche del sistema base.

Specifichiamo che con "personale medico" si intende almeno l'abilitazione di "Medico" ACE3. Nello STANAG non esistono per il momento strumenti limitati solo al ruolo di "Dottore" ACE3.

#### Vie Aeree

Abilitate tutte le meccaniche di ostruzione/occlusione, le ultime possono ripetersi ogni 60s (dopo un cooldown di 45s) con probabilità del 10%.

Per stabilizzare le vie aeree può essere applicato un `Guedel Tube`/`Canula Guedel` o `King LT`/`Tubo Laringeo` in 3s (il secondo solo da personale medico).

Per la risoluzione di ostruzioni possono essere usati: `ACCUVAC` per 3s (da personale medico), `Manual Suction Pump` per 5s o `Head Turning` per una probabilità di successo del 20% ogni 5s.

La `Recovery Position`/`Posizione di Sicurezza` può essere applicata in 4s, annullata in 2s e risolvere un'ostruzione in 5s.

#### Respirazione

La condizione di `Cyanosis`/`Cianosi` viene indicata come `Slight`/`Leggera` a SpO2 <90% (minimo per il rinvenimento), `Mild`/`Moderata` a <80% (soglia di svenimento) e `Severe`/`Severa` a <70%. La soglia letale è il 60%.

Abilitati tutti i tipi di condizioni toraciche con descrescente probabilità di occorrenza:

- `Pneumothorax` al 40%<br>
Risolvibile da chiunque mediante un `Chest Seal`;
- `Tension Pneumothorax` al 20%<br>
Risolvibile da personale medico mediante un `Chest Seal` + decompressione con `NDC Kit`/`AAT Kit`;
- `Hemothorax` al 10%<br>
Risolvibile da personale medico mediante un `Chest Seal` + `Drain Fluids`/`Drenare il liquido` con un `AAT Kit`;

!!! warning "Le condizioni NON sono visibili nel menu medico, vanno diagnosticate con lo stetoscopio o mediante Inspect Chest."

Tutte le varianti del `BVM`/`Maschera AMBU` sono utilizzabili da chiunque, anche con ossigeno supplementare.

#### Circolazione

Sono abilitati i ritmi avanzati [come spiegati dalla documentazione](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.bvxbceizzega), con tempo di degradazione massimo di 900s. Probabilità del 70% per `VTac` e del 30% per `PEA`.

Le [condizioni H&T](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.ke7yki3idopn) "hardcore" sono disabilitate.

La RCP ha intervallo di 12s per probabilità di successo (minime-massime) del 30-50% per chiunque, 40-60% per "Medici" e 50-70% per "Dottori" ACE.

Il defibrillatore `AED` ha probabilità di successo (minima-massima) del 45-80%, mentre l'`AED-X` (solo utilizzabile da personale medico) del 60-90%.

Sono abilitati i gruppi sanguigni, essi vengono assegnati randomicamente a tutti ogni volta che entrano in missione. Il settaggio del "proprio gruppo" viene quindi ignorato.

#### Coagulazione

Medesima meccanica già accennata nel [sistema base](#il-sistema-base), impostata come "avanzata" in maniera realistica. TXA/EACA somministrato senza altri fluidi può causare un blocco della cannula.

#### Chirurgia

Le fratture avanzate (composte/pluriframmentarie) sono disabilitate per motivi di giocabilità e realismo (non si effettuano interventi chirurgici di quella scala sul campo).

Sono attive solo le fratture semplici, riducibili da personale medico (non è possibile ridurre da soli le proprie fratture).

#### Altri Sistemi

Il sistema renale e di pH sanguineo è disattivato, così come la PaCO2 e il nuovo sistema di ipotermia (ancora in valutazione).

### Download dei settaggi CBA

<div class="grid cards" markdown>
- :material-chevron-triple-down: [__Sistema Base__](../assets/cba_setting_presets/MEDICAL_BASE.sqf)<br>
  Preset medico base, completo di tutti i settaggi.
</div>
<div class="grid cards" markdown>
- :material-chevron-double-up: [__Override Base :material-arrow-right: Avanzato__](../assets/cba_setting_presets/MEDICAL_AVANZATO_OVERRIDE.sqf)<br>
  Preset con i soli settaggi necessari per abilitare moduli avanzati sovrascrivendoli dalla missione, quando il server è impostato con il preset base.
</div>
<div class="grid cards" markdown>
- :material-chevron-triple-up: [__Sistema Avanzato__](../assets/cba_setting_presets/MEDICAL_AVANZATO.sqf)<br>
  Preset medico avanzato, completo di tutti i settaggi.
</div>
