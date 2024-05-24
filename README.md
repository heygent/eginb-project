# Introduzione

Il progetto richiedeva la scelta di un settore e di una tecnologia a cui fare
riferimento. A questo fine abbiamo scelto come settore l'educazione, e come
tecnologia la stessa Generative AI.

Nello spirito di sfruttare i punti di forza della generative AI, abbiamo optato
per un'esperienza museale che non debba per forza essere relegata a un
particolare argomento, ma che possa essere generata dinamicamente dall'utente
in base alle sue esigenze. L'utente può dare in input il
particolare argomento di cui ha un interesse, o dei documenti di cui vuole
avere un approfondimento o una sintesi, per generare automaticamente uno spazio
con cui interagire tramite realtà virtuale.

Esiste una mnemotecnica molto conosciuta, la tecnica dei loci, dove la persona
usa un luogo che le è familiare e crea associazioni tra i diversi spazi al suo
interno e le cose che vuole ricordare. Una volta associati gli spazi e gli
oggetti da ricordare, la persona può percorrere mentalmente il posto per
ritrovare gli oggetti, ricordando così la sequenza di cose da imparare.

In un museo virtuale, non c'è più l'aspetto di conservazione di un reperto,
resta solo l'aspetto didattico e di divulgazione. Questo vuol dire il potersi
sganciare da aspetti funzionali, come teche di vetro e barriere di restrizione,
e permettere che il posto possa essere una composizione visiva che non lascia
restrizioni al visitatore, e che gli permette e anzi lo incoraggia a
distruggere e rimodellare lo spazio in base a ciò che vuole ottenere.

Nello sviluppo dell'idea sarebbe interessante vedere come un'LLM si approccia
a questioni che hanno implicazioni fondamentalmente sensoriali e umane come le
precedenti, e vedere se riesce a trarre quelli che possono essere fondamentali
punti di forza di un'esperienza di questo tipo, considerando che un museo è
qualcosa di fruito da esseri umani che conoscono i propri sensi in modo tale da
sapere cosa rende un'esperienza museale godibile. Essendo l'apparato sensoriale
di un'IA fondamentalmente diverso dal nostro, come lo è il suo rapporto con la
memoria e l'apprendimento, è ipotizzabile che le loro proposte siano
disconnesse da questi aspetti, che invece possono essere centrali nel creare
un'esperienza che abbia valore umano.

Nel valutare le risposte delle LLM si considereranno questi aspetti, anche in
relazione al tipo di modello. Per quanto questo divario sia invalicabile con
i modelli disponibili ora, sarebbe interessante fare un confronto tra modelli
multimodali e solo testuali. Avere una capacità, anche modesta, di elaborazione
di quello che può essere un'esperienza visiva, potrebbe influenzare le risposte
date.

## Prompt

Per la fase di elaborazione dell'idea abbiamo usato questi modelli:

- GPT-4o
- Claude Opus
- Google Gemini 1.5

Preliminarmente, la richies


Fase 1. Sviluppare un’idea. 

A partire dalla seguente consegna:

> L’idea di partenza viene sviluppata dagli studenti, scegliendo: 
> - Un topic/museo/settore
> - Una tecnologia 
>  
> Gli studenti successivamente dovranno utlizzare tre strumenti genAI-based (es.
> chatGPT) e:
> 
> - Inserire i due elementi indicati innanzi
> - interrogare i bot, chiedendo una idea creativa e innovativa per una nuova
>   esperienza museale immersiva 
> 
> Obiettivo: esaminare ogni idea in modo più approfondito, ricorrendo ad analisi
> su documenti reperibili online:
> - confrontare i tre output ottenuto dai tre strumenti, spiegando quale fra
>   questi ha performato meglio in termini di:
>   - velocità di esecuzione
>   - puntualità e appropriatezza del risultato ottenuto

Sviluppa un prompt da inserire in tre LLM, che tenga in conto dei requisiti
richiesti e che usi come settore l'educazione, e come tecnologia la generative
AI.

GPT4-o:

> Sto cercando un’idea creativa e innovativa per una nuova esperienza museale
> immersiva nel settore dell’educazione. Vorrei sfruttare la tecnologia della
> generative AI per creare un’esperienza unica e coinvolgente per i visitatori.
> Puoi suggerirmi un concetto dettagliato che utilizzi la generative AI per
> migliorare l’apprendimento e l’interazione all’interno del museo?

La risposta è la più sintetica e diretta delle tre, e non ricorre
all'attribuire un'identità al modello. Non sembra aggiungere molto a ciò che
avremmo potuto scrivere senza particolare considerazione.

Claude:

