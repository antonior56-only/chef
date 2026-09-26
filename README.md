# Il Mio Chef PWA

Apri `index.html` tramite un server locale o HTTPS. Il protocollo `file://` non supporta l’installazione PWA né il service worker.

## Avvio locale

Con Python installato, apri un terminale in questa cartella e avvia:

```bash
python -m http.server 8000
```

Visita `http://localhost:8000`. Il pulsante **Scarica l’app** appare quando l’app non è già aperta in modalità installata. Su browser supportati avvia il prompt nativo; su iPhone/iPad mostra i passaggi per aggiungerla alla schermata Home.

La pagina e le risorse locali vengono memorizzate nella cache. Le richieste ai servizi IA richiedono una connessione internet e una chiave API configurata nell’app.
