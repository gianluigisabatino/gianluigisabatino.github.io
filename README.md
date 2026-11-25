# CV di Gianluigi Sabatino

CV in inglese per posizioni da **tecnico di laboratorio di biologia** (Pfizer, Boehringer Ingelheim, Takeda e ruoli analoghi) e, in parallelo, per **analisi chimiche**. I fatti vengono da `original_cv.doc`. Il layout è nuovo.

## Cosa è stato fatto

`original_cv.doc` è un Word di 5 pagine. È stato ricostruito in LaTeX, con un PDF solo CV e uno con le lettere di referenza allegate. `original_cv.doc` non è stato modificato.

| File | Contenuto |
| --- | --- |
| `cv/gianluigi_sabatino.tex` | Sorgente del CV |
| `cv/cover_letter.tex` | Cover letter riscritta, al posto della pagina 2 del `.doc` |
| `cv/photo_2.jpg` | Foto in testata (1156×1280). `cv/photo.jpg` è il ritaglio vecchio, non usato |
| `output/Gianluigi_Sabatino_CV.pdf` | CV, 1 pagina |
| `output/Gianluigi_Sabatino_Cover_Letter.pdf` | Cover letter, 1 pagina |
| `output/Gianluigi_Sabatino_CV_with_recommendations.pdf` | CV + 3 lettere |
| `letters/recommendation_tuwien_ias_ret.pdf` | Pagina 3 dell’originale |
| `letters/recommendation_meduni_vizzardelli.pdf` | Pagina 4 dell’originale |
| `letters/recommendation_tuwien_ias_2022.pdf` | Pagina 5 dell’originale |
| `templates/Omar_Cusma_Fait_CV.pdf` | Riferimento visivo, non il CV di Gianluigi |

Compilazione (TinyTeX, già presente sulla macchina):

```powershell
cd cv
pdflatex -interaction=nonstopmode gianluigi_sabatino.tex
pdflatex -interaction=nonstopmode gianluigi_sabatino.tex
```

Le lettere non sono riscritte. Sono le pagine originali, unite al PDF compilato, così restano firme, timbri e carte intestate.

## Pagine del documento originale

1. **CV**, con foto. Layout Word a due colonne.
2. **Lettera di accompagnamento** originale, scritta da Gianluigi. Non è una referenza e non è nei PDF. La versione corretta è `output/Gianluigi_Sabatino_Cover_Letter.pdf`.
3. **Technische Universität Wien — Institute of Applied Synthetic Chemistry.** Dr. techn. Davide Ret (Senior Scientist, Polymer Chemistry and Technology), Vienna, marzo 2026. Getreidemarkt 9/163 FBMC, 1060 Wien. Firmata e timbrata. Riguarda il ruolo di laboratory technician, settembre 2024–gennaio 2026, compreso il lavoro su polimeri acrilati (polimerizzazione termica e fotoiniziata, HPLC, GPC, NMR).
4. **Center for Pathophysiology, Infectiology and Immunology — Medical University of Vienna**, Institute of Pathophysiology and Allergy Research. Caterina Vizzardelli, PhD (FWF Project Leader), 13 febbraio 2026. Waehringer Guertel 18-20, 1090 Vienna. Firmata. Periodo metà maggio–fine agosto 2024.
5. **Technische Universität Wien — Institute of Applied Synthetic Chemistry, Research Unit Macromolecular Chemistry.** Lettera distinta dalla pagina 3, sul periodo ottobre 2021–maggio 2022 (gruppo Polymer Chemistry and Technology, in collaborazione con Gastrointestinal Immunology, MedUni Wien). Getreidemarkt 9/E 163, 1060 Vienna. In calce ci sono firma e timbro, senza nome stampato. Gianluigi la attribuisce a Dr. techn. Davide Ret (Senior Scientist). Il PDF della lettera non è stato alterato.

## Scelte di contenuto

- Lingua: inglese, come l’originale. 
- **R** al posto di RStudio.
- Correzioni solo di forma: Bachelor’s; University of Trieste; RT-PCR; Illumina MiSeq; MestReNova (nel `.doc` è scritto “MesterNova”); mMass; “Participated”; l’inglese delle bullet. Il titolo del poster usa “cells cultured”, come nella lettera di Ret. Nel `.doc` c’era “cell cultured”.
- Profilo riscritto sui fatti già presenti (HPLC, MALDI-TOF, NMR, biologia molecolare, colture, istologia, calibrazione, manutenzione, sterilizzazione). L’elenco generico “My strengths” non è stato copiato.
- Le skill sono in righe leggibili: analytical, molecular biology, cell culture, in vivo, histology, data, e una riga GMP (“Familiar with GMP”). HILIC, reverse phase e GPC sono in evidenza perché compaiono nell’esperienza, non solo nella lista skill del Word.
- Tedesco nel CV: B1 (professional working proficiency). Greco: basic.
- Nel profilo: oltre due anni di HPLC, sui periodi ottobre 2021–maggio 2022 e settembre 2024–gennaio 2026.
- Dalle lettere, ora anche nel CV: Long Night of Research e materiali per le esercitazioni; polimerizzazione radicalica termica e fotoiniziata; modelli di topo umanizzati, midollo e milza, saggi colorimetrici; sintesi di polimeri superassorbenti.
- Gli immunoassay (Evans blue, Ficoll, citofluorimetria) restano nelle bullet di MedUni Wien. Non sono diventati una categoria skill nuova.
- Indirizzo Elisenstraße 1, 1230 Wien: nel CV breve c’era solo “Vienna”; l’indirizzo completo è sulla lettera di accompagnamento dello stesso file. È in testata.
- Data di nascita, nazionalità, patente B, chitarra e cucina sono in fondo, non in apertura.
- Layout a **colonna singola**, con testata, contatti, foto e date a destra. Il riferimento visivo è `templates/Omar_Cusma_Fait_CV.pdf` (LaTeX, tipografia pulita, contatti in riga). La sidebar a due colonne di quel template non è stata copiata: Workday e Taleo, usati da queste aziende, leggono male le due colonne.
- Obiettivo di lunghezza: 1 pagina. Ci sta, senza seconda pagina quasi vuota.
