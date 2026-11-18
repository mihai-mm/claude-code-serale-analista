# Corso Claude Code serale · L'esercitazione del 18 novembre

Qui trovi il materiale dell'esercitazione del modulo 7: il tuo **Analista**. È quello che hai visto con Paola: capire un cliente, cercare fuori, leggere i numeri, presentare, e un collega in più, l'agent, che lavora sulla sua scrivania e ti restituisce solo il resoconto.

L'esercitazione non parte da un esempio: parte dal tuo lavoro. Un agent legge il tuo Secondo Cervello e ti propone dove l'Analista ti serve davvero; poi crei il tuo primo agent salvato e fai una mossa sul tuo caso.

## Come si parte

1. **Fai scaricare la cartella a Claude.** Nell'app di Claude apri una conversazione nuova nella cartella del tuo Secondo Cervello (quella del pacchetto, che contiene `LEGGIMI.md`) e scrivi:

> scarica in 0-Inbox la cartella dell'esercitazione da https://github.com/mihai-mm/claude-code-serale-analista

   È la strada consigliata: lo ZIP a volte non si estrae. Se Claude ti chiede il permesso di scaricare, consenti.

2. **Fai partire la guida.** Nella stessa conversazione scrivi:

> leggi ESERCITAZIONE e guidami

   Da lì ti guida lui, un passo alla volta.

Se Claude non riesce a scaricarla, scaricala a mano: pulsante verde **Code** → **Download ZIP**, apri lo ZIP e trascina la cartella in `0-Inbox/`. I passi sono in `Guida a GitHub.md`.

Claude lavora solo dentro il tuo Secondo Cervello: una cartella lasciata nei Download non la legge.

## Cosa ti serve

- L'app di Claude per computer.
- Il tuo Secondo Cervello, con il lavoro delle lezioni precedenti. Se non hai ancora clienti o progetti, la guida te lo dice e ti fa usare il Birrificio Claudio Codice, il cliente di Paola.

## Cosa c'è dentro

- **`ESERCITAZIONE.md`**: il punto di partenza. Lo leggi tu e lo legge Claude.
- **`Da usare con Claude/`**: i file che non leggi tu, li dai a Claude.
  - *Il tuo Analista al lavoro*: la guida dell'esercitazione, in quattro passi. Prepari il vault; l'esploratore, un agent, legge il tuo lavoro e ti propone tre opportunità; crei il tuo agent salvato; fai una mossa dell'Analista sul tuo caso.
- **`skill-pronte/`**: le due skill che hai visto con Paola, `scheda-cliente` e `analisi-mercato`. La guida le usa se una tua opportunità le chiede; istruzioni in `skill-pronte/LEGGIMI.md`.
- **`Esempi di agent/`**: `revisore.md`, il revisore di Paola. Un esempio di come è fatto un agent salvato: lo guardi per scrivere il tuo.
- **`Cliente di esempio/`**: il Birrificio Claudio Codice con il suo materiale (brief, sito, listino, profilo, vendite del 2025, post, dati delle campagne), se non hai ancora clienti su cui provare.
- **`Guida a GitHub.md`**: cos'è GitHub e come scarichi il materiale a mano.

Per leggere i file non devi installare niente: si aprono già formattati qui sul sito, basta cliccarci sopra.

## Per chi finisce prima

Fai l'altra opportunità che ti ha proposto l'esploratore. Oppure fai lavorare il tuo agent sul risultato della mossa che hai appena fatto: un agent può lavorare seguendo una skill.

## Il compito per casa

Usa il tuo agent almeno due volte in settimana, su lavoro vero, e fai l'opportunità che ti è rimasta. Poi raccontalo con un'email a mihai@mihaimoraru.net entro **mercoledì 25 novembre alle 13:00**: cosa fa il tuo agent, cosa ha trovato che ti sarebbe sfuggito, cosa gli cambieresti. Nell'email niente nomi di clienti o dati riservati: scrivi il ruolo («un cliente», «la socia»).

## Se qualcosa non torna

- **Claude dice che non trova il file?** Quasi sempre la cartella non è dentro il tuo Secondo Cervello. Controlla che sia in `0-Inbox/` e che tu abbia aperto Claude nella cartella che contiene `LEGGIMI.md`.
- **Lo ZIP non si estrae?** Non insistere: torna al passo 1 e fai scaricare la cartella a Claude con il link.
- **L'app chiede il permesso di scrivere in `.claude/`?** È normale quando crea il tuo agent o installa una skill: consenti.
- **Il tuo agent non risponde al suo nome?** Apri una conversazione nuova e scrivi la frase per riprendere che trovi in fondo alla guida.
- **Una skill non compare nel menu `/`?** Scrivi `/reload-skills` o apri una conversazione nuova.
- **Il computer chiede se «Claude» può accedere a Documenti, Scrivania o Download?** Consenti.
- In aula scrivilo nella chat; a casa scrivimi a mihai@mihaimoraru.net.

---

Mihai Moraru · Corso Claude Code serale
