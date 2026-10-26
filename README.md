# Landing page di Giovanni Testa

Pagina statica senza dipendenze o fase di compilazione. HTML/CSS, font di sistema, SVG locale. Nessun modulo o analytics aggiunto. Stile ispirato alla home pubblica di Energy Shift: bianco, blu #0A5BD3, titoli sans serif in grassetto.

## Pubblicazione gratuita su GitHub Pages

1. Crea un repository pubblico dedicato, ad esempio `profilo`. Con GitHub Free anche i file sorgente saranno pubblici.
2. Carica nella radice `index.html`, `en.html`, `icon.svg`, `pexton-cover.png` e `.nojekyll`. Puoi aggiungere questo README. Il selettore IT / EN collega le due pagine statiche, senza cookie o JavaScript; `en.html` è il link diretto alla versione inglese.
3. Apri **Settings → Pages → Build and deployment**.
4. Seleziona **Deploy from a branch**, poi il branch `main` e la cartella `/ (root)`, quindi **Save**.
5. Attendi la pubblicazione: il link comparirà nella stessa pagina. Il formato sarà `https://TUO-USERNAME.github.io/profilo/`.

Per avere `https://TUO-USERNAME.github.io/`, usa invece come nome del repository `TUO-USERNAME.github.io`, se non esiste già.

Non caricare l'intero vault, la cartella `.git` del progetto Sites, `.openai`, archivi di distribuzione o credenziali. Questo pacchetto contiene solo i file della pagina. Non serve un dominio a pagamento.

GitHub può registrare informazioni tecniche dei visitatori secondo la propria informativa. Il sito non integra un sistema di tracciamento proprio.

Documentazione: https://docs.github.com/en/pages/quickstart e https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
