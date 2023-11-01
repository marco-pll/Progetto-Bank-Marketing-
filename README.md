# Progetto-Bank-Marketing-
Progetto di gruppo realizzato per il corso "Metodi Statistici per l'Analisi di Dati Aziendali".  
La repository contiene il codice utilizzato durante lo sviluppo del progetto e i dati utilizzati. Attraverso il progetto ci siamo posti 3 obiettivi: 1) quello di utilizzare le caratteristiche del cliente per prevedere il suo interesse per il prodotto offerto, 2) quello di prevedere un suo eventuale stato di default, e 3) quello di costruire dei cluster di clienti (sulla base delle caratteristiche disponibili) con cui informare future campagne di marketing.

## Dati
I dati sono stati ottenuti a [questo link](https://www.openml.org/search?type=data&sort=runs&status=active&id=1461). Sono 2 dataset, entrambi riferiti a delle campagne di telemarketing portate avanti negli anni da un istituzione bancaria Portoghese.  
- Le signole osservazioni rappresentano chiamate ai clienti. La variabile di interesse è binaria, l'accettazione o meno dell'offerta proposta.  
- L'insieme di feature a disposizione per effettuare la classificazione è disponibile al link.

## Codice
Il codice relativo al file "Previsione dell'interesse" fa riferimento all'analisi svolta al fine del primo obiettivo: cercare un modello che preveda l'interesse del cliente per il prodotto offerto. La metrica utilizzata per il confronto tra i modelli è il punteggio F1. Il codice è scritto in markdown, ma solo per poterlo organizzare i segmenti. Non è pensato per essere knittato in un pdf.
