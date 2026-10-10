# Sistema di discesa verticale e pozzo di colata

## Architettura e meccanica del sistema di discesa verticale (Dropping Unit)

Il gruppo di discesa verticale movimenta il tavolo di partenza (bottom block o starting head), la struttura iniziale su cui viene colato il metallo per formare la testa della placca, e sostiene progressivamente tutto il peso della placca man mano che questa solidifica e scende.

**Tipologie di Attuazione**

- **Cilindri Idraulici Telescopici**: La soluzione più robusta e diffusa per impianti di grandi dimensioni (placche pesanti). Garantiscono una spinta e un controllo fluidodinamico eccellenti, ma richiedono centraline oleodinamiche complesse ad altissima pressione con oli speciali ignifughi per prevenire rischi in caso di perdite vicino al metallo fuso.
- **Sistemi Elettromeccanici a Vite a Ricircolazione di Sfere o Cremagliera**: Azionati da motori brushless ad alta coppia con riduttori epicicloidali di precisione. Offrono un controllo della velocità estremamente lineare e privo delle micro-pulsazioni tipiche dei circuiti idraulici, migliorando la qualità superficiale della placca.
- **Guide e Parallelismo**: Il carro di discesa scorre su colonne di guida verticali massicce o su guide prismatiche precaricate. Il parallelismo tra il tavolo di partenza e la lingottiera deve essere perfetto (tolleranze inferiori al decimo di millimetro su corse di diversi metri). Un disallineamento o una minima torsione causerebbero un attrito anomalo di una faccia della placca contro la lingottiera, portando a grippaggi o sfondamenti (breakouts).

## Sincronizzazione dinamica: velocità di caduta vs. solidificazione

La velocità di "vertical fall" non è costante o casuale, ma è il parametro cinematico fondamentale che si interseca con il bilancio termico:

- **Legge di Conservazione della Massa**: La velocità di discesa verticale deve bilanciare esattamente la portata massica del metallo liquido in ingresso nella lingottiera.
- **Profondità del Sump**: Se la velocità di caduta aumenta improvvisamente, il bacino liquido tende a salire o ad assottigliarsi pericolosamente; se diminuisce troppo, il sump si approfondisce, aumentando il rischio di centerline cracking (cricche al centro) e segregazione macroscopica, tipica delle leghe alto-allegate al magnesio come la 5754.
- **Rampe di Accelerazione (Start-up e Fine Corsa)**: La fase di inizio colata (starting phase) richiede una rampa di discesa estremamente lenta e controllata (fase di formazione della testa della placca sul ceppo di partenza), seguita da un'accelerazione graduale fino a raggiungere la velocità di regime (steady-state). Analogamente, la fase finale di arresto richiede una decelerazione calibrata per evitare accumuli di metallo liquido non solidificato.

## Il pozzo di colata (Casting Pit) e l'altezza di caduta

Considerando che una placca in alluminio per laminazione può raggiungere lunghezze comprese tra i 3 e i 6 metri (e in alcuni impianti industriali avanzati anche superiori), il sistema di caduta verticale opera all'interno di un'infrastruttura civile imponente: il pozzo di colata.

- **Profondità Strutturale**: Il pozzo si sviluppa interamente sotto il livello del suolo (spesso tra gli 8 e i 14 metri di profondità).
- **Gestione dell'Acqua e dei Volumi**: Nel pozzo si raccoglie l'ingente quantità d'acqua utilizzata per il raffreddamento secondario (spray). Il fondo del pozzo deve essere progettato per drenare istantaneamente l'acqua e impedire ristagni che potrebbero generare reazioni violente in caso di emergenza.
- **Impermeabilità e Falde**: Trovandosi molto in profondità, la struttura in cemento armato del pozzo deve resistere alla spinta idrostatica della falda acquifera circostante, spesso mediante vasche a tenuta stagna e doppi fondi ispezionabili.

## Sistemi di sicurezza critici: il rischio di "Caduta Libera" (Uncontrolled Fall)

Il pericolo più catastrofico in un impianto di colata continua verticale è il cedimento del sistema di sostegno della discesa verticale.

- **Il Pericolo Termico (Steam Explosion)**: Se per un guasto meccanico o idraulico il carro dovesse precipitare liberamente (free fall) nel pozzo, la placca calda finirebbe completamente sommersa dall'acqua di raffreddamento a velocità elevatissima. Questo provocherebbe la vaporizzazione istantanea di enormi volumi d'acqua, generando un'esplosione da vapore (physical/steam explosion) in grado di distruggere l'intero capannone e mettere a repentaglio la vita degli operatori.

