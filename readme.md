Milestone 1
Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto

Milestone 2
Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
Click sul contatto mostra la conversazione del contatto cliccato


Milestone 3
Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde
Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo.

Milestone 4
Ricerca utenti: scrivendo qualcosa nell’input a sinistra, vengono visualizzati solo i contatti il cui nome contiene le lettere inserite (es, Marco, Matteo Martina -> Scrivo “mar” rimangono solo Marco e Martina)

Milestone 5 - opzionale
Cancella messaggio: cliccando sul messaggio appare un menu a tendina che permette di cancellare il messaggio selezionato

milestone 1:
1. iniziare con gli elementi di css per replicara la grafica
2. creare la lista di contatti
3. tramite v-for, visualizzare nome e immagine di ogni contatto

milestone 2:
1. creare un indice per ciascun contatto
2. tramite l'indice assegnata, si puo usare il v-for per visualizzare i messaggi relativi al contatto attivo

milestone 3:
1. Aggiungere un event listener 'keyup' al text input
2. prendere il dato dal text input e metterlo dentro in un oggetto message
3. pushare l'oggetto nuovo al contatto attivo
4. creare un metodo che crea un altro oggetto message che contiene il messaggio 'ok' e viene inserito dentro un timeout di 1000

milestone 4:
1. 