> Immagina di essere un consulente per un museo dedicato all’educazione. Il
> museo vuole creare una nuova esperienza immersiva e coinvolgente per i
> visitatori, in particolare per gli studenti, sfruttando le potenzialità della
> generative AI.
>
> Proponi un’idea creativa e innovativa per un’installazione o un’attività
> interattiva che utilizzi la generative AI per creare un’esperienza educativa
> unica. L’idea dovrebbe stimolare l’apprendimento e la curiosità dei
> visitatori, offrendo loro l’opportunità di esplorare concetti educativi in
> modo nuovo e accattivante.
>
> Descrivi nel dettaglio come la generative AI verrebbe utilizzata all’interno
> dell’esperienza, quali contenuti o elementi visivi potrebbero essere generati
> dall’AI, e come questi si integrerebbero nell’ambiente del museo. Spiega
> anche in che modo l’esperienza proposta promuoverebbe l’apprendimento e
> l’engagement dei visitatori.
>
> Fornisci una risposta dettagliata e ben strutturata, con un massimo di 200
> parole.

Questa è la risposta più dettagliata, dove c'è l'attribuzione di un ruolo e un
richiamo al dettaglio e alla struttura, e a un limite di parole. Come prompt
sembra il più funzionale al fine di ottenere risultati mirati.

Gemini:

> Sei un esperto di tecnologie educative e museali. Vorrei progettare una nuova
> esperienza museale immersiva che utilizzi la Generative AI nel settore
> dell’educazione. Fornisci un’idea creativa e innovativa, descrivendo in
> dettaglio come la Generative AI potrebbe essere utilizzata per creare
> un’esperienza coinvolgente ed educativa per i visitatori del museo.

Il prompt è il più sintetico tra quelli proposti, ed è simile in direzione a
quello di Claude.

Come prompt di base abbiamo scelto quello di Claude, dato che era sia quello
più esaustivo sia quello che andava più verso l'essere mirato nei contenuti.

## Idee proposte

### GPT4-o

> Un'idea innovativa per un'esperienza immersiva e coinvolgente in un museo
> dedicato all'educazione potrebbe essere "Il Viaggio nel Tempo: Esplora le
> Civiltà Antiche". Questa installazione utilizza la generative AI per creare
> un'avventura interattiva in cui i visitatori possono esplorare diverse epoche
> storiche, immergendosi nella vita quotidiana di civiltà antiche come l'Egitto,
> Roma e la Grecia.
> 
> **Come viene utilizzata la Generative AI:** La generative AI può essere
> utilizzata per creare ambientazioni storiche dettagliate, personaggi
> interattivi e narrazioni personalizzate. Quando un visitatore entra
> nell'installazione, può scegliere una civiltà da esplorare tramite
> un'interfaccia touch-screen. L'AI genera in tempo reale un ambiente visivo
> tridimensionale che rappresenta la città o il villaggio di quella civiltà,
> completo di edifici, strade e paesaggi.
> 
> **Elementi Visivi e Contenuti Generati:** La generative AI può creare
> personaggi storici interattivi che i visitatori possono incontrare e con cui
> possono dialogare. Questi personaggi possono rispondere a domande, raccontare
> storie e fornire informazioni dettagliate sulla loro cultura e il loro modo di
> vivere. Inoltre, l'AI può generare ricostruzioni di eventi storici
> significativi, permettendo ai visitatori di assistere a scene importanti come
> cerimonie religiose, battaglie o momenti di vita quotidiana.
> 
> **Integrazione nell'Ambiente del Museo:** L'installazione può essere realizzata
> in una grande sala con schermi panoramici e sistemi di proiezione a 360 gradi.
> I visitatori possono muoversi liberamente nello spazio, con sensori di
> movimento che rilevano la loro posizione e adattano le proiezioni di
> conseguenza. Postazioni interattive con auricolari e microfoni permettono ai
> visitatori di comunicare con i personaggi generati dall'AI.
> 
> **Promozione dell'Apprendimento e dell'Engagement:** Questa esperienza
> immersiva stimola l'apprendimento e la curiosità dei visitatori attraverso un
> approccio hands-on e coinvolgente. I visitatori non solo apprendono fatti
> storici, ma vivono esperienze che li aiutano a comprendere meglio i contesti
> culturali e sociali delle civiltà studiate. La possibilità di interagire con
> personaggi storici e partecipare a eventi significativi rende l'apprendimento
> dinamico e memorabile, aumentando l'engagement e la retentività delle
> informazioni acquisite.

Idea OK

## Claude