**Dispositivi di Sicurezza Obbligatori**

- **Valvole di Blocco Pilota (Safety Holding Valves)**: Montate direttamente sui cilindri idraulici per bloccare istantaneamente il fluido in caso di rottura dei tubi di mandata.
- **Freni Meccanici di Emergenza (Anti-drop Mechanical Catches)**: Sistemi a denti di arresto o pinze meccaniche automatiche a scatto rapido disposte lungo le colonne di guida, capaci di bloccare meccanicamente il carro in frazioni di secondo se la velocità di discesa supera la soglia di sicurezza impostata.
- **Sistemi di Monitoraggio della Velocità (Encoder Ridondati)**: Controllano millimetricamente che la discesa avvenga con la precisione richiesta, arrestando immediatamente il flusso di metallo al minimo scostamento anomalo.

## Impatto della caduta verticale sulla qualità della placca

Ogni imperfezione meccanica nel movimento di discesa verticale si imprime indelebilmente sulla struttura cristallina e superficiale del metallo:

- **Segni di Oscillazione (Stutter Marks)**: Se il sistema di discesa soffre di vibrazioni torsionali o di scorrimento non uniforme (attriti a secco sulle guide), sulla superficie della placca compaiono segni orizzontali periodici. Nel caso della lega 5754, questi segni possono innescare tensioni locali che riducono la resistenza della pelle durante la deformazione a caldo successiva (laminazione a caldo).
- **Linearità dell'Asse**: La precisione millimetrica della discesa verticale garantisce che la placca mantenga una sezione trasversale perfettamente costante, evitando fenomeni di svergolamento (warping) strutturale dovuti a tensioni interne asimmetriche indotte da una discesa non perfettamente ortogonale rispetto ai flussi d'acqua della lingottiera.

# Difetti metallurgici e cause di rottura delle placche

## Parte prima: i difetti metallurgici e strutturali delle placche

I difetti delle placche per laminazione derivano da un'alterazione dei campi termici, da problemi fluidodinamici nel bacino liquido (sump) o da un controllo inadeguato della composizione e della chimica del fuso.

### Cricche a caldo (Hot Tearing / Hot Cracking)

Rappresentano il difetto più critico e temuto nella colata continua delle leghe della serie 5xxx (come il 5754), che possiedono un intervallo di solidificazione moderatamente ampio (590 – 645 °C).

**Cricche Centrali (Centerline Cracking)**

- **Descrizione**: Fratture intergranulari che si sviluppano lungo l'asse longitudinale centrale dello spessore della placca, nella fase finale della solidificazione (all'interno della zona pastosa o mushy zone).
- **Cause Metallurgiche**: Si verificano quando i grani cristallini in crescita si scontrano e non c'è più sufficiente liquido residuo arricchito di soluti (Mg, Si) per bagnare i bordi grano e compensare il ritiro volumetrico. Le tensioni di trazione indotte dalla contrazione termica superano la resistenza meccanica a caldo dei bordi grano.
- **Fattori scatenanti**: Velocità di colata troppo elevata (che approfondisce eccessivamente il sump), surriscaldamento eccessivo del metallo in ingresso, o un inefficace affinamento del grano (carenza di nuclei eterogenei da leghe madri Al-Ti-B).

**Cricche d'Angolo e Superficiali**

- **Descrizione**: Lesioni longitudinali o trasversali che originano sugli spigoli vivi della placca.
- **Cause**: Gli angoli subiscono una bidirezionalità di raffreddamento (cedono calore su due facce ortogonali), raffreddandosi molto più rapidamente rispetto al centro delle facce larghe. Ciò genera gradienti di contrazione termica estremi e tensioni di taglio che lacerano la pelle metallica appena formata.

### Porosità (Da Gas e Da Ritiro)

**Porosità da Idrogeno (H₂)**

- **Descrizione**: Vescichette sferiche di gas distribuite nella massa o concentrate verso il centro della placca. L'idrogeno è l'unico gas con una solubilità significativa nell'alluminio liquido, ma la sua solubilità crolla bruscamente al momento del passaggio dallo stato liquido a quello solido (rapporto circa 1:20).
- **Cause**: Trattamento di degasaggio in linea insufficiente, umidità nei refrattari dei canali o nei flussi di gas inerte (Ar/N2), o turbolenze nel distributore che inglobano aria umida.

**Porosità da Ritiro (Shrinkage Porosity)**

