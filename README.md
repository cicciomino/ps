# SpeedTest PRO

Pagina web a file singolo per misurare la connessione internet: ping, jitter, velocità di download e di upload, con indicatore circolare, grafico in tempo reale, informazioni sulla rete (IP e provider), valutazione per gaming, streaming e videochiamate, e storico degli ultimi 5 test salvato nel browser.

## Uso

Apri `index.html` in un browser (serve la connessione internet per caricare le librerie da CDN) e premi **Avvia speedtest**.

## Limiti

Il test usa server di terze parti raggiunti direttamente dal browser. Se un server blocca le richieste (CORS) o è irraggiungibile, il risultato può essere più basso del reale. Nell’upload, quando una richiesta fallisce il codice conta comunque metà del carico come inviato, quindi quel valore è una stima e non una misura. Per misure di riferimento conviene confrontare con un servizio dedicato.

## Pubblicazione con GitHub Pages

Il workflow in `.github/workflows/pages.yml` pubblica la pagina a ogni push su `main`. In **Settings > Pages** imposta **Source** su **GitHub Actions**, oppure usa **Deploy from a branch** con branch `main` e cartella `/ (root)`.

## Crediti

Made with ❤️ by Giaco&Dario

## Licenza

MIT
