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

Un fante senza specializzazione può a volte stabilizzare un ferito senza richiedere l'intervento di un soccorritore/medico, ma anche nei casi in cui non gli è possibile sarà comunque in grado di alleggerire il compito al personale medico.

Per questo è importante che ogni fante conosca le fondamenta del sistema medico e settaggi in uso, al fine di accorciare il più possibile i tempi di cura (propri e altrui) e snellire il flusso della missione.

#### Il Soccorritore

Un "mini-medico" a livello di gruppo/squadra che potrà spesso stabilizzare in autonomia pazienti lievi, ma contare sul supporto del medico per casi gravi.

#### Il Medico

Il medico totalmente formato a livello di squadra/plotone, che può supervisionare vari paramedici ai livelli sottostanti e supportarli con il suo equipaggiamento più specialistico. Inoltre potrà assumere la responsabilità in eventi di MCI e dirigere la triage di molteplici feriti, in attesa di un eventuale CASEVAC o MEDEVAC.

### L'ordine di cura

In entrambi livelli dello STANAG (e molte altre missioni impostate diversamente) i settaggi vigenti comportano un ordine di cura ottimale, che riduce la durata di rinvenimento del paziente e la probabilità del decesso ad un minimo.

#### 1. Ferma l'emorragia

L'azione di fermare il dissanguamento è praticamente sempre quella con priorità più alta. Più tempo trascorre e più si dovrà attendere per colmare il volume di fluidi perso mediante flebo. Inoltre, se la perdita di sangue diventa più grave del colore giallo (nel menu medico), sarà impossibile far rinvenire il paziente senza il supporto di personale medico.

Per fermare l'emorragia da arti (braccia/gambe) è spesso preferibile l'utilizzo di un laccio emostatico (anche chiamato "CAT") visto che il tempo di applicazione è molto minore di una qualsiasi benda.