- **Descrizione**: Cavità a forma irregolare (macro o micro) localizzate tipicamente nelle zone assiali o terminali del sump.
- **Cause**: Compensazione inadeguata del ritiro di solidificazione (≈ 6 – 8 %). Se il metallo liquido non riesce a fluire attraverso i canali dendritici ormai stretti della mushy zone per alimentare le zone sottostanti, si formano vuoti interni non riempiti.

### Segregazioni macrostrutturali

**Segregazione di Centrogetto (Centerline Segregation)**

- **Descrizione**: Un'anomalia chimica per cui la concentrazione degli elementi leganti (specialmente il Magnesio nella lega 5754) aumenta significativamente nella zona centrale dello spessore della placca rispetto al valore nominale della lega.
- **Cause**: Movimenti convettivi e pompaggio meccanico del liquido arricchito di soluti all'interno di un sump troppo profondo e appuntito. Durante la solidificazione frazionata, i soluti vengono espulsi dai fronti dendritici e trascinati verso il fondo del bacino liquido.

**Segregazione Inversa (Inverse Segregation)**

- **Descrizione**: Arricchimento di soluti basso-fondenti direttamente sullo strato superficiale o subsuperficiale della placca.
- **Cause**: Fenomeni di espulsione del film liquido eutettico attraverso i canali dendritici verso la parete fredda della lingottiera a causa della contrazione della pelle solida.

### Inclusioni non metalliche e film di ossido (Bifilms)
- **Descrizione**: Frammenti solidi inclusi nella matrice di alluminio, costituiti principalmente da ossidi di magnesio (MgO, spinelli) o particelle refrattarie staccate dai canali e dai filtri.
- **Cause**: Nel caso della lega 5754, la forte affinità chimica del Magnesio con l'ossigeno atmosferico provoca la rapida formazione di pellicole di ossido sulla superficie del bagno fuso se questo non è protetto da coperture gassose inerti o flussi idonei. Se queste pellicole vengono frammentate e trascinate nel flusso di colata, formano i cosiddetti bifilms (pellicole doppie racchiuse da un sottile strato d'aria microscopico), che agiscono come pericolosissimi inneschi di cricca durante la successiva deformazione plastica (laminazione a caldo o estrusione).

## Parte seconda: cause di rottura e guasti catastrofici nel pozzo di colata

Le rotture strutturali non riguardano solo il metallo in solidificazione, ma anche eventi critici che coinvolgono l'intero sistema meccanico, idraulico e termico del pozzo di colata.

### Sfondamento della pelle (Breakout)

È l'incidente più grave e pericoloso che possa verificarsi in un impianto DC casting.

- **Dinamica**: La pelle solida formatasi all'interno della lingottiera si rompe meccanicamente sotto lo stampo, permettendo al metallo liquido ancora presente nel bacino interno di fuoriuscire violentemente e riversarsi senza controllo nel pozzo di colata e nell'acqua di raffreddamento.

**Cause Principali**

- **Deficit di Raffreddamento Primario**: Portata d'acqua nella lingottiera insufficiente o ostruita da depositi calcarei, che impedisce la rapida solidificazione della pelle iniziale.
- **Attrito Eccessivo (Grippaggio)**: Perdita di efficacia del sistema di lubrificazione a olio o usura del trattamento superficiale (nichelatura/cromatura) della lingottiera, che frena bruscamente la discesa della placca lacerando la pelle sottile.
- **Fluttuazioni Termiche del Bagno**: Un improvviso calo della temperatura del metallo in arrivo dal forno provoca una solidificazione anomala e irregolare sulle pareti dello stampo.
- **Errori di Velocità**: Accelerazione improvvisa del carro di discesa verticale (dropping unit) che supera la velocità di formazione della pelle metallica.

### Rottura per tensioni residue e svergolinamento (Thermal Warping & Spontaneous Cracking)
- **Dinamica**: La placca, una volta completata la colata e estratta dal pozzo, subisce tensioni interne talmente elevate da deformarsi elasticamente/plasticamente in modo marcato (warping) o, nei casi estremi, da fratturarsi spontaneamente di schianto (spesso durante le operazioni successive di intestatura e taglio con sega circolare).

**Cause Principali**

