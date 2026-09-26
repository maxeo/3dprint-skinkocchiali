# SkinkOcchiali

Versione attuale: revisione 14. Apri **guida.html** per la vista 3D interattiva, il movimento del vassoio, gli STL e le istruzioni.

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