> Ecco la mia proposta per un'installazione interattiva che sfrutti la generative
> AI per creare un'esperienza educativa coinvolgente nel museo:
> 
> "Viaggio nel Tempo Generativo"
> 
> L'idea è di creare una stanza immersiva che trasporti i visitatori in diverse
> epoche storiche utilizzando proiezioni e ambienti generati dall'AI.
> All'ingresso, i visitatori scelgono un periodo storico di interesse (ad es.
> Antico Egitto, Rinascimento, Rivoluzione Industriale, ecc.). 
> 
> Utilizzando algoritmi di generative AI addestrati su un vasto database di
> immagini, opere d'arte, fotografie e descrizioni relative all'epoca
> selezionata, l'AI genera in tempo reale un ambiente visivo dettagliato e
> realistico che avvolge completamente i visitatori. Paesaggi, edifici, oggetti,
> persone e scene di vita quotidiana caratteristici del periodo storico prendono
> vita sulle pareti.
> 
> I visitatori possono interagire con l'ambiente generato, esplorando liberamente
> lo spazio. Toccando elementi proiettati, ricevono informazioni, curiosità e
> approfondimenti, generati anch'essi dall'AI sulla base di una knowledge base
> validata. L'esperienza è personalizzata in base alle azioni e agli interessi
> dei singoli visitatori.
> 
> Alcune zone tematiche permettono di sperimentare attività specifiche, ad
> esempio:
> - Un cavalletto con una tela "magica" su cui i visitatori possono far comparire
>   opere d'arte generate dall'AI nello stile del periodo 
> - Un tavolo con oggetti d'epoca che, se toccati, svelano storie e dettagli sul
>   loro utilizzo, con immagini e scene di contesto generate dall'AI
> - Personaggi storici con cui dialogare: l'AI genera risposte appropriate sulla
>   base di biografie e documenti dell'epoca.
> 
> Questa esperienza stimola l'apprendimento in modo nuovo e accattivante. I
> visitatori sono protagonisti attivi, sperimentano in prima persona la storia e
> la cultura del passato, con un approccio multisensoriale. La generative AI
> permette di creare ambienti dinamici, realistici e interattivi, che favoriscono
> l'immersione, la curiosità e la memorizzazione delle informazioni attraverso
> l'esperienza diretta.
> 
> Il "Viaggio nel Tempo Generativo" può adattarsi a diverse fasce d'età e a varie
> aree tematiche del museo. Rappresenta un modo innovativo per avvicinare
> studenti e visitatori alla conoscenza del passato, sfruttando il potenziale
> della generative AI per rendere l'apprendimento un'avventura coinvolgente e
> indimenticabile.

### Gemini

> **Un Viaggio Interattivo Attraverso la Storia con la Generative AI**
> 
> Propongo la creazione di un'esperienza immersiva chiamata **"Eco dal
> Passato"**, che utilizza la generative AI per far rivivere la storia ai
> visitatori, con un focus particolare sugli studenti. 
> 
> **Ecco come funzionerebbe:**
> 
> 1. **Il Portale del Tempo:** All'ingresso, un grande schermo touchscreen funge
> da "portale" temporale. La AI, addestrata su un vasto database di eventi
> storici, personaggi e periodi, invita i visitatori a scegliere un'epoca da
> esplorare. 
> 
> 2. **Storie Generate e Visualizzate:**  Sulla base della scelta, la AI genera
> una "capsula del tempo" personalizzata: una breve narrazione che descrive la
> vita quotidiana in quel periodo storico. La narrazione è arricchita da
> immagini, musiche e suoni generati dall'AI che rispecchiano l'epoca
> selezionata. Ad esempio, se si sceglie il Rinascimento italiano, la AI potrebbe
> generare immagini di botteghe artigiane, musica dell'epoca e descrizioni di
> abiti e cibi.
> 
> 3. **Interazione e Apprendimento:** I visitatori non si limitano ad osservare
> passivamente. Attraverso il touchscreen, possono interagire con l'ambiente
> generato, "intervistando" personaggi storici creati dalla AI (tramite chatbot)
> o esplorando oggetti 3D ricostruiti digitalmente.
> 
> 4. **Lascia la Tua Eco:** Alla fine dell'esperienza, i visitatori possono
> creare la propria "eco dal passato": una breve riflessione testuale o un
> disegno ispirato da ciò che hanno appreso. L'AI trasforma le loro creazioni in
> un formato digitale che si integra nell'installazione, creando un mosaico
> collettivo di "eco" che si arricchisce con il contributo di ogni visitatore.
> 
> **Vantaggi Educativi:**
> 
> * **Apprendimento Immersivo e Coinvolgente:** L'utilizzo di elementi visivi,
> * sonori e narrativi generati dall'AI rende la storia tangibile e coinvolgente,
> * stimolando la curiosità e l'immaginazione. **Personalizzazione e
> * Interazione:** La possibilità di scegliere il proprio percorso e interagire
> * con l'ambiente rende l'esperienza più personale e memorabile, favorendo un
> * apprendimento attivo. **Sviluppo del Pensiero Critico:**  "Intervistare"
> * personaggi storici virtuali e analizzare diverse prospettive stimola il
> * pensiero critico e la capacità di valutare diverse fonti di informazione.
> 
> "Eco dal Passato" trasforma la visita al museo in un'avventura interattiva e
> personalizzata, dimostrando il potenziale della generative AI come strumento
> educativo innovativo. 
> 
