# Osservazioni — Esercitazione 0

Gruppo: CM-B19

Componenti (nome, cognome e username GitHub di entrambi): Andrea Gargiulo andreagargiulo10, Martina Scalia martinascalia

URL del repository condiviso: https://github.com/andreagargiulo10/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2: Ci siamo alternati in entrambi gli step

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato: ./hello il risultato osservato e' che sul terminale viene stampato il messaggio contenuto come argomento nel printf di  hello.c ("Hello, computational physics!")

Che cosa ho capito su sorgente ed eseguibile: la sorgente e' il file in cui vengono dati dei "comandi" ed e' scritta in linguaggio di programmazione (C in questo caso), mentre l'eseguibile e' il file scritto in linguaggio macchina, generato dal compilatore a partire dal file sorgente  

Output richiesto e comportamento del programma prima della modifica: Il file sorgente veniva compilato ma non stampava sul terminale alcun messaggio come invece era richiesto

Esito dopo la modifica e spiegazione della correzione: Dopo aver aggiunto il comando printf con il relativo argomento, compilando il file sorgente ed eseguendo, appariva sul terminale l'output richiesto. La correzione consiste nell'aggiunta del comando printf("Hello computational physiscs!\n"); al di fuori delle righe di commento ma sempre all'interno del main

## Step 1 — Git

Quali file ho incluso nel commit e perché:

Come ho verificato che la versione provata sia presente su GitHub:

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:

Che cosa posso concludere:

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
