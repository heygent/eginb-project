# Introduzione

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
disconnesse da questi aspetti, che invece possono essere al centro nel creare
un'esperienza che abbia valore umano.

Nel valutare le risposte delle LLM si considereranno questi aspetti, anche in
relazione al tipo di modello. Per quanto questo divario sia invalicabile con
i modelli disponibili ora, sarebbe interessante fare un confronto tra modelli
multimodali e solo testuali. Avere una capacità, anche modesta, di elaborazione
di quello che può essere un'esperienza visiva, potrebbe influenzare le risposte
date.

# Fase 1

Per la fase di elaborazione dell'idea abbiamo usato questi modelli:

- GPT-4o
- Claude Opus
- Google Gemini 1.5

Preliminarmente, per scegliere un prompt efficace, 


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
> Fornisci una risposta dettagliata e ben strutturata, con un minimo di 200
> parole.

Gemini:

> Sei un esperto di tecnologie educative e museali. Vorrei progettare una nuova
> esperienza museale immersiva che utilizzi la Generative AI nel settore
> dell’educazione. Fornisci un’idea creativa e innovativa, descrivendo in
> dettaglio come la Generative AI potrebbe essere utilizzata per creare
> un’esperienza coinvolgente ed educativa per i visitatori del museo.
