# Crash course
OBS Studio permette di fare il setup di scene in cui si può:
* Fare vedere uno sfondo
* Fare vedere un testo HTML
* Fare vedere lo streaming delle slide dal PC dello speaker
* Fare vedere input della telecamera
* Fare sentire input dei microfoni

Nelle scene si selezionano questi input a seconda della situazione
ad esempio nella scena "OnlySlides" il segnale della telecamera
non viene fatto vedere

Le scene sono già pronte.

# Setup

* Collegare telecamera.
* Collegare microfoni il pezzo a T è una "sound card" a cui va collegato il trasmettitore dei microfoni.
* Il marchio della sound card deve essere visibile se si guarda il PC dall'alto.
* Il cavo giusto da usare è quello con i due jack neri (dovrebbe essere già collegato alla sound card)
* Il tramettitore è il pezzo in mezzo nell'astuccio dei microfoni, va collegato con un jack nero.
* Aprire OBS Studio.
* Import Scene, puntare alla directory che contiene scene_pymi.json
* Ci sarà un errore perché non troverà il file speaker.html
* OBS manderà un avviso e bisogna farlo puntare al path giusto.
* Le scene sono WaitScreen, SpeakerAndSlides, OnlySlides, OnlySpeaker.
* Nel caso manchi qualcosa in "Sources" per una certa scena è possibile aggiungere con tasto destro sulla scena "Add Source".
* Il setup delle slide è da fare la sera del meetup, vedi: CHECKLIST_ITA.md
* Lo schema degli stream è in OBS-Streams.excalidraw, aprire in https://excalidraw.com/ usando "Open".
* Bisogna cambiare il nome degli speaker in speaker.html la sera del meetup.

## Setup for PyData

* a new `scene_pydata.json` has been created, it should work for both pydata and pymi setup
* it contains a new Background (Background PyData)
* to switch from PyData to Pymi hide/show the correct background
* a new Darken BG 2 has been created to fix some issues, we probably can use that also for PyMI
