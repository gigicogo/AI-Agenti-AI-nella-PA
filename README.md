# 🤖 Sei tu a decidere: autorizzi questo agente AI?

**Sei tu a decidere** è il laboratorio finale individuale del **Modulo — Etica e responsabilità degli agenti AI nella Pubblica Amministrazione**.

Il partecipante entra nel gruppo di valutazione di un ente e deve esaminare una proposta commerciale interamente inventata: **CivicaFlow AI**, un agente AI per la gestione delle segnalazioni dei cittadini. L’obiettivo non è sviluppare l’agente, ma decidere quali prove chiedere, quali limiti stabilire, come reagire a un incidente e se autorizzare — o meno — una sperimentazione.

<img width="1082" height="700" alt="Screenshot 2026-11-04 alle 17 26 00" src="https://github.com/user-attachments/assets/fd63db01-84ba-43d1-966a-9dde75e6650e" />


## 🎯 A chi è rivolto

Il laboratorio è pensato per:

- funzionari ed esecutori della Pubblica Amministrazione;
- responsabili di servizi, procedimenti e comunicazione con i cittadini;
- referenti ICT, RTD, privacy, sicurezza e trasformazione digitale;
- direttori e dirigenti coinvolti nelle decisioni su IA e digitalizzazione;
- formatori che vogliono proporre un’attività finale di sintesi sull’etica e la responsabilità degli agenti AI.

La durata indicativa è di **30 minuti**.

## 🧠 L’idea

Un agente AI può promettere efficienza, velocità e automazione. Ma prima di autorizzarne l’uso, un ente deve chiedersi:

- Che cosa fa davvero?
- A quali dati e sistemi può accedere?
- Quali azioni può eseguire da solo?
- Chi verifica i risultati?
- Come si ricostruisce il suo operato?
- Cosa succede se commette un errore?

Il messaggio centrale è:

> Scegliere di usare un agente significa definire cosa può fare, dove deve fermarsi, come si ricostruisce il suo operato e chi ne valuta i risultati.

## 🧩 Il caso: CivicaFlow AI

**CivicaFlow AI** è una proposta commerciale fittizia per un agente AI che aiuterebbe a gestire le segnalazioni dei cittadini, dalla lettura alla possibile risposta.

Il fornitore promette di:

- leggere le segnalazioni arrivate dal sito;
- assegnare categoria e priorità;
- consultare documenti e predisporre risposte;
- inviare direttamente le risposte al cittadino, come opzione commerciale.

La demo mostra solo tre pratiche ordinarie. Non sono ancora disponibili prove su bias, gestione degli errori, accessi, registrazioni, costi variabili e limiti di autonomia.

Il partecipante non è lo sviluppatore: è componente del gruppo di valutazione dell’ente.

## 🕹️ Le quattro fasi

| Fase | Durata | Attività |
|---:|---:|---|
| 1. **La proposta** | 4–5 minuti | Leggere le promesse del fornitore e selezionare tre richieste documentali prioritarie. |
| 2. **Le condizioni** | 10–12 minuti | Configurare sette scelte su perimetro, dati, permessi, supervisione, tracciabilità, collaudo e gestione nel tempo. |
| 3. **L’imprevisto** | 6–7 minuti | Affrontare una possibile distorsione nella classificazione delle segnalazioni, scegliere le azioni iniziali e le condizioni per riprendere. |
| 4. **La decisione** | 5–7 minuti | Scegliere se autorizzare un test isolato con dati fittizi, rinviare, non procedere oppure — opzione volutamente problematica — passare direttamente in produzione. |

Al termine, il partecipante compila una **scheda di restituzione personalizzata**, stampabile in PDF dal browser e scaricabile come file Markdown.

## 🧪 Fase 1 — La proposta

Il fornitore presenta la soluzione, ma una scheda commerciale convincente non dimostra automaticamente che il sistema sia adatto all’ente.

Il partecipante deve scegliere **tre richieste prioritarie**, tra documentazione su:

- dati e permessi richiesti;
- tracciabilità delle azioni;
- test su errori, bias e casi difficili;
- protezione di dati e sistemi;
- costi, manutenzione e uscita;
- stile grafico, premi o velocità dichiarata.

L’esercizio invita a distinguere le richieste davvero rilevanti dalle informazioni promozionali.

## ⚙️ Fase 2 — Le condizioni

Il partecipante definisce il perimetro dell’agente attraverso sette decisioni:

| Area | Domanda decisiva |
|---|---|
| Perimetro e dati | Quanto è ampio il primo impiego? |
| Perimetro e dati | A quali informazioni dovrebbe accedere? |
| Autonomia e controlli | Quali azioni può eseguire? |
| Autonomia e controlli | Come interviene il funzionario? |
| Tracciabilità e qualità | Che cosa deve essere ricostruibile? |
| Tracciabilità e qualità | Come si collauda la proposta? |
| Gestione nel tempo | Chi governa costi, aggiornamenti e problemi? |

Tre principi guidano le scelte:

