# University-Database
Creazione di un database per la gestione di un'Università
## Caso di studio
Una Università di medie dimensioni offre svariati curriculum di laurea, di master e di dottorato. La struttura educativa dell’Università è composta di Dipartimenti. I Dipartimenti amministrano i curricula, il curriculum può contenere corsi di altri dipartimenti.. Infatti, l’Università vanta un’ampia libertà di scelta dei corsi da parte degli studenti per comporre i loro piani di studio.
La flessibilità nella selezione dei corsi richiede uno sforzo da parte del sistema di gestione delle immatricolazioni. Piani di studio liberi e individuali non devono contraddire le regole che governano il curriculum, in termini di numero di CFU coperti per le diverse discipline (di base, caratterizzante, affine, notando che un corso catalogato caratterizzante per un curriculum può essere catalogato come affine per un altro), corsi obbligatori e prerequisiti.
La flessibilità della didattica è stata la principale causa del costante incremento del numero di studenti. Comunque, per mantenere la sua tradizionale efficienza, il sistema di immatricolazione, ancora parzialmente manuale, deve essere sostituito con una nuova soluzione software. La ricerca preliminare di una package già disponibile sul mercato non ha avuto successo. Il sistema di immatricolazioni universitarie è talmente particolare da richiedere uno sviluppo specifico.
Il sistema deve essere di supporto alle attività di pre-immatricolazione e alle procedure di gestione delle immatricolazioni. Le attività di pre-immatricolazione devono comprendere l’invio agli studenti dei risultati degli esami dell’ultimo semestre insieme alle istruzioni per l’immatricolazione. Durante il periodo di immatricolazione il sistema deve verificare il piano proposto dagli studenti a fronte di prerequisiti. Infine il sistema deve fornire alcune semplici statistiche circa la percentuale di superamento degli esami del semestre precedente e per l’intero anno, nonché il numero totale di iscritti ad ogni curriculum per i diversi anni.
## Implementazione 
L'unico file presente nella directory comprende il caso di studio definitivo, il quale consta delle seguenti sezioni:
- Analisi dei requisiti
- Progettazione concettuale
- Progettazione logica
- Codifica SQL e test (in cui vi sono tutte le operazioni per la creazione, la gestione e l'interrogazione del DB)
