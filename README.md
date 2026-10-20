# SkinkOcchiali

Versione attuale: revisione 14. Apri **guida.html** per la vista 3D interattiva, il movimento del vassoio, gli STL e le istruzioni.

**Guida di stampa e montaggio:** https://maxeo.github.io/3dprint-guide/skinkocchiali/guida.html

- `stl/P01`–`P06`: sei pezzi da stampare, una copia ciascuno, millimetri e Z=0.
- `stl/P07_Chiave_meandro.stl`: chiave a S da 2 mm che unisce P06 a P01, **due copie**; sta in tasche aperte sotto P06, invisibili da sopra.
- `stl/P08_Fermo_L.stl`: fermo a L che blocca P02 dal lato Sud, tre perni nelle tre file di fori di P01.
- `dati/guida_spec.json`: sorgente della guida (skill guida-stampa-3d).
- `blender/SkinkOcchiali_v14.blend`: assieme modificabile; fotogrammi 1–60 per il sollevamento di 25 mm.
- `documenti/LEGGIMI_STAMPA_E_MONTAGGIO.txt`, `documenti/mappa_montaggio.svg`: istruzioni offline.
- `prove/`: guida e cursore corti ricavati dalla geometria reale.
- `originale/`: bozza e documenti originali, più assieme v14 di riferimento da NON stampare come pezzo unico.
- `documenti/progetto_sistema_modulare_mobile_v14.md`: specifiche aggiornate.
- `dati/verifica_geometria.json` e `dati/verifica_STL.json`: controlli digitali.

Nord = destra, Sud = sinistra guardando il frontale. Nell'assieme: X cresce verso destra, Y verso il fondo, Z verso l'alto. Le parti sono state riflesse in profondità rispetto alla bozza per correggere l'inversione della vista frontale.

Il nuovo porta patch ha pareti piene e una sola fessura funzionale. Il fondo mobile e l'asticella frontale sono un unico pezzo separato. Il cursore si estrae dall'alto: non ha un blocco in posizione sollevata.

Verifica digitale completata; accoppiamento e scorrimento da tarare con i provini sulla propria stampante. Il progetto conserva la struttura della bozza e non costituisce una riprogettazione completa per stampa senza supporti.

Aggiornamento su richiesta: asta P05 accorciata da 88,7 a 29,57 mm (un terzo). Presa, vassoio e corsa di 25 mm invariati.

Aggiornamento del 14 settembre 2026: lato Sud di P01 aperto, parete posteriore dietro P02/P03, fermi superiori agli angoli della grata, nasello di P06 arrotondato e giunto P01–P06 a chiave a meandro (P07). P02 e P03 sono profondi 77,3 mm, invertiti (P02 a Sud, P03 a Nord) e fissati su tre file di fori; nuovo fermo a L P08; tasca del porta patch a portapenne, alta e lasca.

Aggiornamento del 27 settembre 2026: le fessure a S di P06 sono diventate tasche aperte solo sotto (2,2 mm, piano intero sopra) e la chiave P07 è scesa a 2 mm di spessore; P08 ha il terzo perno a Y = 42,5 mm.


AGGIORNAMENTO 1 OTTOBRE 2026
Altezza totale aumentata da 218,7 a 220,3 mm (+1,6 mm).
Allungati solo i quattro fermi superiori di P01 e i due fermi corrispondenti
nel provino T04_Fetta_Sud_completa.stl, ora alto 220,3 mm.
Quota della grata, base, incastri e altri pezzi invariati. T01, T02 e T03 invariati.
La misura interna del mobile di 219 mm nei documenti precedenti non e stata aggiornata: aumento del modulo confermato dall'utente.


AGGIORNAMENTO 1 OTTOBRE 2026 - PROVINO T04 PIU SOTTILE
T04 ridotto da 16 a 8 mm di larghezza: fetta X = 0-8 mm,
profondita 100 mm (grata compresa), altezza 220,3 mm.
La geometria e tagliata, non scalata. T03 e il modulo finale restano invariati.
Il taglio intercetta il secondo foro di ogni fila (X = 7 mm) e le tasche a
meandro; per provare gli incastri completi usare T03.


Provino T05 aggiunto il 1 ottobre 2026: riquadro 20 x 20 x 3 mm della tasca sotto P06, da provare con la chiave P07 esistente.


2 ottobre 2026: aggiunte in prove tre chiavi a S P07 da 16,1 x 19,1 mm, spesse 1,7 / 1,4 / 1,2 mm (T06, T07, T08).


2 ottobre 2026: aggiunta chiave di prova T09, 16,25 x 19,25 x 1,6 mm.


2 ottobre 2026: aggiunta chiave di prova T10 con profilo piu aderente (+0,10 mm per lato rispetto a T09), spessore 1,6 mm.


2 ottobre 2026: T11 con grata estesa di 11 mm fino a chiudere i quadretti; corpo largo 45 mm, ingombro totale 56 x 100 x 52,5 mm, soffitto a 5 mm dalla grata e piedino da 12 mm.


2 ottobre 2026: aggiunta chiave di prova T11, ulteriore aumento del profilo di 0,10 mm per lato rispetto a T10; 16,65 x 19,65 x 1,6 mm. Taratura sul gioco fisico, con lieve interferenza CAD nominale.


2 ottobre 2026: aggiunto T12, test bridge numerato con campate da 2 a 25 mm, da stampare senza supporti con il profilo della grata.


3 ottobre 2026: aggiunto T12, test bridge numerato con campate da 2 a 15 mm, da stampare senza supporti con il profilo della grata.


3 ottobre 2026: aggiunto T12, test bridge numerato con campate da 2 a 15 mm, da stampare senza supporti con il profilo della grata.


20 ottobre 2026: P01 aggiornato.
- Grata: aggiunte barre a X = 30, 50, 70, 90 e 106,5 mm; tutte le colonne sono ora strette (4,5–8 mm) e in stampa i ponti non superano gli 8 mm.
- Tasca del porta patch: il fondo scende da Z = 5 a Z = 3,2 mm (0,2 mm sopra P06), a Z = 4,2 mm sopra il bordino Nord di P06 (X 105,6–108,4).
- STL P01 rigenerato (volume 180 844 mm³, mesh chiusa); guida.html rigenerata. Provino T11 aggiornato con le stesse modifiche; T03 e T04 (X 0–16 e 0–8 mm) non toccano le zone modificate e restano validi.


20 ottobre 2026 (2): parete esterna Nord di P01 da 0,8 a 2 mm, come la parete interna accanto.
- Fessura della Sezione 1 invariata (2,4 mm); P01 largo 116,2 mm, assieme 151,2 × 126,1 × 220,3 mm.
- Fermi superiori Nord spostati di 1,2 mm (X 106,2–116,2), stessa misura di prima; bordo Nord della grata da 4,2 mm.
- Stessa modifica sul provino T11, ora 57,2 × 100 × 52,5 mm.
