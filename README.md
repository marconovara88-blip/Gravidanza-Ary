# Diario di gravidanza

Diario privato per la gravidanza: pressione, peso, sintomi, appuntamenti, esami e un riepilogo da portare al ginecologo. Funziona come app sul telefono, anche senza rete.

I dati restano solo nel dispositivo di chi usa l'app. In questo repository non c'è nessun dato personale.

## Come pubblicarlo con GitHub Pages

1. Crea un nuovo repository su GitHub (ad esempio `diario-gravidanza`). Se vuoi tenere privati i file, scegli "Private": con Pages gratuito il sito però è pubblico, ma contiene solo l'app vuota, senza dati.
2. Nel repository premi **Add file → Upload files** e trascina tutti i file di questa cartella (compreso `.nojekyll`). Poi **Commit changes**.
3. Vai in **Settings → Pages**. Sotto "Build and deployment" scegli **Deploy from a branch**, branch **main**, cartella **/ (root)**, e premi **Save**.
4. Dopo uno o due minuti Pages mostra l'indirizzo, di solito `https://TUONOME.github.io/diario-gravidanza/`.

## Come installarlo su Android

1. Apri l'indirizzo con Chrome.
2. Tocca i tre puntini in alto a destra e scegli **Installa app** (o **Aggiungi a schermata Home**).
3. L'icona "Diario" compare tra le tue app.

## Copia di sicurezza e sincronizzazione

In fondo alla sezione **Visita** ci sono **Esporta i dati** e **Importa e sincronizza**. Servono per fare una copia di sicurezza e per unire le modifiche con un altro dispositivo o con la versione online. Per ogni voce vince la modifica più recente. Le voci eliminate non si sincronizzano.

## File

- `index.html`: l'app (pagina unica)
- `manifest.webmanifest`: nome, colori e icone dell'app
- `sw.js`: permette di usarla senza rete
- `icon-*.png`, `apple-touch-icon.png`: icone
- `.nojekyll`: dice a GitHub Pages di pubblicare i file così come sono
