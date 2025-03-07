# Checklist per streaming video

* host = membro dello staff pythonmilano
* speaker = un-grande-pythonista

## Il giorno prima

* Caricare i microfoni
* host deve aver generato la streaming da YouTube Studio
  * (https://www.youtube.com/watch?v=VfzToppf_rw

## Il giorno del meetup

* host edita il file speaker.html coi dati della serata
  * Puo' essere fatto il giorno prima e lo streamer fa `git pull`
* host attacca telecamera e microfoni
* host avvia OBS studio
* host si assicura che camera e microfoni vadano
  * nelle scene SpeakerAndSlides e OnlySpeaker si deve vedere la camera centrata
  * i microfoni si dovrebbero sentire in una breve registrazione
  * idealmente, un mic dovrebbe essere passato al pubblico per le domande alla fine

* speaker e host si collegano alla wifi

* speaker va su https://vdo.ninja/?push=STREAM_ID
* va scelto uno STREAM_ID semplice! **Oppure se ne usa uno di default fornendo il link allo speaker**.
* speaker click su screen share
* speaker condivide lo schermo
* speaker indica all'host l'URL https://vdo.ninja/?view=STREAM_ID
  * attenzione che sia l'URL con scritto "view=" e non "push="
  * essendo lo schema dell'URL sempre quello, si può anche dettare la parte dopo view=

* host va su OBS, doppio click su NinjaSlides (scena OnlySlides o SpeakerAndSlides)
* host aggiorna l'URL di quella sorgente usando https://vdo.ninja/?view=STREAM_ID
* host verifica che in SpeakerAndSlides e OnlySlides si veda lo schermo dello speaker

* host deve aver configurato la streaming key usando la chiave da YouTube per questo live

* host a questo punto dovrebbe essere Ok:
  * mette scena WaitScreen finché si è in attesa
  * click su Start Recording (di sicurezza se cade la connessione) + Start Streaming
  * quando gli speaker sono pronti e si parte, click su SpeakerAndSlides
  * la regia può cambiare scena secondo preferenze/necessità
  * quello che si vede nella finestra di preview è quello che si vedrà nel record/stream
