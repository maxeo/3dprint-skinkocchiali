# Progetto — Sistema modulare per mobile

## 1. Obiettivo

Realizzare un sistema modulare stampabile in 3D da inserire all'interno di un mobile.

Il sistema deve integrare:

- un modulo principale strutturale;
- quattro sezioni per scatoline;
- una grata superiore ventilata;
- un porta-patch removibile;
- un modulo portaocchiali removibile;
- un sistema di inserti sulla faccia superiore della base per spostare alcuni moduli;
- una predisposizione per aggiungere moduli successivi verso Sud.

Si utilizza **solo la Variante A**.

---

## 2. Orientamento

Il mobile viene osservato frontalmente.

- **Nord = destra**
- **Sud = sinistra**
- **Davanti = verso chi guarda il mobile**
- **Dietro = fondo del mobile**
- **Alto = soffitto del mobile**
- **Basso = piano inferiore del mobile**

Gli elementi principali partono da Nord e si sviluppano verso Sud.

---

## 3. Dimensioni interne del mobile

| Dimensione | Misura |
|---|---:|
| Larghezza interna | 310 mm |
| Altezza interna | 219 mm |
| Profondità interna | 130 mm |

La profondità complessiva del sistema può arrivare fino a **130 mm**.

---

# 4. Modulo principale

## 4.1 Dimensioni generali

| Elemento | Misura |
|---|---:|
| Larghezza modulo principale | 115 mm |
| Profondità corpo principale | 80 mm |
| Altezza disponibile | 219 mm |
| Base inferiore | 6 mm nominali |
| Pareti strutturali | 2,4 mm nominali |

La base da 6 mm viene mantenuta.

Le sezioni verticali arrivano direttamente sulla base: non deve esserci uno spazio vuoto tra sezioni e base.

---

# 5. Distribuzione laterale

La configurazione logica da **Nord verso Sud** è:

1. **Sezione 1 — 4 × 80 mm — fissa**
2. **Sezione 3 — 30 × 80 mm — fissa**
3. **Sezione 2 — 4 × 60 mm — mobile**
4. **Sezione 4 — 50 × 80 mm — mobile**
5. **Zona strutturale Sud — 27 mm — fissa**

Controllo totale:

**4 + 30 + 4 + 50 + 27 = 115 mm**

La posizione relativa delle due sezioni mobili non è però obbligatoriamente quella sopra indicata: **Sezione 2 e Sezione 4 possono essere spostate tramite gli inserti nella base**.

---

# 6. Sezioni per scatoline

## 6.1 Sezione 1

- larghezza: **4 mm**
- profondità: **80 mm**
- posizione: lato Nord
- **fissa**

## 6.2 Sezione 2

- larghezza: **4 mm**
- profondità: **60 mm**
- **removibile**
- collegata alla base tramite inserti
- deve poter essere spostata e reinstallata senza utensili

Questa sezione può essere collocata, a seconda della configurazione desiderata:

- dopo la sezione fissa da 30 mm;
- dopo la sezione mobile da 50 mm;
- oppure ulteriormente verso Sud sfruttando anche gli inserti presenti nella zona strutturale da 27 mm.

## 6.3 Sezione 3

- larghezza: **30 mm**
- profondità: **80 mm**
- **fissa**
- fondo posteriore aperto
- è il pezzo rappresentato in blu negli schemi

Questa sezione **non è removibile e non cambia posizione**.

## 6.4 Sezione 4

- larghezza: **50 mm**
- profondità: **80 mm**
- **removibile**
- fondo posteriore consentito
- collegata alla base tramite inserti

Può essere spostata e reinstallata senza utensili.

---

# 7. Zona strutturale Sud da 27 mm

La zona da **27 mm** sul lato Sud rimane parte della struttura permanente del modulo principale.

Deve:

