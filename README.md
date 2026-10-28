# Sito vetrina – guida per pubblicarlo su GitHub

Questa cartella contiene tutto il necessario per pubblicare il sito con **GitHub Pages**, gratis.

## File inclusi
- `index.html`: il sito completo (è la pagina principale, non rinominarla)
- `404.html`: pagina mostrata se qualcuno apre un indirizzo che non esiste
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: icona nella scheda del browser e nella schermata Home
- `og-image.png`: immagine di anteprima quando condividi il link su WhatsApp, Instagram, Facebook
- `robots.txt` e `sitemap.xml`: aiutano Google a trovare il sito

## Come pubblicarlo (anche dal telefono)
1. **Decomprimi** lo zip: dall'app File tocca il file e si crea una cartella.
2. Entra su **github.com** e accedi. Tocca **+** → **New repository**.
3. Come nome scrivi `sito-vetrina-` (con il trattino finale, come prima). Scegli **Public** e tocca **Create repository**.
4. Nella nuova pagina tocca **uploading an existing file** (oppure **Add file → Upload files**).
5. Seleziona **tutti i file della cartella** (non lo zip) e aspetta il caricamento.
6. In basso tocca **Commit changes**.
7. Vai in **Settings → Pages**. In *Build and deployment* scegli **Deploy from a branch**, poi **main** e **/ (root)**, e tocca **Save**.
8. Dopo 1–2 minuti il sito è online a questo indirizzo:
   **https://antoninoarcabasso.github.io/sito-vetrina-/**

## Se cambia il nome utente o il nome del repository
Sostituisci l'indirizzo `https://antoninoarcabasso.github.io/sito-vetrina-/` con quello nuovo in questi file:
`index.html` (compare 4 volte: indirizzo canonico, anteprima, immagine di anteprima e codice QR della demo), `robots.txt` e `sitemap.xml`.
Su GitHub apri il file, tocca la matita (**Edit**), modifica e fai **Commit changes**.

## Come aggiornare il sito
Apri `index.html` su GitHub, tocca la matita, modifica, **Commit changes**. Le modifiche compaiono online dopo circa un minuto.

## Dati di contatto da controllare in `index.html`
- E-mail del modulo di contatto: `antoninoarcabasso@libero.it`
- WhatsApp: `393925142096` (prefisso +39 seguito dal numero)

## Cose da sapere
- Il modulo "Contattami" apre l'app di posta del visitatore con il messaggio già scritto: non salva nulla e non serve un server.
- Il sito non usa cookie né statistiche. Salva solo la lingua scelta (IT/EN) nel browser del visitatore.
- Il codice QR della demo "Menu QR Code" usa una libreria caricata da internet (jsDelivr). Se non si carica, mostra un codice di esempio.
- Se in futuro aggiungi statistiche, un modulo che raccoglie dati o altri servizi, ti serviranno informativa privacy e, se necessario, avviso sui cookie. Per i dati dell'attività (partita IVA, ecc.) chiedi al tuo commercialista cosa va indicato.
- Le parti non incluse: assistente automatico e pagina recensioni.
