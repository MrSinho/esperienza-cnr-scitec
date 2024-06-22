---
title  : "Produzione biotecnologica dell'enzima"  
draft  :  false
toc    :  true
math   :  true
editURL: ""
weight : 2

cascade:
    type: "docs"
---

La produzione ricombinante di una proteina termostabile richiede un approccio dettagliato che coinvolge diverse fasi operative, tecniche di screening ad alto rendimento e l'assistenza di proteine chaperonine per il corretto folding della proteina. Di seguito sono illustrati i passaggi e le metodologie chiave del processo.

‎


{{< tabs items="Screening, Trasformazione, Biofermentazione e recupero, Purificazione, Saggi" >}}

{{< tab >}}

## Screening ad alto rendimento

La costruzione di una libreria genetica per isolare un ceppo termoresistente coinvolge l'acquisizione diretta di campioni da ambienti estremi, come regioni vicino ai vulcani, deserti o altre aree con condizioni ambientali estreme di temperatura. Questo approccio mira a identificare organismi che hanno sviluppato adattamenti per sopravvivere e prosperare in tali ambienti rigidi, tra cui la capacità di produrre proteine termostabili.

Dai campioni raccolti, vengono isolati organismi (come batteri termofili) o estratti di DNA genomico che possono contenere geni di interesse, tra cui quelli che codificano per proteine termostabili. Una volta ottenuto il DNA, i geni di interesse vengono amplificati utilizzando tecniche come la PCR per creare una libreria di varianti genetiche. Le varianti genetiche sono quindi inserite in vettori di espressione e trasformate in un sistema ospite come E. coli per l'espressione e l'analisi ad alto rendimento delle proteine prodotte. 

Le colture trasformate vengono quindi sottoposte a trattamenti termici e analizzate per la produzione di proteine attive a temperature elevate. Infine per la conferma vengono eseguiti dei saggi di attività ad alte temperature.
{{< /tab >}}

{{< tab >}}
## Applicazione della tecnologia del DNA ricombinante

Il gene viene inserito in un vettore di espressione (un plasmide di sintesi) che contiene i geni necessari per la trascrizione e traduzione nel sistema ospite: il gene di interesse, ottenuto legando delle estremità coesive dopo l'attività degli enzimi di restrizione; dei geni regolatori, primo fra tutti l'operone lac; dei marcatori selettivi, ossia dei geni resistenza agli antibiotici, in questo caso specifico alla kanamicina e al cloramfenicolo. 

Il plasmide viene quindi introdotto nel microrganismo per trasformazione, facilitando il processo aggiungendo in soluzione del cloruro di calcio (aumenta le dimensioni e il numero di pori sulla membrana plasmatica) e ricorrendo allo shock termico.

{{< /tab >}}


{{< tab >}}

## Biofermentazione e recupero

Le cellule trasformate vengono coltivate e indotte a esprimere la proteina target. La presenza di chaperonine nel sistema ospite aiuta nel corretto folding della proteina, migliorando la resa e la funzionalità.

Le cellule vengono quindi raccolte e lisate ricorrendo agli ultrasuoni per liberare la proteina ricombinante. Seguono le fasi di centrifugazione e raccolta del lisato, mentre il pellet viene scartato. 

È molto importante verificare di aver recuperato la proteina desiderata, cosa che si può fare velocemente attraverso un'elettroforesi su gel del campione recuperato. Occorre quindi assicurarsi che il peso molecolare delle proteine maggiormente presenti (si presume) nel lisato siano le chaperonine e la transaminasi ricombinanti.
{{< /tab >}}



{{< tab >}}
## Purificazione e concentrazione del prodotto

La proteina viene purificata per mezzo di diversi cicli di cromatografia di affinità grazie alla presenza di un'etichetta di poli-istidina (his-tag) sul gene: si tratta di una sequenza di amminoacidi aggiunta alla proteina di interesse durante il processo di clonaggio nel vettore di espressione. Comunemente, la sequenza consiste in 6-10 residui di istidina consecutivi, sebbene possano essere utilizzate varianti più lunghe o più corte a seconda dell'applicazione. La His-tag ha una forte affinità per le resine di nichel o cobalto, che funzionano come ligandi nella cromatografia di affinità.

Per valutare la concentrazione proteica si ricorre a un saggio spettrofotometrico di Bradford, mentre la soluzione viene eventualmente concentrata (se dovesse risultare troppo diluita) con delle membrane da dialisi. 

![](/media/dialisi.jpg)

{{< /tab >}}


{{< tab >}}
## Saggio di attività

Quest'ultimo saggio spettrofotometrico consente di analizzare la cinetica enzimatica della transaminasi termostabile. Trattandosi di un enzima a inibizione competitiva (non allosterica), la curva della velocità di reazione in funzione della concentrazione di substrato rispetta la cinetica di Michaelis Menten:

$$\ce{piruvato + metilbenzilammina ->[transaminasi ricombinante] alanina + acetofenone}$$

L'analisi spettrofotometrica ricorre alla lunghezza d'onda di massimo assorbimento dell'acetofenone, pari a 295 nm. A partire dal valore di assorbanza viene quindi calcolata l'attività enzimatica specifica, espressa in Unità Internazionali (UI) per unità di volume.

$$
\text{Attività enzimatica specifica} = \cfrac{\overline{\Delta A}}{\Delta t}\ \cdot\ \cfrac{V_{soluzione}}{\epsilon\ V_{enzima}}
$$
{{< /tab >}}

{{< /tabs >}}