1. Il fornitore propone, ma **l’ente definisce il perimetro**.
2. Una funzione utile non è automaticamente autorizzata.
3. Un test non equivale all’avvio in produzione.

## ⚠️ Fase 3 — L’imprevisto

Durante il test emerge una possibile anomalia: le segnalazioni scritte in modo incerto finiscono più spesso in bassa priorità.

Il partecipante deve scegliere le azioni iniziali più adeguate, ad esempio:

- sospendere la classificazione automatica e ogni eventuale invio;
- rivedere i casi coinvolti e confrontarli con criteri e fonti;
- coinvolgere i referenti competenti e conservare le tracce necessarie.

Deve inoltre definire le condizioni per riprendere l’uso, evitando soluzioni come continuare ad attendere il fornitore, cancellare i registri o correggere silenziosamente le risposte.

## ✅ Fase 4 — La decisione

Il partecipante sceglie una delle opzioni:

| Decisione | Significato |
|---|---|
| **Autorizzo soltanto una prova isolata** | Test con dati fittizi, senza connessione ai sistemi dell’ente e senza utilizzo reale. |
| **Rinvio la decisione e richiedo chiarimenti** | Servono documentazione, test e coinvolgimento dei referenti prima di qualsiasi sperimentazione con dati reali. |
| **Non procedo con questa proposta** | I rischi e le lacune non sono accettabili nelle condizioni offerte. |
| **Attivo direttamente l’agente in produzione** | Opzione volutamente problematica: consentirebbe accessi e invii senza ulteriori passaggi. |

Il partecipante motiva la scelta e indica **tre condizioni prioritarie**, tra ruoli e autorizzazioni, tracciabilità, accesso minimo ai dati, controllo umano, test su bias ed errori, costi e modalità di uscita.

## 💻 Come usare l’app

L’app è una **web app statica** pensata per la distribuzione tramite **GitHub Pages**.

Il file `index.html` contiene HTML, CSS e JavaScript: non servono build, pacchetti, account, chiavi API o server applicativi.

- Nessun agente reale è attivo.
- Nessun dato reale della PA è incluso nell’esempio.
- Non ci sono richieste API, invii al server o salvataggi automatici.
- I dati inseriti esistono solo nella pagina aperta.
- Chiudere o ricaricare la pagina li cancella.
- Il report Markdown è generato nel browser dell’utente.
- Funziona anche offline.

### Avvio locale

1. Scarica o clona il repository.
2. Apri `index.html` con un browser moderno.
3. Avvia il laboratorio e completa le quattro fasi.

### Clonare il repository

```bash
git clone [https://github.com/gigicogo/AI-Agenti-AI-nella-PA.git](https://github.com/gigicogo/AI-Agenti-AI-nella-PA.git)
cd AI-Agenti-AI-nella-PA
```

## 🖨️ Scheda di restituzione

Al termine dell’esercitazione è possibile:

- visualizzare una sintesi personalizzata delle scelte;
- leggere il feedback sulle decisioni prese;
- stampare o salvare la scheda in PDF dal browser;
- scaricare il report in formato Markdown.

La scheda è uno strumento di riflessione e restituzione didattica, non una valutazione formale né una documentazione di conformità.

## ⚠️ Limiti importanti

Questa applicazione:

- non effettua analisi normative;
- non rilascia certificazioni;
- non valuta la conformità di un sistema o di un procedimento;
- non sostituisce le competenze, le procedure, le regole, le verifiche e le valutazioni applicabili all’ente.

Le indicazioni finali sono feedback didattici basati sulle opzioni selezionate.

## 🧪 Possibili evoluzioni

- Aggiunta di nuovi scenari di agenti AI per diversi settori della PA.
- Versione per gruppi, con confronto delle decisioni e discussione guidata.
- Esportazione della scheda in PDF strutturato o Markdown arricchito.
- Versione inglese dell’esercitazione.
- Integrazione con checklist di governance, valutazione dei rischi e supervisione umana.
- Nuovi imprevisti su bias, sicurezza, accessi non autorizzati e dipendenza dal fornitore.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi scenari, miglioramenti didattici, correzioni e materiali di supporto.

1. Apri una Issue per proporre un’idea o segnalare un problema.
2. Oppure apri una Pull Request con una modifica o un nuovo scenario.
3. Mantieni la struttura a quattro fasi e l’attenzione a perimetro, dati, autonomia, tracciabilità e decisione umana.

---

## 📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il file `LICENSE` del repo.

## 👤 Autore e contesto

**Gianluigi Cogo**  
Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa nella Pubblica Amministrazione.

L’app nasce come esercitazione nel percorso operativo **“L’IA nella Pubblica Amministrazione — Percorso operativo per l’uso consapevole, sicuro e governato dell’IA generativa”** (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti). Per info sul corso contattami usando i social qui sotto.

- 📮 **Newsletter:** [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 **Blog:** [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ **YouTube:** [youtube.com/@gigicogo](https://youtube.com/@gigicogo)
- 💼 **LinkedIn:** [linkedin.com/in/gigicogo](https://www.linkedin.com/in/gigicogo)