- contribuire alla rigidità generale;
- sostenere la grata superiore;
- mantenere la predisposizione per l'espansione verso Sud;
- avere sulla **faccia superiore della base** lo stesso sistema di inserti usato per i moduli mobili.

Quindi la zona da 27 mm è strutturale, ma **la sua superficie superiore rimane utilizzabile per il posizionamento dei moduli removibili**.

---

# 8. Fascia di inserti superiori nella base

Gli inserti superiori devono coprire:

- i **27 mm** della zona strutturale Sud;
- i **54 mm** normalmente occupati da Sezione 2 e Sezione 4.

Totale fascia utile:

**27 + 4 + 50 = 81 mm**

I due moduli mobili occupano insieme:

**4 + 50 = 54 mm**

Rimane quindi:

**81 - 54 = 27 mm**

di libertà complessiva per traslare e riposizionare i due moduli.

Gli inserti devono essere ricavati nella faccia superiore della base senza indebolire eccessivamente la struttura.

La geometria definitiva dell'inserto verrà ottimizzata in CAD per stampa FDM.

---

# 9. Modularità interna

Solo questi due elementi sono mobili:

- **Sezione 2 — 4 × 60 mm**
- **Sezione 4 — 50 × 80 mm**

Devono poter:

- essere rimossi singolarmente;
- essere invertiti;
- essere traslati verso Sud;
- sfruttare anche la superficie superiore della zona strutturale da 27 mm;
- essere reinstallati manualmente.

Restano invece fissi:

- Sezione 1 da 4 × 80 mm;
- Sezione 3 da 30 × 80 mm;
- telaio strutturale Sud;
- grata;
- parete Nord;
- struttura posteriore.

---

# 10. Soffitto delle sezioni

Le sezioni per scatoline devono avere un proprio soffitto.

Tra il soffitto delle sezioni e la faccia inferiore della grata superiore devono rimanere:

**10 mm di spazio libero**

per l'aerazione.

---

# 11. Grata superiore

## 11.1 Dimensioni

| Elemento | Misura |
|---|---:|
| Larghezza | 115 mm |
| Profondità | 100 mm |
| Spessore nominale | 3 mm |
| Distanza della superficie superiore dal soffitto | 22,7 mm |

Dato che il mobile è alto 219 mm:

**219 - 22,7 = 196,3 mm**

La superficie superiore della grata si trova quindi a:

**196,3 mm dal fondo del mobile**

Con spessore nominale della grata di 3 mm:

- faccia inferiore grata: **193,3 mm**
- soffitto delle sezioni: **183,3 mm**
- altezza utile delle sezioni sopra la base da 6 mm:

**183,3 - 6 = 177,3 mm**

---

# 12. Aerazione

La grata deve essere ampiamente traforata.

La struttura deve garantire il passaggio d'aria attraverso:

- grata superiore;
- camera d'aria da 10 mm;
- lato Sud ventilato;
- eventuali aperture posteriori.

La parte frontale sotto la grata deve rimanere **completamente aperta**.

---

# 13. Supporto strutturale della grata

La grata deve essere indipendente dai moduli removibili.

Deve essere sostenuta da elementi permanenti:

- parete Nord;
- struttura posteriore;
- telaio strutturale Sud;
- eventuali nervature.

Il lato Sud può avere una parete o telaio, purché sia:

- traforato;
- a griglia;
- o comunque sufficientemente ventilato.

Il carico previsto sopra la grata è di circa **2 g**, ma la struttura deve essere stabile anche durante inserimento, rimozione e manipolazione del modulo.

---

# 14. Bloccaggio nel mobile

Il modulo principale deve avere elementi superiori che lo stabilizzino tra:

- piano inferiore del mobile;
- soffitto del mobile.

Gli elementi di bloccaggio devono:

- impedire oscillazioni;
- evitare il ribaltamento in avanti;
- non richiedere viti;
- permettere la rimozione del modulo.

Lo spazio nominale tra grata e soffitto è:

**22,7 mm**

