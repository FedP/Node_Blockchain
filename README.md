# Node_Blockchain

Un nodo completo è un computer nella rete peer-to-peer di Bitcoin che ospita e sincronizza una copia dell'intera blockchain Bitcoin. I nodi sono essenziali per mantenere in funzione una rete di criptovaluta.

 - Nodo completo (Full node)

Secondo la documentazione Bitcoin Core, "un nodo completo è un programma che convalida completamente le transazioni e i blocchi. Quasi tutti i nodi completi, inoltre, supportano la rete accettando transazioni e blocchi da altri nodi completi, convalidando tali transazioni e blocchi e poi ritrasmettendoli ad altri nodi completi." 
Un full node contiene tutta la Blockchain (Bitcoin: 188 GB al 28/10/2018)

1) Verify the blocks
2) Store the blockchain

 - Nodo leggero (Light Node)

Esistono anche "nodi leggeri" che dipendono dai nodi completi per il funzionamento. Questi richiedono una capacità di download e di memorizzazione notevolmente inferiore rispetto ai nodi completi, poiché scaricano solo blockheader dalla blockchain Bitcoin e quindi non memorizzano l'intera blockchain. Il loro unico compito è quello di verificare le transazioni nella blockchain utilizzando la verifica semplificata dei pagamenti (Simplified Payment Verification - SPV).

1) Can be used for wallet purpose

- Consenso 

Il consenso in una rete decentrata è definito dalle regole in base alle quali la rete opera e conferma la validità delle informazioni contenute nei blocchi. Il mantenimento del consenso tra i nodi, la verifica delle transazioni e il voto sulle proposte sono tra i compiti principali dei nodi completi. 

- Nodo potato (pruned)

Un tipo di nodo completo è il nodo completo potato, che scarica i blocchi dall'inizio della catena fino a raggiungere un certo limite e poi elimina i blocchi più vecchi. Si definisce "potato" perché il sottoalbero dell'albero decisionale è stato rimosso, quindi il nodo potato occupa meno spazio sul disco rigido.

I nodi archivio completi, invece, ospitano l'intera blockchain, occupando molto più spazio sul disco rigido rispetto al nodo completo potato. I nodi archivio sono classificati in ulteriori sottocategorie.

- Nodi completi archivistici

I nodi completi archivistici comprendono i nodi di mining, i nodi staking e i nodi di autorità. I masternode sono un altro tipo speciale di nodo. 

- Nodi di mining (Miner)

Comunemente chiamati "miner", questi nodi risolvono complessi enigmi crittografici in un processo chiamato "mining". Ogni miner ambisce ad essere il primo nodo a creare un nuovo blocco nella blockchain e a dimostrare che è colui che ha eseguito il lavoro richiesto (da cui la Proof of Work - PoW). Una volta che l'intera rete verifica una transazione, un nuovo blocco viene aggiunto alla blockchain esistente e il miner riceve una ricompensa.

Nel whitepaper Bitcoin, Satoshi utilizza la parola "nodo" come sinonimo di "miner", ma nel corso degli anni queste due definizioni leggermente diversificate. Seppure siano tecnicamente dei nodi, i miner utilizzano hardware ASIC specializzato per aggiungere blocchi alla blockchain Bitcoin e ricevere ricompense per il lavoro svolto. L'acronimo ASIC (application specific integrated circuit) significa "circuiti integrati specifici per applicazione", sono stati progettati per un uso particolare, come ad esempio il mining di Bitcoin. 

- Proof of Work (PoW)

https://www.blockchain4innovation.it/criptovalute/blockchain-cosa-sono-i-protocolli-pow-e-pos-e-a-cosa-servono/

Il termine Proof-of-Work (PoW) indica l’algoritmo di consenso alla base di una rete blockchain. Questo algoritmo viene utilizzato per confermare le transazioni e produrre i nuovi blocchi della catena; PoW incentiva i miner a competere tra loro nell’elaborazione degli scambi, ricevendo in cambio una ricompensa. I miner risolvono il problema, danno vita a un nuovo blocco e confermano tutte le transazioni al suo interno.

Il nodo che per primo risolve il puzzle ha diritto di inserire il blocco sulla blockchain e ottiene una ricompensa per incentivare la continuazione del lavoro. Solo in questo modo un utente può essere sicuro che tutte le proprie transazioni vengano incluse nella blockchain.

- Nodi di Staking

Il principio di consenso alla base della convalida delle operazioni dei nodi staking è la Proof of Stake (PoS). Per partecipare alla creazione, all'approvazione e alla convalida dei blocchi, gli staker sono tenuti a detenere determinati quantitativi di monete. Oltre alle monete investite, gli algoritmi di consenso PoS considerano anche il tempo nella blockchain, il numero totale di staker nella blockchain, nonché un fattore casuale nel determinare chi convalida un blocco.

- Nodi di Autorità

Un altro modello di consenso è la Proof of Authority (PoA), che è più popolare nella configurazione di catene private. I nodi definiti "autorità" sono progettati per creare e convalidare nuovi blocchi nella blockchain. Per la convalida è richiesta la maggioranza delle autorità.

- Masternode

Infine, i masternode sono un altro tipo di nodi completi. Oltre a memorizzare l'intera blockchain e a convalidare le transazioni, i masternode stabilizzano e rendono sicuro il loro intero ecosistema e possono offrire servizi come transazioni private, transazioni istantanee, gestione della tesoreria, finanziamento e voto di governance. 




