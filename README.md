# Progetto-Bank-Marketing-
Progetto di gruppo realizzato per il corso "Metodi Statistici per l'Analisi di Dati Aziendali".  
La repository contiene il codice utilizzato durante lo sviluppo del progetto e i dati utilizzati. Attraverso il progetto ci siamo posti 3 obiettivi: 1) quello di utilizzare le caratteristiche del cliente per prevedere il suo interesse per il prodotto offerto, 2) quello di prevedere un suo eventuale stato di default, e 3) quello di costruire dei cluster di clienti (sulla base delle caratteristiche disponibili) con cui informare future campagne di marketing.

## Dati
I dati sono stati ottenuti a [questo link](https://www.openml.org/search?type=data&sort=runs&status=active&id=1461). Sono 2 dataset, entrambi riferiti a delle campagne di telemarketing portate avanti negli anni da un istituzione bancaria Portoghese.  
- Le signole osservazioni rappresentano chiamate ai clienti. La variabile di interesse è binaria, l'accettazione o meno dell'offerta proposta.  
- L'insieme di feature a disposizione per effettuare la classificazione è disponibile al link.

I dati sono composti da due dataset, bank_full.csv e bank_additional_full.csv, il primo utilizzato per l'analisi dell'interesse e il clustering, i secondo utilizzato per l'analisi dei clienti in default.

## Codice
Il codice relativo al file "Previsione dell'interesse" fa riferimento all'analisi svolta al fine del primo obiettivo: cercare un modello che preveda l'interesse del cliente per il prodotto offerto. La metrica utilizzata per il confronto tra i modelli è il punteggio F1. 

Il file "Analisi_del_Default_Balanced_Dataset" fa riferimento all'analisi dello stato di default del cliente. La scelta del modello si basa sulla metrica F1.

Il file "Segmentazion" contiene l'analisi relativa al clustering dei clienti. Sono stati provati diversi metodi, scegliendo quello che dava risultati più interpretabili.

Il codice è scritto in markdown, ma solo per poterlo organizzare i segmenti. Non è pensato per essere knittato in un pdf.
