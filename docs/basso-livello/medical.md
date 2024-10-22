---
template: home.html
title: Sistema Medico
---

# Sistema Medico

## Concetti generali

A prescindere dalle mod e i settaggi esatti in uso, esistono dei concetti generali utili a medicare altri giocatori in missione in maniera efficiente.

### L'ordine di cura

In entrambi livelli dello STANAG (e molte altre missioni impostate diversamente) i settaggi vigenti comportano un ordine di cura ottimale, che riduce la durata di rinvenimento del paziente e la probabilità del decesso ad un minimo.

1. **Ferma l'emorraggia**

2. **Ristabilisci il battito cardiaco**

3. **Controlla le vie aeree**

4. **Agevola il rinvenimento**

### I Ruoli

#### Il Fante

Un fante senza specializzazione può a volte stabilizzare un ferito senza richiedere l'intervento di un soccorritore/medico, ma anche nei casi in cui non gli è possibile sarà comunque in grado di alleggerire il compito al personale medico.
Per questo è importante che ogni fante conosca le fondamenta del sistema medico e settaggi in uso, al fine di accorciare il più possibile i tempi di cura (propri e altrui) e snellire il flusso della missione.

#### Il Soccorritore

Un "mini-medico" a livello di gruppo/squadra che potrà spesso stabilizzare in autonomia pazienti lievi, ma contare sul supporto del medico per casi gravi.

#### Il Medico

Il medico totalmente formato a livello di squadra/plotone, che può supervisionare vari paramedici ai livelli sottostanti e supportarli con il suo equipaggiamento più specialistico. Inoltre potrà assumere la responsabilità in eventi di MCI e dirigere la triage di molteplici feriti, in attesa di un eventuale CASEVAC o MEDEVAC.

## Lo STANAG Medico

??? note
    Una descrizione dei 2 livelli medici dello STANAG

Al fine di essere compatibile sia con piccole missioni improvvisate, che con grandi eventi con decine di giocatori, lo STANAG si suddivide in due livelli, uno Base e uno Avanzato.

Entrambi richiedono la combinazione di mod ACE Medical + KAT Medical. La differenza consiste solamente nel numero maggiore di moduli KAM abilitati nel sistema Avanzato rispetto a quello Base.

### Il Sistema Base

??? note
    Descrizione di nozioni fondamentali ACE Medical e KAM, considerando solo i moduli abilitati (ben pochi).

Per quanto riguarda il fante non-specialista, il sistema base non aggiunge alcun livello di difficoltà rispetto al solo ACE Medical, la presenza della KAM comporta solamente l'aggiunta di funzionalità utili come il risveglio assistito mediante "riorientamento" (schiaffo sulla guancia) e la meccanica di coagulazione.

Il personale medico invece può trarre beneficio dall'aggiunta di:

- Defibrillatori (AED e AED-X), utili per ristabilire un ritmo cardiaco normale più velocemente della sola CPR;
- Medicinali avanzati, come antidolorifici più variati e coagulanti (TXA e EACA);
- Feature QOL come la suturazione di tutto il corpo mediante una sola interazione;

Il personale medico deve però considerare anche le seguenti **difficoltà aggiunte**:

- Per iniettare fluidi o farmaci (eccetto autoiniettori) nel corpo del paziente, dovranno prima piazzare uno dei seguenti collegamenti:
    - un collegamento endovenoso in un arto, il `16g IV`;
    - un collegamento intraosseo nello sterno, il `Fast IO`;
- Il sistema di coagulazione avanzata permette la chiusura automatica di ferite, senza richiedere bendaggi. Questa meccanica consuma però certi "fattori coagulanti" nel sangue del paziente, certi fluidi sono più efficaci di altri nel ripristino di questi fattori. **Link a documentazione KAM**
- La somministrazione di coagulanti mediante IV può causare il blocco del collegamento se non vengono preceduti da soluzione salina. In quel caso potrete somministrare soluzione salina e effettuare un `"saline flush"` dal tab "farmaci" per sbloccare il collegamento.

<div class="grid cards" markdown>
- :fontawesome-solid-chevron-down: [__Sistema Base__](../assets/cba_setting_presets/MEDICAL_BASE.sqf)<br>
  Preset medico base, completo di tutti i settaggi.
</div>

### Il Sistema Avanzato

??? note
    Descrizione dei moduli KAM aggiunti dal livello avanzato.

#### Vie aeree

Vie aeree

#### Polmoni

Polmoni

#### Ritmi avanzati

Ritmi cardiaci avanzati

#### Coagulazione

Coagulazione

<div class="grid cards" markdown>
- :fontawesome-solid-chevron-up: [__Sistema Avanzato__](../assets/cba_setting_presets/MEDICAL_AVANZATO.sqf)<br>
  Preset medico avanzato, completo di tutti i settaggi.
- :fontawesome-solid-chevron-up: [__Override Base :material-arrow-right: Avanzato__](../assets/cba_setting_presets/MEDICAL_AVANZATO_OVERRIDE.sqf)<br>
  Preset con solo i settaggi per abilitare moduli avanzati sovrascrivendoli dalla missione, quando il server è impostato con il preset base.
</div>
