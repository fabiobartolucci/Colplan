# Lingottiere a placche nella colata DC

## Architettura e principi fisici della lingottiera a placche

La lingottiera a placche in un impianto DC casting non è un semplice contenitore geometrico, ma un vero e proprio scambiatore di calore ad altissimo flusso termico accoppiato a un sistema di formatura idrodinamica. La sua funzione primaria è estrarre il calore latente di fusione e il calore sensibile dal metallo liquido, generando una "pelle" solida autoportante (shell) in grado di contenere il nucleo ancora liquido (il bacino liquido o sump) durante la discesa controllata sul tavolino di partenza (bottom block).

Il bilancio termico si divide in due zone distinte:

- **Raffreddamento Primario (All'interno della lingottiera)**: Estrae circa il 10 – 15 % del calore totale. Ha il compito critico di formare la pelle iniziale. Un'estrazione troppo lenta porta allo sfondamento della pelle (breakout); un'estrazione troppo violenta o non uniforme causa tensioni termiche eccessive e cricche superficiali.
- **Raffreddamento Secondario (Subito sotto la lingottiera)**: Estrae l'85 – 90 % del calore residuo tramite getti d'acqua diretti sulla superficie della placca appena uscita dallo stampo. Qui la gestione del film d'acqua e del fenomeno di ebollizione (transizione dal regime nucleato a quello pellicolare o Leidenfrost) determina la profondità del bacino liquido e la struttura cristallina finale.

## Materiali, geometria e trattamenti superficiali

### Scelta dei materiali

Il corpo della lingottiera è realizzato quasi esclusivamente in leghe di rame ad alta conducibilità termica e buone caratteristiche meccaniche a caldo per evitare deformazioni termiche (thermal warping):

- **CuCrZr (Rame-Cromo-Zirconio)**: La lega più diffusa. Offre un ottimo compromesso tra conducibilità termica (≈ 320 – 340 W/(m·K)) e resistenza a trazione/snervamento ad alte temperature.
- **CuAg (Rame-Argento)**: Utilizzata per applicazioni estreme dove è richiesta una stabilità termica superiore senza penalizzare la conducibilità termica.

### Trattamenti galvanici superficiali

Il rame puro o legato reagisce chimicamente con l'alluminio liquido formando composti intermetallici fragili e causando fenomeni di incollaggio (soldering). Per ovviare a ciò, le pareti interne della lingottiera subiscono trattamenti galvanici multistrato:

- **Nichelatura Chimica o Elettrolitica (Ni)**: Fornisce durezza superficiale e riduce l'affinità chimica con l'alluminio.
- **Cromatura Dura (Cr)**: Spesso applicata sopra il nichel per aumentare la resistenza all'usura abrasiva causata dallo sfregamento della pelle di alluminio in discesa.
- **Rivestimenti Compositi (Ni-Graphite o Ni-Co)**: Introdotti in impianti avanzati per abbassare il coefficiente d'attrito dinamico tra la parete della lingottiera e la placca in formazione.

### Geometria e conicità (taper)

Le pareti delle lingottiere a placche presentano una conicità geometrica calcolata millimetricamente (espressa in millimetri per metro di altezza, tipicamente tra 0,8 e 1,5 mm/m per faccia).
- **Motivazione**: L'alluminio, passando dallo stato liquido a quello solido, subisce una contrazione volumetrica significativa (≈ 6 – 8 %). La conicità della lingottiera segue esattamente il profilo di ritiro termico della pelle metallica, garantendo un contatto termico ottimale nella parte superiore (dove serve il massimo scambio termico) e riducendo l'attrito meccanico nella parte inferiore, dove la pelle si stacca progressivamente dalla parete di rame.

## Alimentazione e gestione del flusso (hot top e distribuzione)

Il modo in cui il metallo liquido entra nella lingottiera determina la qualità interna della placca. I sistemi moderni utilizzano configurazioni a testa calda (Hot Top):

- **Canali e Distributori (Tundish / Bagged Systems)**: Il metallo arriva dal forno di colata attraverso canalizzazioni riscaldate per evitare cadute termiche indesiderate.
- **Filtrazione in Linea**: L'utilizzo di filtri ceramici in schiuma di allumina (generalmente tra 30 e 50 PPI) è obbligatorio per trattenere le inclusioni di scorie, ossidi di magnesio (spinelli) e particelle intermetalliche.
- **Controllo del Livello Metallo**: Regolato da valvole a spillo, paratoie refrattarie o sistemi basati su sensori elettromagnetici di livello. Un livello costante (oscillazioni millimetriche) previene difetti superficiali da sbordatura o discontinuità di raffreddamento.
- **Sacchetti di Distribuzione (Hot Top Bags / Compo-bags)**: Realizzati in fibra refrattaria porosa, distribuiscono il flusso di metallo in modo laminare e uniforme lungo il perimetro della lingottiera, riducendo i moti convettivi turbolenti che potrebbero danneggiare la sottile pelle iniziale in fase di formazione.

## Dinamica del bacino liquido e struttura solidificata

Il bacino liquido (sump) è la zona di metallo fuso racchiusa all'interno della placca solida in corso di estrazione. La sua forma (profondità e profilo) è il risultato del bilancio tra il calore entrante dal flusso di colata e il calore estratto dal sistema di raffreddamento.
- **Profondità del Sump**: Dipende direttamente dalla velocità di colata, dallo spessore della placca e dalla temperatura del bagno. Un sump troppo profondo aumenta drasticamente il rischio di segregazione centrale (arricchimento di elementi leganti come il Magnesio o il Silicio al centro della placca) e di cricche a caldo nel tratto finale di solidificazione (mushy zone).
- **Fronte di Solidificazione**: Si divide in:
  - **Zona di transizione (Mushy Zone)**: Intervallo bifasico (liquido + solido) governato dall'intervallo di solidificazione della lega (es. 590 – 645 °C per la lega 5754).
  - **Grani Colonnari vs. Equassici**: Un forte gradiente termico iniziale favorisce la crescita di grani colonnari orientati verso il centro. L'immissione di affinatori del grano (es. leghe madri Al-Ti-B) promuove la nucleazione eterogenea, trasformando la struttura in grani equassici fini, essenziali per prevenire cricche e garantire proprietà meccaniche isotrope nella successiva deformazione plastica (laminazione).

## Idraulica e fluidodinamica del raffreddamento secondario

Il sistema di raffreddamento secondario è il cuore operativo della sicurezza e della qualità geometrica del DC casting.
- **Disposizione degli Ugelli (Water Box / Spray Rings)**: L'acqua viene spruzzata sulla placca appena esce dalla lingottiera tramite una serie di fori calibrati o ugelli a cono/ventaglio disposti su più file o anelli perimetrali.
- **Ottimizzazione dei Flussi per Faccia**: Nelle placche larghe (rolling slabs), il rapporto d'aspetto tra faccia larga e faccia stretta impone un differenziale di raffreddamento. Gli angoli della placca tendono a raffreddarsi più rapidamente rispetto al centro delle facce larghe (per effetto bidimensionale del calore). Per evitare tensioni che causano fessurazioni d'angolo, i flussi d'acqua vengono sagomati e parzializzati (maggiore intensità al centro delle facce larghe, minore o controllata sugli angoli).
- **Regime Termoidraulico**: L'obiettivo è evitare il cosiddetto "shock termico incontrollato" che porterebbe a tensioni residue inaccettabili o, nel peggiore dei casi, all'esplosione per contatto diretto di grandi volumi d'acqua con il metallo fuso in caso di sfondamento della pelle (water explosion hazard).

## Lubrificazione della lingottiera

Per ridurre l'attrito radente tra la pelle di alluminio in solidificazione e le pareti rivestite della lingottiera, si ricorre a sistemi di lubrificazione continua:

- **Olii di Colata Sintetici o Semi-sintetici**: Oli specifici ad alto punto di fiamma che non si degradano istantaneamente a contatto con il rame caldo.
- **Modalità di Iniezione**: L'olio viene pompato attraverso micro-fori calibrati o inserti in bronzo sinterizzato porosi posti nella parte superiore della lingottiera, creando un velo lubrificante microscopico che previene grippaggi, graffi longitudinali superficiali e strappi della pelle.

## Difettologia metallurgica e superficiale delle placche

Una gestione errata anche minima dei parametri della lingottiera a placche genera difetti macroscopici e microscopici irreversibili:

- **Cricche a Caldo (Hot Tearing / Cracking)**: Fratture intergranulari che si verificano nella zona pastosa (mushy zone) durante le fasi finali della solidificazione, causate da contrazioni impedite e scarsa resistenza meccanica ad alte temperature. Si combattono riducendo la velocità di colata, ottimizzando l'affinamento del grano e bilanciando il raffreddamento secondario.
- **Segregazione di Centrogetto (Centerline Segregation)**: Concentrazione anomala di soluti ed elementi eutettici al centro dello spessore della placca, dovuta al movimento del liquido residuo arricchito all'interno del sump profondo.
- **Segni di Oscillazione e Segni di Colata (Bleed Marks / Oscillation Marks)**: Solchi o discontinuità orizzontali sulla superficie della placca causati da micro-arresti o vibrazioni meccaniche del sistema di estrazione o da fluttuazioni del livello di metallo nel hot top.
- **Inclusioni di Ossido (Bifilms / Oxide Skins)**: Film di ossido (es. MgO o Al₂O₃) intrappolati nel metallo durante il colaggio a causa di turbolenze nel distributore o nella lingottiera, che agiscono come inneschi di cricca durante la laminazione successiva.
- **Pelle Fredda / Sfondamenti (Cold Shuts & Breakouts)**: I cold shuts si verificano quando il metallo lambisce la lingottiera a temperatura troppo bassa, creando pieghe superficiali non saldate. I breakouts (catastrofici) avvengono quando la pelle solida si rompe all'uscita della lingottiera, facendo fuoriuscire il metallo liquido ad alta temperatura nel pozzo di colata.
