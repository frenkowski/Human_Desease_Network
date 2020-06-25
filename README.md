# Human Desease Network

## Team
Andrea Ruggieri (_a.ruggieri4@campus.unimib.it_)  
Francesco Stranieri (_frenkowski+github@gmail.com_)

## Sommario
Gli algoritmi di Community Detection su una rete biologica svolgono un ruolo essenziale, in quanto permettono di comprenderne la struttura e le funzioni, oltre ad essere utili per predirne alcuni comportamenti e per poterla analizzare. Con questo studio si analizzerà una nota rete biologica, la *"Human Disease Network"*, al fine di coglierne le proprietà più importanti, attraverso un’attività di Network Analysis, e di valutare le connessione tra i diversi nodi, attraverso tecniche di Community Detection.

## Introduzione
La rete Human Disease Network (HDN) è stata proposta nel 2007 da *Goh*, usando le informazioni disponibili sul database OMIM. La rete in questione rappresenta diverse malattie umane, con riferimento alle loro origini genetiche. In particolare, si è deciso di analizzarla poiché risulta essere di rilievo all’interno della comunità scientifica. Tale rete ha difatti permesso di approfondire e di rappresentare in maniera chiara ed efficiente tutte quelle connessioni presenti tra le malattie e i disordini genetici.
All’interno di questo progetto si cercherà di rispondere ad alcune domande relative alla HDN (Sezione 2). Si descriveranno quindi le proprietà più importanti di questa rete, attraverso l’attività di Network Analysis (Sezione 3). Successivamente si condurrà una trasformazione della rete, in modo da renderla più compatta e facile da studiare, rimuovendo tutte le informazioni ritenute ridondanti (Sezione 4). Questo porterà ad avviare una nuova attività di Network Analysis (Sezione 5), sulla rete trasformata. Si procederà quindi con un’attività di Community Detection (Sezione 6) che, assieme ad ulteriori analisi (Sezione 7), permetterà di trarre importanti conclusioni (Sezione 8).

## Obiettivi
In questo progetto, si è deciso di analizzare nel dettaglio la rete Human Disease Network, concen- trandosi maggiormente sui seguenti punti:
• Quali geni causano la maggior parte delle malattie? E quali tra queste sono associate al gene "più rilevante"?
• Come cambia la rete dopo averla trasformata? E cosa comporta questa trasformazione?
• Le malattie tendono ad "essere legate" tra di loro?
• Esistono malattie "più rilevanti" di altre?
• Quale algoritmo di Community Detection partiziona meglio la rete? Considerare questa come pesata ha effetto sulle partizioni?
• Esistono gruppi di malattie "ben distinte" tra di loro?
• E’ possibile assegnare una categoria alle malattie classificate come *’Unclassified’*?
