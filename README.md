# Entropy

**Entropy** è un gioco arcade 2D sviluppato interamente in Java, utilizzando le librerie grafiche native **Swing** e **AWT**.

## Di cosa si tratta?
In *Entropy*, controlli una sfera con l'obiettivo di raccogliere quante più stelle (punti) possibili all'interno di un'area di gioco chiusa, entro un limite di tempo prestabilito di 90 secondi.
Ma attenzione, la sfida diventa sempre più ardua:
- Al raggiungimento di determinate soglie di punteggio, compariranno **ostacoli letali** che rimbalzeranno per la mappa e che dovrai assolutamente evitare.
- Ogni 15 punti otterrai un temporaneo **boost di velocità** per aiutarti a destreggiarti meglio!
- Raggiungi **50 punti** prima che il tempo scada per ottenere la vittoria!
- Se tocchi i bordi dello schermo, esaurisci il tempo o vieni colpito da un ostacolo, sarà **Game Over**.

## Cosa serve installare?
Trattandosi di un progetto nativo, non avrai bisogno di motori grafici pesanti. È sufficiente avere installato sul proprio sistema il **Java Development Kit (JDK)** (versione 8 o superiore).

Puoi scaricare gratuitamente il JDK da uno dei distributori ufficiali, come ad esempio:
- [Adoptium (OpenJDK)](https://adoptium.net/)
- [Oracle JDK](https://www.oracle.com/java/technologies/downloads/)

## Come avviare il gioco

Ci sono due modi principali per eseguire *Entropy*:

### Metodo 1: Tramite un IDE (Consigliato)
1. Scarica i file del progetto o clona il repository
2. Apri la cartella del progetto tramite un IDE compatibile con Java, come **IntelliJ IDEA** o **Visual Studio Code**
3. Apri il file principale: `src/entropy/Test.java`
4. Esegui la classe `Test` cliccando sul tasto "Run"

### Metodo 2: Tramite Terminale (Riga di comando)
1. Apri il terminale (o il Prompt dei comandi su Windows).
2. Spostati all'interno della cartella `src` del progetto:

```bash
cd percorso/del/progetto/src
```

Compila le classi Java:

```bash
javac entropy/*.java
```

Esegui il gioco chiamando il main:

```bash
java entropy.Test
```

(Assicurati che la cartella media contenente suoni e immagini si trovi nella posizione corretta per poter essere caricata dal programma durante l'esecuzione)

Comandi di Gioco
Frecce Direzionali o W, A, S, D: Muovi il personaggio

Invio (Enter): Avvia la partita o riprova dopo un Game Over

ESC: Metti il gioco in pausa o riprendi a giocare

P: Muta / Riproduci la musica (utilizzabile dalla schermata di pausa o fine partita)

M: Muta / Riproduci gli effetti sonori (utilizzabile dalla schermata di pausa o fine partita)

E: Esci dal gioco