Una ferita bendata può riaprirsi se non viene successivamente suturata da un soccorritore/medico. Alcuni tipi di bende sono più veloci nel tappare ampie ferite, altri sono più longevi prima di permettere la riapertura. [Qui potete trovare una tabella che elenca tali differenze](https://i.imgur.com/yr1hXT4.png).

#### 2. Ristabilisci il battito cardiaco

Emorragie e ferite gravi, in particolare alla testa, possono spesso causare un arresto cardiaco del paziente. Questa condizione può causare la morte entro pochi minuti, a prescindere dal dissanguamento o altre problematiche più apparenti.

Per questo motivo è importante ristabilire un ritmo normale appena possibile, prima di perdere tempo prezioso su azioni minori come la suturazione di ferite bendate.<br>
^^Nel caso specifico in cui un paziente potrebbe già essere in arresto da qualche minuto e la perdita di sangue non è ancora gravissima, lo ristabilimento del ritmo normale diventa prioritario rispetto a fermare prima tutte le emorragie.^^

Tutti possono controllare il battito cardiaco mediante opportune interazioni su arti (senza CAT), petto o testa. È dunque la responsabilità del primo soccorritore, a prescindere dal livello di formazione medica, di controllare che il paziente abbia battito. In caso di assenza bisogna immediatamente avvisare tale condizione al proprio gruppo e cominciare (se tatticamente possibile) la RCP.
Un soccorritore/medico potrà poi arrivare per supportare il ristabilimento di un ritmo normale, ma nella maggioranza dei casi dove il paziente riceve cure quasi subito anche la RCP da un fante normale può bastare.

#### 3. Controlla le vie aeree

Nel caso in cui [sono attivi i moduli KAM di vie aeree e respirazione](#vie-aeree) (airway e breathing), per stabilizzare un paziente bisognerà anche controllare che le vie aeree sono libere (prive di ostruzioni o occlusioni) e che i polmoni e la gabbia toracica del paziente sono integri.

Entrambe le meccaniche hanno a che fare con il sistema KAM di `SpO2`, ovvero l'ossigenazione del sangue del paziente, che idealmente è al 100%. A seconda dei settaggi, valori sotto al 90% possono impossibilitare il rinvenimento (come una volume di sangue ridotto) e valori critici sotto al 60% causano la morte immediata. La persistenza di un SpO2 ridotto può allungare drasticamente i tempi di rinvenimento.

Il valore esatto di SpO2 può essere stimato, mediante l'indicatore di `Cyanosis` su arti e testa del paziente, oppure ricavato esattamente mediante l'utilizzo di strumenti come il pulsossimetro o il `Vitals Monitor` integrato nel AED-X.

1. Le vie aeree possono essere:

    - ^^Ostruite/Obstructed^^ da una posizione del corpo stesso, es: la testa che in stato di svenimento si accascia. Tale condizione è **mitigabile** mediante `hyperextension`/`iperestensione` della testa (solo finché si rimane accanto al paziente) oppure risolvibile a tempo prolungato mediante l'utilizzo di `Guedel Tube`/`Canula Guedel` o `King LT`/`Tubo Laringeo` (solo da parte del medico).<br>
    In assenza di utensili (o al fine di non consumarli su lievi feriti) è validissima anche la `Recovery Position`/`Posizione di Sicurezza`, che risolve entrambe le problematiche finché il paziente non viene spostato o medicato con [interazioni che annullano la posizione](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.ch6nvx96t0nv).
    - ^^Occluse/Occluded^^ dalla presenza di fluidi, es: vomito (spesso collegato all'arresto cardiaco). Risolvibile mediante l'utilizzo di una `Manual Suction Pump` (monouso) da parte di chiunque o del `ACCUVAC` da parte di un soccorritore/medico. Finché il paziente è svenuto la condizione si può ripetere, quindi conviene prevenirla mediante un `King LT`/`Tubo Laringeo` o la `Recovery Position`/`Posizione di Sicurezza`.

2. I polmoni di un paziente (anche conscio) possono presentare lesioni più subdule, diagnosticabili mediante `Inspect Chest` o `Auscultando` il torace con uno stetoscopio, [secondo criteri specifici elencati nella documentazione](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.cgxm2eh7b3pw). Sono elencate in ordine decrescente di frequenza.

    - ^^Pneumothorax:^^ risolvibile mediante un `Chest Seal` che può applicare chiunque;
    - ^^Tension Pneumothorax:^^ risolvibile da un `Chest Seal` + decompressione con `NDC Kit` o `AAT Kit` da parte di un soccorritore/medico.
    - ^^Hemothorax:^^ risolvibile da un `Chest Seal` + `Drain Fluids`/`Drenare il liquido` mediante un `AAT Kit` da parte di un soccorritore/medico.

#### 4. Agevola il rinvenimento


## Lo STANAG Medico

??? note
    Una descrizione dei 2 livelli medici dello STANAG

Al fine di essere compatibile sia con piccole missioni improvvisate, che con grandi eventi con decine di giocatori, lo STANAG si suddivide in due livelli, uno Base e uno Avanzato.

Entrambi richiedono la combinazione di mod ACE Medical + KAT Medical. La differenza consiste solamente nel numero maggiore di moduli KAM abilitati nel sistema Avanzato rispetto a quello Base.

### Il Sistema Base

??? note
    Descrizione di nozioni fondamentali ACE Medical e KAM, considerando solo i moduli abilitati (ben pochi).

Per quanto riguarda il fante non-specialista, il sistema base non aggiunge alcun livello di difficoltà rispetto al solo ACE Medical, la presenza della KAM comporta solamente l'aggiunta di funzionalità utili come il risveglio assistito mediante `Reorient Patient`/`Stimolare il paziente` (schiaffo sulla guancia) e la meccanica di coagulazione.

Il personale medico invece può trarre beneficio dall'aggiunta di:

- Defibrillatori (AED e AED-X), utili per ristabilire un ritmo cardiaco normale più velocemente della sola CPR;
- Medicinali avanzati, come antidolorifici più variati e coagulanti (TXA e EACA);
- Feature QOL come la suturazione di tutto il corpo mediante una sola interazione;

Il personale medico deve però considerare anche le seguenti **difficoltà aggiunte**:

- Per iniettare fluidi o farmaci (eccetto autoiniettori) nel corpo del paziente, dovranno prima piazzare uno dei seguenti collegamenti:
    - un collegamento endovenoso in un arto, il `16g IV`;
    - un collegamento intraosseo nello sterno, il `Fast IO`;
- Il [sistema di coagulazione avanzata](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.kftfvmvzcnlk) permette la chiusura automatica di ferite, senza richiedere bendaggi. Questa meccanica consuma però certi "fattori coagulanti" nel sangue del paziente, [alcuni fluidi sono più efficaci di altri](https://docs.google.com/document/d/1YlY00qoL2gdrbOJJzi5aW19A3HqT7uXflszDYuK7h3M/edit?tab=t.0#heading=h.brf4cmv3xjxe) nel ripristino di questi fattori.
- La somministrazione di coagulanti mediante IV può causare il blocco del collegamento se non vengono preceduti da altri fluidi. In quel caso potrete somministrare soluzione salina e effettuare un `saline flush` dal tab "farmaci" per sbloccare il collegamento.

<div class="grid cards" markdown>
- :fontawesome-solid-chevron-down: [__Sistema Base__](../assets/cba_setting_presets/MEDICAL_BASE.sqf)<br>
  Preset medico base, completo di tutti i settaggi.
</div>

### Il Sistema Avanzato

I seguenti moduli KAM vengono abilitati dal sistema avanzato, senza modificare gli esistenti settaggi o altre meccaniche del sistema base.

#### Vie aeree

Vie aeree

#### Polmoni

Polmoni

#### Ritmi avanzati

Ritmi cardiaci avanzati

#### Coagulazione

Medesima meccanica già accennata nel [sistema base](#il-sistema-base), 

<div class="grid cards" markdown>
- :fontawesome-solid-chevron-up: [__Sistema Avanzato__](../assets/cba_setting_presets/MEDICAL_AVANZATO.sqf)<br>
  Preset medico avanzato, completo di tutti i settaggi.
- :fontawesome-solid-chevron-up: [__Override Base :material-arrow-right: Avanzato__](../assets/cba_setting_presets/MEDICAL_AVANZATO_OVERRIDE.sqf)<br>
  Preset con solo i settaggi per abilitare moduli avanzati sovrascrivendoli dalla missione, quando il server è impostato con il preset base.
</div>