La geometria definitiva dei fermi superiori verrà ottimizzata nel CAD con un piccolo gioco di montaggio.

---

# 15. Porta-patch

## 15.1 Foglietti di riferimento

Dimensioni tipiche:

- larghezza: **66 mm**
- altezza: **108 mm**

Spazio interno consigliato:

- larghezza utile: circa **67 mm**
- altezza utile: circa **109 mm**
- spessore utile: circa **2 mm**

---

## 15.2 Posizione

Il porta-patch è collocato sul davanti del modulo principale.

Non deve interferire con la sezione sottile fissa più a Nord.

È accettabile che per accedere alle scatoline retrostanti sia necessario rimuovere il porta-patch.

---

## 15.3 Forma

Il porta-patch deve essere:

- removibile;
- traforato;
- leggero;
- visivamente aperto;
- con frontale più basso dei foglietti.

I patch devono sporgere leggermente sopra il frontale per essere facilmente afferrabili.

---

# 16. Fissaggio del porta-patch

Non si utilizza una rotaia integrale.

La soluzione scelta è:

- **tasca inferiore leggermente lasca**;
- piccolo piede inferiore sul porta-patch;
- lieve contenimento superiore contro il ribaltamento;
- linguetta superiore di presa.

## Montaggio

1. inserire il piede del porta-patch nella tasca inferiore;
2. accompagnare il pezzo nella posizione corretta;
3. il contenimento superiore evita che cada in avanti.

## Rimozione

1. afferrare la linguetta superiore;
2. sollevare il porta-patch;
3. estrarre il piede dalla tasca;
4. rimuovere il pezzo.

Non devono essere presenti clip elastiche che richiedano piegature ripetute.

---

# 17. Modulo portaocchiali

Il modulo portaocchiali è un pezzo removibile montato davanti al modulo principale.

## 17.1 Dimensioni degli occhiali

| Dimensione | Misura |
|---|---:|
| Larghezza | 142 mm |
| Profondità | 46,1 mm |

Il portaocchiali può quindi essere più largo dei 115 mm del modulo principale.

---

## 17.2 Profondità complessiva

Profondità corpo principale:

**80 mm**

Profondità minima portaocchiali:

**46,1 mm**

Totale:

**80 + 46,1 = 126,1 mm**

Profondità interna mobile:

**130 mm**

Margine residuo:

**130 - 126,1 = 3,9 mm**

Il progetto deve restare entro il limite totale di 130 mm.

---

# 18. Bordo anticaduta del portaocchiali

Il portaocchiali deve avere un bordino di circa:

**1 mm**

presente lungo:

- fronte;
- lato Nord;
- lato Sud.

Il bordo deve limitare lo scivolamento senza ostacolare il prelievo degli occhiali.

---

# 19. Fermo per il naso

Il portaocchiali deve integrare un fermo approssimativamente triangolare.

## Altezza

**20,7 mm**

## Posizione laterale

Gli occhiali sono larghi 142 mm.

Centro:

**142 / 2 = 71 mm**

Il fermo deve quindi essere centrato lateralmente a circa:

**71 mm dal bordo del portaocchiali**

## Posizione in profondità

Il fermo **non deve stare a metà della profondità**.

Deve essere collocato:

**tutto davanti, verso chi guarda il mobile**

quasi in corrispondenza del bordo anteriore del portaocchiali.

Gli spigoli devono essere arrotondati.

---

# 20. Aggancio del portaocchiali

Il modulo principale deve contenere solo gli elementi:

**femmina / concavi**

Il portaocchiali deve avere gli elementi:

**maschio / sporgenti**

integrati direttamente nel pezzo.

Non devono essere necessari connettori separati.

Il sistema di aggancio deve essere ricavato nella base del modulo principale.

---

# 21. Predisposizione per moduli futuri verso Sud

Il modulo principale deve permettere l'aggiunta futura di ulteriori moduli verso Sud.

