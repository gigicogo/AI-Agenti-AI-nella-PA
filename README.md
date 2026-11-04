# Sei tu a decidere: autorizzi questo agente AI?

**Laboratorio finale individuale del Modulo B — Etica e responsabilità degli agenti AI nella Pubblica Amministrazione**

Questa è una **web app statica** pensata per essere distribuita tramite **GitHub Pages**. Il file `index.html` contiene HTML, CSS e JavaScript: non servono build, pacchetti, account, chiavi API o server applicativi.

## Scopo

Il partecipante è parte del gruppo che deve valutare una proposta commerciale *interamente inventata*, **CivicaFlow AI**. Non deve saper sviluppare un agente: deve decidere quali prove chiedere al fornitore, quali limiti stabilire, come reagire a un incidente e quale decisione motivata prendere.

### Le quattro fasi

1. **La proposta (4–5 minuti).** Leggere le promesse del fornitore e scegliere tre richieste documentali prioritarie.
2. **Le condizioni (10–12 minuti).** Configurare sette scelte sul perimetro, i dati, i permessi, la supervisione, la tracciabilità, il collaudo e la gestione nel tempo.
3. **L'imprevisto (6–7 minuti).** Affrontare una possibile distorsione nella classificazione delle segnalazioni, selezionare le azioni iniziali e le condizioni per riprendere.
4. **La decisione (5–7 minuti).** Scegliere se autorizzare un **test isolato con dati fittizi**, rinviare, non procedere o — opzione volutamente problematica — passare direttamente in produzione. Motivare e indicare tre condizioni prioritarie.

Al termine compare una **scheda di restituzione personalizzata**, stampabile in PDF dal browser e scaricabile come file Markdown.

## Pubblicazione su GitHub Pages

1. Crea un repository GitHub, ad esempio `AI-Decidi-se-autorizzare-agente`.
2. Carica `index.html` nella **radice** del repository (puoi caricare anche questo README e la guida docente).
3. In **Settings → Pages** seleziona **Deploy from a branch**, ramo `main` e cartella `/ (root)`.
4. Dopo la pubblicazione, il link avrà di norma la struttura `https://<nomeutente>.github.io/<nome-repository>/`.
5. Inserisci il link o il QR code nella slide dell'esercitazione. L'URL effettivo dipende dal repository che avrai creato.

Puoi anche aprire `index.html` direttamente nel browser: funziona senza connessione Internet.

## Dati e sicurezza

- Nessun dato reale della Pubblica Amministrazione è incluso nell'esempio.
- La pagina non carica librerie, font, immagini o servizi esterni.
- Non ci sono richieste API, invii al server né salvataggi automatici.
- I dati inseriti esistono soltanto nella pagina aperta; chiudere o ricaricare la pagina li cancella.
- Il report Markdown è generato **nel browser dell'utente**.
- Il caso e il fornitore **CivicaFlow AI** sono inventati; l'attività è esclusivamente formativa.

## Limiti importanti

Questa applicazione **non** effettua analisi normativa, certificazioni o valutazioni di conformità. Le indicazioni finali sono feedback didattici basati sulle opzioni selezionate. Nella realtà un eventuale progetto deve seguire competenze, procedure, regole, verifiche e valutazioni applicabili all'Ente.

**Il messaggio da portare a casa:** scegliere di usare un agente significa definire cosa può fare, dove deve fermarsi, come si ricostruisce il suo operato e chi ne valuta i risultati.
