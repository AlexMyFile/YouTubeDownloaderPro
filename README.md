  Un'applicazione desktop sviluppata in Python con CustomTkinter, convertita in file eseguibile (.exe) con inclusi ffmpeg.exe, ffplay.exe e ffprobe.exe.
 👉 Funziona standalone su Windows 10/11 senza necessità di installare Python o altre librerie.
  
  YouTube Downloader Pro è un'applicazione con interfaccia grafica (GUI) per scaricare video e audio da YouTube. È costruita utilizzando le librerie Python Tkinter e
  CustomTkinter per un aspetto moderno e supporta temi chiari e scuri. L'applicazione non si affida a librerie interne per il download, ma utilizza l'eseguibile esterno
  yt-dlp.exe, che può essere aggiornato direttamente dall'interfaccia.

  Funzionalità Principali e Utilizzo
  L'interfaccia è divisa in due sezioni principali: un pannello di controllo a sinistra e un'area di contenuto a destra.

  1. Aggiungere Video alla Lista
   - Inserimento URL: Nel campo di testo in alto a destra ("Indirizzo Web di Origine"), puoi incollare l'URL di un singolo video di YouTube o di un'intera playlist.
   - Pulsanti di Aggiunta:
       - `📋 Incolla URL`: Incolla automaticamente l'URL presente negli appunti nel campo di testo.
       - `➕ Aggiungi URL`: Aggiunge l'URL dal campo di testo alla lista di download.
   - Gestione Playlist: Se inserisci l'URL di una playlist, l'applicazione ti chiederà se vuoi aggiungere l'intera playlist o solo il video specifico (se l'URL punta a un
     video all'interno di una playlist).

  2. Configurare il Download
   - Scelta Formato: Sotto il campo URL, puoi scegliere il formato di output desiderato:
       - `🎵 MP3 320kbps`: Per scaricare solo l'audio in formato MP3 di alta qualità.
       - `🎶 FLAC`: Per scaricare l'audio in formato FLAC (senza perdita di qualità).
       - `🎥 MP4 (Alta Qualità)`: Per scaricare il video completo nel formato MP4 con la migliore qualità disponibile.
   - Cartella di Destinazione:
       - La cartella di download predefinita è la cartella "Downloads" del tuo utente.
       - Puoi cambiarla in qualsiasi momento cliccando su `📁 Scegli Cartella`. La nuova cartella verrà salvata per le sessioni future.
       - Per accedere rapidamente ai file scaricati, puoi usare il pulsante `📂 Apri Cartella`.

  3. Gestire la Lista di Download
  L'area centrale mostra tutti i video che hai aggiunto, con titolo e durata.
   - Selezione: Puoi cliccare su un video nella lista per selezionarlo. Il video selezionato verrà evidenziato.
   - Pulsanti di Gestione (sul pannello sinistro):
       - `🧹 Pulisci Lista`: Rimuove tutti i video dalla lista di download.
       - `🗑 Elimina Selez.`: Rimuove solo il video attualmente selezionato.

  4. Avviare il Download
   - `⬇️ Scarica Selez.`: Avvia il download solo per il video che hai selezionato nella lista.
   - `📥 Scarica Tutto`: Avvia il download di tutti i video presenti nella lista, uno dopo l'altro.
   - `❌ Annulla Tutto`: Interrompe il processo di download in corso.

  5. Gestione delle Playlist dell'Applicazione
  Puoi salvare e ricaricare le tue liste di download.
   - `💾 Salva Playlist`: Salva l'elenco corrente di URL in un file (PlayList.json) con un nome a tua scelta. Questo ti permette di riprendere il download in un secondo
     momento.
   - `📂 Carica Playlist`: Mostra un elenco delle playlist che hai salvato. Quando ne selezioni una, puoi scegliere se:
       - Sostituire la lista corrente.
       - Aggiungere i video alla lista corrente.
   - Salvataggio Automatico: L'applicazione salva automaticamente la lista di video quando la chiudi e la ricarica al successivo avvio, permettendoti di riprendere da dove
     avevi lasciato.

  6. Strumenti e Aggiornamenti
   - `🔄 Aggiorna Strumenti`: Questo pulsante è fondamentale. Apre un menu che ti permette di:
       - Aggiornare o Installare yt-dlp: Scarica l'ultima versione dello strumento di download. È importante farlo periodicamente per garantire la compatibilità con YouTube.
       - Aggiornare o Installare ffmpeg: FFmpeg è uno strumento necessario per convertire i file in MP3, FLAC o per unire audio e video in MP4. Se i download falliscono, è
         probabile che questo componente manchi o sia obsoleto.

  7. Interfaccia e Log
   - Finestra di Log: In basso a destra, c'è un'area di testo ("mini-terminale") che mostra messaggi dettagliati su ciò che l'applicazione sta facendo: aggiunta di video,
     errori, completamento dei download, ecc. Puoi pulirla con il pulsante `📄 Pulisci Log`.
   - Barra di Stato: Sopra il log, una barra di stato ti dà informazioni rapide sull'operazione in corso (es. "In attesa...", "Download in corso...").
   - Tema Scuro/Chiaro: In basso a sinistra, puoi usare l'interruttore `Tema scuro` per cambiare l'aspetto dell'applicazione. La scelta viene salvata.

  File di Configurazione
  L'applicazione crea due file JSON nella stessa cartella dell'eseguibile:
   - config.json: Salva le tue preferenze, come la cartella di download e il tema scelto.
   - PlayList.json: Salva le liste di video che crei con la funzione "Salva Playlist".

  In sintesi, per usare l'applicazione, aggiungi uno o più URL, scegli formato e cartella, e avvia il download. Ricorda di usare "Aggiorna Strumenti" se riscontri
  problemi, poiché YouTube cambia spesso il suo funzionamento.

Teama Light
<img width="844" height="678" alt="Tema Light" src="https://github.com/user-attachments/assets/299aa0c5-6a81-4fdc-8536-01c8d75695f8" />

Tema Dark
<img width="840" height="672" alt="Teama Dark" src="https://github.com/user-attachments/assets/4cc6c2db-4466-490f-8b72-972752fb5d32" />
