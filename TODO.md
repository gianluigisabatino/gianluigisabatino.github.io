
# TODO

> **Goal**: trasformare questa obsoleta versione del CV di Gianluigi in un CV moderno e accattivante, che massimizza la probabilità di venire assunto dalle aziende. Puntiamo ad entrare in aziende inerenti all'ambito di studi di Gianluigi, tipo Pfizer, Boheringher, Takeda, per fare il tecnico di laboratorio di biologia. In tutto questo Gianluigi prova anche a chiedere per posizioni di analisi chimiche. Ha preparato anche la lettera di raccomandazione che evidenzia le sue ultime esperienze in un laboratorio per produrre e caratterizzare materie plastiche.

---

- [x] Convertire il [original_cv.doc] in LaTeX
- [x] Cambiare template (reference in 'TEMPLATES/')
- [x] Mettere R anziché RStudio magari  
- [x] Estrai le pagine della recommendation letter. Vogliamo una versione con e una senza recommendation letter


- [x] **Tedesco.** Nel CV è “professional working proficiency”. Nella lettera di accompagnamento Gianluigi scrive che lo sta ancora imparando, insieme al greco. È stata tenuta la formulazione del CV. Se il livello reale è più basso, va abbassato prima di un colloquio in tedesco: a Vienna (Boehringer Ingelheim, Takeda) lo controllano. #todo fix: B1 può essere considerato professional
- [x] **Lettera di pagina 5.** È nel PDF con le referenze perché è nel `.doc`. È la più debole: niente nome del firmatario, chiusura incompleta, e copre solo il 2021–2022. Le lettere di Ret e Vizzardelli sono più utili. Si può togliere quella pagina senza rifare il CV. #todo fix: Ah Dr. Tech. Davide Ret (Senior Scientist)
- [x] **Niente GMP, LIMS o SOP.** Non compaiono nel documento. Non sono stati aggiunti, anche se molti annunci pharma li chiedono. #todo aggiungi una breve riga dove citi che Gianluigi è famigliare con _GMP_ specificatamente
- [x] **Foto.** È il JPEG incorporato nel Word, 258×272 px. In testata si vede, in stampa è morbida. Se esiste uno scatto più grande, va sostituito `cv/photo.jpg`. #todo sostituire foro con `cv/photo_2.jpg`
- [x] **Fatti solo nelle lettere, non nel CV.** Non sono stati importati nel testo del CV, per non aggiungere esperienze che il `.doc` non elencava tra le bullet: Long Night of Research, preparazione di esercitazioni, modelli di topo umanizzati descritti da Vizzardelli oltre quanto già scritto, sintesi di superadsorber (nella lettera del 2022; nel CV c’è la caratterizzazione GPC di biomateriali e, nel ruolo 2024–2026, gli idrogel acrilati). Se Gianluigi vuole questi punti nel CV, vanno aggiunti esplicitamente. #todo aggiungi direttamente nel CV
- [x] **“Over two years of HPLC”** sta nella lettera di accompagnamento, non è stato messo come claim nel CV. I periodi con HPLC sono ottobre 2021–maggio 2022 e settembre 2024–gennaio 2026. La somma è circa due anni, ma non continuativi. #todo aggiungi direttamente nel CV
- [x] **Copertina personale.** La pagina 2 ha refusi (mantained, coltures, “Your sincerely”) e dice che il tedesco e il greco sono in corso. Non è stata riscritta. Per una candidatura serve una cover letter nuova, diversa da questa e diversa dalle referenze. #todo ricordiamoci di sestemare questo punto

---

## Osservazioni

- **Lettera di Ret e analisi chimica.** È la referenza che sostiene anche le posizioni di analisi chimica e di caratterizzazione di materiali plastici: HPLC in HILIC e fase inversa, GPC, NMR, MALDI-TOF, integrazione dei picchi, polimeri acrilati. Nel CV questo filone c’è (idrogel acrilati, NMR, indice di rifrazione, GPC, metodo HPLC per l’acido sialico), ma il sottotitolo è “Laboratory Technician | Biologist”. Se le candidature chimiche sono allo stesso livello di quelle di biologia, il sottotitolo e le prime righe del profilo vanno riequilibrati. Non è stato inventato un secondo profilo.
- ==**Buco maggio 2022–maggio 2024.** Nessuna esperienza in mezzo. Non è stato riempito.
- ==🟢**Voti.** MSc Functional Genomics 104/110 (2017–2019), BSc Biological Sciences and Technologies 110/110 (2013–2016), diploma in Chemical Engineering 91/100 (2008–2013, istituto tecnico G. D’Annunzio – M. Fabiani). Nessun titolo di tesi era nel `.doc`.

## Osservazioni nuove

- **B1 e “professional working”.** Nel CV e nella cover letter il tedesco è scritto `B1 (professional working proficiency)`, come chiesto. Per chi usa il CEFR, B1 è un livello intermedio (utente indipendente), non il “professional working” delle scale LinkedIn/ILR, che di solito corrisponde a un B2 alto o a un C1. A un colloquio in tedesco a Vienna la differenza si nota. Nessun altro livello è stato inventato.
- **Firma della lettera 2021–2022.** Il nome di Dr. techn. Davide Ret non è stampato su quella pagina: ci sono una firma e il timbro TU Wien. L’attribuzione viene da Gianluigi. La scansione non è stata modificata e resta nel PDF con le referenze.
- **GMP.** La riga è solo “Familiar with GMP”, nelle skill. Non era nel `.doc` né nelle lettere. Non sono stati aggiunti LIMS o SOP. In colloquio possono chiedere un esempio concreto (quale laboratorio, quale attività).
- **Fatti aggiunti dalle lettere.** Long Night of Research e materiali per le esercitazioni (Ret, 2024–2026); polimerizzazione radicalica termica e fotoiniziata, aggiunta alla bullet degli idrogel già presente; topo umanizzato, isolamento da midollo e milza, saggi colorimetrici (Vizzardelli); sintesi di polimeri superassorbenti (lettera 2022, dove è scritto “superadsorber”). Nel CV è usato il termine inglese “superabsorbent polymers”.
- **HPLC.** “Over two years” è nel profilo, con le due finestre di date scritte accanto, così non sembra un unico periodo continuo.
- **Cover letter.** `cv/cover_letter.tex` e `output/Gianluigi_Sabatino_Cover_Letter.pdf`. Data: 16 November 2026. Corretti i refusi della pagina 2. Il tedesco non è più “I’m learning German”. Resta, solo nella lettera, la frase dell’originale “identified bacteria by PCR”: non compare nelle referenze né nelle bullet del CV. Se non va tenuta, si toglie da lì.
- **Sottotitolo.** È ancora “Laboratory Technician | Biologist”. L’osservazione sul riequilibrio verso l’analisi chimica non aveva un fix. Il profilo ora cita anche la caratterizzazione dei polimeri, e la cover letter dice esplicitamente biology or chemical analysis.
- **Buco 2022–2024 e voti.** Invariati. Il buco non è stato riempito. I voti restano quelli del `.doc`, senza titoli di tesi.
- **Foto.** In testata c’è `cv/photo_2.jpg`. `cv/photo.jpg` è il vecchio JPEG del Word e non è più incluso.