Questa funzione è indipendente dagli inserti superiori usati per Sezione 2 e Sezione 4.

Il principio è:

- modulo principale: **cavità femmina**
- modulo aggiuntivo: **maschi integrati nel pezzo**

I giunti devono trovarsi nel **bordo Sud della base**, sullo stesso piano del modulo principale.

Non devono essere rappresentati come moduli montati sotto il corpo principale.

---

# 22. Separazione dei sistemi di aggancio

Il progetto utilizza quindi due sistemi distinti.

## Inserti superiori

Servono per:

- Sezione 2 da 4 × 60 mm;
- Sezione 4 da 50 × 80 mm;
- eventuali futuri accessori montati sopra la base.

Coprono una fascia di **81 mm**, inclusi i 27 mm strutturali Sud.

## Giunti verso Sud

Servono per:

- aggiungere nuovi moduli lateralmente verso Sud;
- estendere il sistema lungo la larghezza del mobile.

Questi giunti si trovano sul bordo Sud della base.

I due sistemi non devono interferire tra loro.

---

# 23. Principi di progettazione FDM

Il modello dovrà essere ottimizzato per stampa FDM.

Principi:

- evitare supporti dove possibile;
- pareti sufficientemente robuste;
- raccordare gli spigoli soggetti a carico;
- non usare clip fragili se non necessarie;
- mantenere tolleranze adatte a parti removibili;
- permettere la ristampa indipendente dei moduli;
- ridurre l'attrito negli incastri;
- mantenere gli inserti accessibili e pulibili.

Tolleranza iniziale indicativa per parti removibili:

**circa 0,30 mm per lato**

da verificare prima della modellazione definitiva.

---

# 24. Componenti da modellare

Il progetto finale dovrà generare almeno i seguenti componenti separati:

1. **Modulo principale**
   - base da 115 mm;
   - Sezione 1 fissa;
   - Sezione 3 fissa;
   - struttura Nord;
   - struttura Sud;
   - supporto della grata;
   - grata superiore;
   - inserti superiori;
   - sedi femmina portaocchiali;
   - sedi femmina per espansione Sud.

2. **Sezione 2 removibile**
   - 4 × 60 mm;
   - maschi compatibili con gli inserti della base.

3. **Sezione 4 removibile**
   - 50 × 80 mm;
   - maschi compatibili con gli inserti della base.

4. **Porta-patch removibile**
   - struttura traforata;
   - frontale più basso;
   - piede inferiore;
   - linguetta superiore.

5. **Modulo portaocchiali**
   - larghezza adatta a 142 mm;
   - profondità minima 46,1 mm;
   - bordo da 1 mm;
   - fermo naso da 20,7 mm;
   - maschi di aggancio integrati.

6. **Eventuale provino per inserti**
   - utile per verificare la tolleranza prima di stampare l'intero sistema.

---

# 25. Stato attuale del progetto

Sono considerate definite le seguenti scelte:

- modulo principale da **115 mm**;
- solo **Variante A**;
- Sezione 1 da **4 × 80** fissa;
- Sezione 3 da **30 × 80** fissa;
- Sezione 2 da **4 × 60** mobile;
- Sezione 4 da **50 × 80** mobile;
- inserti superiori estesi anche nella zona strutturale da **27 mm**;
- fascia utile degli inserti pari a **81 mm**;
- grata da **115 × 100 mm**;
- camera d'aria da **10 mm**;
- porta-patch traforato con tasca inferiore lasca;
- porta-patch più basso dei foglietti;
- portaocchiali da almeno **142 × 46,1 mm**;
- fermo naso alto **20,7 mm** e posizionato sul davanti;
- giunti futuri verso Sud sul bordo della base;
- maschi integrati nei moduli aggiuntivi;
- cavità femmina sul modulo principale.

Le geometrie definitive di inserti, incastri, nervature e fermi superiori saranno dimensionate nella fase CAD/STL.