- **Raffreddamento Secondario Asimmetrico**: Se gli ugelli del sistema di spruzzatura dell'acqua attorno alla lingottiera sono parzialmente intasati o disallineati, una faccia della placca o un angolo si raffredda molto più velocemente dell'opposta.
- **Gradienti Termici Estremi**: Differenze di temperatura troppo marcate tra il nucleo interno (ancora caldo e a lento raffreddamento) e la periferia esterna (raffreddata bruscamente dall'acqua), che generano campi di tensioni di trazione superficiali e compressione interna insostenibili per la struttura cristallina.

### Incollaggio metallurgico (Soldering / Sticking)
- **Dinamica**: L'alluminio liquido stabilisce un legame chimico diretto con il rame del corpo della lingottiera, fondendosi letteralmente con essa.

**Cause Principali**

- Consumo totale o assenza localizzata del riporto protettivo galvanico (Nichel/Cromo) sulle pareti interne della lingottiera.
- Temperatura di colata eccessivamente elevata che surriscalda localmente il rame, distruggendo il film lubrificante e attivando la bagnabilità del rame da parte dell'alluminio fuso.
- **Conseguenze**: Strappo profondo della superficie della placca, solchi longitudinali marcati e blocco meccanico immediato del sistema di discesa (con conseguente alto rischio di breakout).

### Cedimento strutturale del sistema di sospensione (Free Fall / Mechanical Collapse)
- **Dinamica**: Cedimento strutturale o idraulico del carro di discesa verticale (dropping unit) che sostiene il tavolo di partenza e l'intera massa della placca (che può pesare diverse tonnellate).

**Cause Principali**

- Rottura di tubazioni oleodinamiche ad alta pressione a causa di fatica o vibrazioni in prossimità del calore del pozzo.
- Guasto ai sistemi di controllo elettronico della sincronizzazione o blocco meccanico delle guide di scorrimento.
- **Conseguenze Catastrofiche**: La caduta incontrollata della placca rovente nel pozzo pieno d'acqua provoca il contatto immediato di grandi superfici di metallo liquido/caldo con l'acqua a velocità elevatissima, innescando una violenta esplosione da vapore (steam explosion), caratterizzata dalla conversione istantanea dell'acqua in vapore ad altissima pressione in grado di distruggere le strutture edilizie dell'impianto. Per questa ragione, i pozzi moderni sono dotati di valvole di blocco idraulico pilotate e freni meccanici di emergenza indipendenti a presa rapida.

# Gestione delle scorie (dross)

## Tipologie di scorie nell'industria dell'alluminio

Le scorie prodotte negli impianti di fusione, trattamento e colata dell'alluminio si suddividono principalmente in due categorie:

- **Scorie Bianche (White Dross)**: Si formano nei forni di fusione, nei canali di trasferimento (launders) e nei sistemi di testa calda (hot top) in assenza di sali di copertura o per semplice ossidazione superficiale del metallo liquido a contatto con l'atmosfera del forno. Hanno un alto contenuto di alluminio metallico libero intrappolato (spesso dal 30 % fino al 70 %).
- **Scorie Nere o Salate (Black Dross / Salt Slags)**: Si generano nei processi di rifusione di rottami secondari in cui vengono impiegati fondenti salini (miscele di cloruro di sodio e cloruro di potassio, NaCl-KCl) con aggiunta di fluoruri per proteggere il bagno liquido dall'ossidazione e sciogliere i film di ossido. Contengono una frazione metallica inferiore (10 – 25 %), una matrice di sali fusi e ossidi.

## Composizione chimica e mineralogica

La composizione delle scorie varia in base alla lega trattata e alla tecnologia del forno. Nel caso delle leghe della serie 5xxx (contenenti Magnesio), la composizione chimica è peculiare:

Componenti Principali:

- **Alluminio Metallico (Al)**: Gocce, film e scaglie di metallo puro intrappolate meccanicamente nella matrice ossidata.
- **Allumina (Al₂O₃)**: Ossido di alluminio formatosi per reazione termica con l'ossigeno atmosferico o l'umidità dei rivestimenti refrattari.
- **Ossido di Magnesio (MgO) e Spinelli (MgAl₂O₄)**: Cruciale per la lega 5754. Il magnesio ha un'affinità chimica con l'ossigeno nettamente superiore a quella dell'alluminio. A temperature di fusione, il magnesio affiora in superficie e si ossida rapidamente, formando una crosta polverosa, voluminosa e secca composta da MgO e da spinello di alluminio e magnesio (MgO · Al₂O₃). Questo strato accelera l'ossidazione se non controllato.
- **Sali Estranei / Fondenti (nelle scorie nere)**: Miscele di NaCl (40 – 50 %), KCl (40 – 50 %) e piccole percentuali di criolite o fluoruro di calcio (CaF₂, 2 – 5 %) usate per abbassare il punto di fusione delle scorie e fluidificare i sali.

## Origine e meccanismi di formazione negli impianti

La generazione delle scorie è un processo fisico-chimico inevitabile che avviene attraverso diversi stadi:

- **Ossidazione Primaria**: Quando il lingotto o il rottame viene fuso, o quando il metallo liquido è esposto all'aria nei forni di attesa o nei canali, l'ossigeno dell'aria reagisce formando una pellicola superficiale continua. Nelle leghe al magnesio (5754), questa pellicola tende a ispessirsi rapidamente se non protetta da un'atmosfera inerte (es. azoto o miscele con esafluoruro di zolfo SF₆, se consentito) o da sali protettivi.
- **Intrappolamento Meccanico**: Durante le fasi di mescolamento (stirring), travaso, colaggio o turbolenze nei distributori, la crosta di ossido superficiale viene trascinata e frammentata all'interno del volume del bagno liquido, inglobando gocce di metallo puro. Questo forma il cosiddetto dross bagnato o pesante.

## Gestione operativa, trattamento e skimming (Scostatura)

La gestione delle scorie all'interno dello stabilimento richiede protocolli di sicurezza rigorosi a causa della forte esotermicità dell'ossidazione dell'alluminio e del magnesio.

### Operazione di skimming (Scostatura)
- Consiste nella rimozione meccanica della crosta di scoria accumulata sulla superficie del bagno nei forni o nei colatoi.
- Viene eseguita utilizzando spatole raschiatrici (manuali o montate su bracci meccanici automatizzati).
- **Uso di polveri esotermiche/coprenti**: Prima dello skimming, vengono spesso applicate polveri coprenti (fluxes) che reagiscono esotermicamente per separare il metallo liquido intrappolato nella scoria, facendolo colare nuovamente nel bagno, e riducendo la scoria a una polvere secca e povera di metallo.

### Raffreddamento e spegnimento delle scorie (Dross Cooling)
- Le scorie appena estratte dal forno sono a temperature elevatissime (≈ 700 – 800 °C). Poiché contengono alluminio e magnesio metallico libero, se lasciate all'aria aperta in presenza di umidità o ossigeno possono innescare una reazione esotermica incontrollata (auto-combustione) che brucia il metallo residuo raggiungendo temperature superiori a 1000 °C e sprigionando fumi densi di ossidi.
- **Sistemi di raffreddamento**: Le scorie calde vengono immediatamente trasferite in contenitori di raffreddamento a tenuta o sotto presse di raffreddamento (dross presses), che applicano una forte pressione meccanica sulla scoria calda appena estratta. La pressione compatta la massa, riduce la superficie di contatto con l'ossigeno, espelle il metallo liquido residuo facendolo colare in una vasca sottostante e accelera la dissipazione termica, bloccando l'ossidazione.

## Recupero del metallo e trattamento dei dross

Le scorie bianche trattate vengono avviate a impianti di recupero specializzati:

- **Frantumazione e Vagliatura**: La scoria raffreddata viene frantumata in mulini a barre o frantoi a impatto per separare i pezzi metallici duri dalla frazione polverosa di ossidi.
- **Classificazione Granulometrica**: Tramite vagli vibranti e separatori magnetici/densimetrici, i frammenti di alluminio pulito vengono separati e reimmessi nei cicli di fusione della fonderia, mentre la frazione fine di ossidi (allumina e magnesia) viene avviata ad altri usi industriali (es. produzione di refrattari, cementi o additivi per acciaierie).

## Smaltimento e normativa ambientale

La gestione dei residui e lo smaltimento finale sottostanno a normative ambientali molto rigide (in Europa regolate dal Catalogo Europeo dei Rifiuti - CER):

**Classificazione dei Rifiuti**

- Le scorie bianche prive di trattamenti chimici pericolosi o i residui di ossidi inerti rientrano solitamente in codici CER specifici per i rifiuti della lavorazione dell'alluminio (es. scorie di fusione).
- Le scorie nere (salate) contengono percentuali elevate di cloruri idrosolubili (NaCl, KCl) e fluoruri, e sono classificate come rifiuti speciali pericolosi a causa del potenziale inquinamento delle falde acquifere (rischio di lisciviazione dei cloruri) e del rischio di rilascio di gas tossici (tracce di fosfina o ammoniaca per reazione con l'umidità se sono presenti carburi o nituri metallici).
- **Trattamento delle Scorie Salate (Idrometallurgia)**: Le scorie nere non possono essere conferite tal quali in discarica nei paesi industrializzati. Vengono trattate in impianti di recupero chimico che prevedono la lisciviazione in acqua, la separazione dei sali (recuperati e riutilizzati nei processi elettrolitici o metallurgici) e la purificazione degli ossidi di alluminio residui per il loro riutilizzo sicuro nell'industria ceramica o dell'edilizia.
