# Scoreboard standalone — registro delle versioni

La versione installata si vede in alto nella finestra delle impostazioni.
Qui sotto sono raccolte in un solo elenco tutte le modifiche dalla versione pubblicata stamattina (1.2.0: grafica rivista, Play non necessario a ogni round) alla 1.3.3.

## 1.3.3 — Annotare i bey dell'avversario
Formato dei dati salvati invariato (i bey avversari finiscono nello stesso campo di sempre, `bey_giocatore2` nelle esportazioni).

**Bey dell'avversario "a scoperta"**
- Si attiva quando il Player 1 ha un deck registrato e il Player 2 no (per esempio "Oppo" lasciato senza deck). Se il Player 2 ha un deck registrato, i pulsanti restano quelli di sempre.
- Sotto il Player 2 compare **＋ Bey avversario**: si scrive il nome del bey mostrato e viene associato al round. Nei round successivi i bey già scoperti diventano pulsanti, con il ＋ per quello nuovo, fino a 3 bey.
- Come per il deck registrato, nel primo ciclo i bey già usati sono disattivati; dopo il reshuffle (ogni 3 round) tornano tutti attivi. Finché il deck avversario non è completo, l'ultimo rimasto non viene preselezionato.
- Il deck scoperto vale solo per la battaglia in corso e si azzera con «Nuova partita».
- Mentre scrivi un nome, l'app suggerisce i bey avversari già digitati nelle battaglie della sessione (nessun elenco da mantenere).
- Tocco lungo su un bey avversario: ne corregge il nome in tutti i round della battaglia.

**Annotare o correggere dopo**
- I chip dei round in basso mostrano anche il bey avversario («avv. Xeno», oppure «avv. ?» se manca) e sono toccabili: si sceglie o si corregge il bey di quel round.
- Nella schermata di vittoria compare «Bey avversario da annotare» con un pulsante per ogni round mancante.
- **Storico sessione**: i round delle partite con avversario a scoperta sono toccabili, anche per le partite già archiviate e anche se durante la partita non era stato annotato nulla. Si sceglie uno dei bey già presenti o se ne scrive uno nuovo (al massimo 3 bey diversi per partita) oppure si toglie il bey. Nella stessa finestra si può correggere il nome (per esempio da abbreviazione a nome completo) in tutti i round di quella partita; un nome già usato da un altro bey della stessa partita viene rifiutato.
- Le partite archiviate prima della 1.3.0 non hanno questa funzione (non salvavano se l'avversario era a scoperta).

**Versione**
- Il numero di versione compare in alto nella finestra delle impostazioni.

Dispositivi da ricaricare dopo la pubblicazione.
