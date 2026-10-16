# 📡 Radar AI Act — Laboratorio interattivo per la Pubblica Amministrazione

**Radar AI Act** è una web app didattica per esercitarsi a riconoscere rischi e obblighi legati all'uso dell'intelligenza artificiale nella Pubblica Amministrazione italiana.

Attraverso situazioni realistiche ambientate negli uffici pubblici, i partecipanti imparano a porsi tre domande fondamentali:

1. **Che cosa fa concretamente il sistema di IA?**
2. **Quali persone, diritti o procedimenti può influenzare?**
3. **Quali verifiche occorre svolgere prima di utilizzarlo?**

🌐 **Prova l'app:** https://gigicogo.github.io/radar-ai-act/

## 🎯 A chi si rivolge

Il laboratorio è progettato per percorsi formativi sull'IA nella PA e si rivolge a funzionari, istruttori, tecnici, personale amministrativo e responsabili di servizio. Non richiede conoscenze giuridiche specialistiche.

**Durata suggerita:** 12–15 minuti, adattabile ai tempi dell'aula.

## 🕹️ Come funziona

Ogni partita propone **8 casi selezionati da un archivio di 12 scenari**. La selezione varia a ogni nuova partita e include esempi relativi a tutte e cinque le tipologie di risposta.

Per ciascun caso si svolgono due passaggi:

1. **Individuare il segnale prevalente**, scegliendo fra:
   - ⛔ Possibile pratica vietata
   - ⚠️ Possibile alto rischio
   - 👁️ Obblighi di trasparenza
   - ✅ Uso ordinario
   - ❔ Informazioni insufficienti
2. **Scegliere la motivazione più rilevante** tra le alternative proposte.

Dopo la conferma, l'app mostra la spiegazione, le verifiche da compiere, i referenti da coinvolgere e il riferimento normativo.

> **Nota didattica:** le cinque opzioni sono segnali preliminari, non categorie giuridiche sempre alternative. In un caso concreto possono coesistere più obblighi; inoltre, un uso ordinario resta soggetto alle altre norme applicabili.

## 👥 Modalità disponibili

| Modalità | Utilizzo consigliato |
| --- | --- |
| **Partecipante** | Gioco individuale o a piccoli gruppi: scelta delle risposte, feedback e punteggio. |
| **Formatore** | Proiezione in aula: discussione collettiva, soluzioni mostrate al momento opportuno, senza punteggio. |

La modalità Partecipante assegna **1 punto per la categoria corretta e 1 per la motivazione corretta**, fino a un massimo di **16 punti**.

Sono disponibili un **timer** con comandi di pausa e azzeramento, il riepilogo finale, la stampa e l'esportazione del riepilogo in un file `.txt`.

Il timer è indicativo: **non blocca la partita alla scadenza**.

### Suggerimento per l'uso in aula

Per differenziare l'attività da un normale quiz, il formatore può suddividere i partecipanti in squadre, proiettare i casi, lasciare un breve confronto e chiedere di **motivare la classificazione prima di mostrare la soluzione**. È possibile usare anche solo una parte delle carte, in base al tempo disponibile.

## 🚀 Pubblicazione su GitHub Pages

Il progetto è composto da un **solo file `index.html`**: contiene HTML, CSS, JavaScript e l'archivio degli scenari in formato JSON. Non richiede installazioni né una fase di compilazione.

1. Crea un repository GitHub, oppure aprine uno esistente.
2. Carica `index.html` nella cartella principale del repository. Aggiungi, se desideri, anche questo `README.md`.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona il branch `main` e la cartella `/ (root)`, quindi salva.
6. Apri l'indirizzo GitHub Pages assegnato al repository quando la pubblicazione sarà completata.

Per provarlo senza pubblicarlo, è sufficiente aprire `index.html` in un browser moderno.

## 🛠️ Personalizzazione

Tutti i contenuti sono modificabili direttamente nel file `index.html`:

- **Scenari e risposte:** nel blocco `<script type="application/json" id="case-data">`.
- **Colori, font e layout:** nel blocco `<style>`.
- **Interazioni, punteggi e modalità:** nel blocco JavaScript in fondo alla pagina.

Dopo una modifica ai casi, verifica che ogni scenario contenga una categoria valida, tre motivazioni e l'indice corretto della motivazione attesa. Verifica anche il funzionamento dell'esercitazione prima di usarla in aula.

## 🔒 Privacy e funzionamento tecnico

- Nessun login, database, servizio cloud applicativo o chiave API.
- Nessun cookie o sistema di analisi del traffico inserito nell'app.
- Il nome della squadra e le risposte rimangono nella sessione della pagina e **si perdono quando viene ricaricata**.
- La consultazione delle **fonti ufficiali** apre siti esterni soltanto quando l'utente seleziona i relativi link.
- Il sito è responsive e può essere utilizzato da computer, tablet e smartphone.

## ⚖️ Fonti normative

Gli scenari richiamano soprattutto il **Regolamento (UE) 2024/1689 (AI Act)**:

- [Articolo 5 — Pratiche vietate](https://ai-act-service-desk.ec.europa.eu/it/ai-act/article-5)
- [Articolo 6 — Classificazione dei sistemi ad alto rischio](https://ai-act-service-desk.ec.europa.eu/it/ai-act/article-6)
- [Allegato III — Casi d'uso ad alto rischio](https://ai-act-service-desk.ec.europa.eu/it/ai-act/annex-3)
- [Articolo 50 — Obblighi di trasparenza](https://ai-act-service-desk.ec.europa.eu/it/ai-act/article-50)

**Riferimento del contenuto didattico:** testo consolidato dell'AI Act aggiornato al 27 luglio 2026; revisione del laboratorio: ottobre 2026. Il quadro normativo è soggetto a evoluzioni: prima di riutilizzare gli scenari in futuro, verificare eventuali aggiornamenti nelle fonti ufficiali.

## ⚠️ Avvertenza

Questo progetto è un **esercizio formativo**, non uno strumento di valutazione automatica della conformità né un servizio di consulenza legale. Le risposte sono semplificazioni didattiche da discutere e non sostituiscono l'analisi della finalità, del contesto e delle caratteristiche effettive di un sistema di IA.

---

*Materiale realizzato per la formazione sull'uso consapevole e governato dell'intelligenza artificiale nella Pubblica Amministrazione.*
