## 📊 Progetto: Tre Italiani a Manchester 🏟️
Benvenuti nel repository "Tre Italiani a Manchester", un progetto che esplora ed analizza dati calcistici della Premier League per raccontare storie attraverso i numeri.
Questo progetto è stato sviluppato utilizzando strumenti di **data analysis** e visualizzazione per creare un quadro chiaro e dettagliato delle partite e delle performance dei giocatori.

## 📝 Descrizione del progetto
Il progetto si concentra sull'analisi di dati storici della Premier League con un focus particolare sull'estrazione di informazioni rilevanti come:

- Analisi dettagliata degli eventi in campo (passaggi, tiri, falli, ecc.).

- Creazione di metriche avanzate come match_id per identificare le partite.

- Visualizzazione di dati spaziali, come le coordinate degli eventi sul campo.

- Esplorazione delle caratteristiche dei giocatori e delle squadre.

- Infine viene creato un piccolo sistema RAG con Ollama 3.2 per 'aiutarci' a prendere decisioni sui giocatori in base ai nostri dati.

## 📂 Struttura del progetto
File principali:

**1**. Progetto_Tre_italiani_a_Manchester.ipynb – Notebook contenente il codice Python per l'analisi e la visualizzazione dei dati.

**2**. 20-21_plEventsData.csv – Dataset utilizzato per l'analisi, contenente oltre 600.000 eventi calcistici della Premier League.

**3**. Arsenal_AI_assistant.ipynb - File contenente l'assistente AI che ci aiuta a prendere decisioni per la partita successiva analizzando le partite precedenti. 

## 🔧 Tecnologie utilizzate
- Linguaggi : Python

- Librerie per l'Analisi Dati : Pandas, Numpy

- Librerie per la Visualizzazione Dati : Seaborn, Matplotlib
  
- Ambiente di Sviluppo : Google Colab

## 🚀 Come iniziare
1️⃣ Prerequisiti
Assicurati di avere installato:

Python 3.x

Librerie: pandas, numpy, seaborn, matplotlib

2️⃣ Clonare il repository
bash
Copy
Edit
git clone https://github.com/Luigimascolo123/Tre-Italiani-a-Manchester.git
cd Tre-Italiani-a-Manchester
3️⃣ Eseguire il notebook
Apri il file Progetto_Tre_italiani_a_Manchester.ipynb in Google Colab o Jupyter Notebook e segui le istruzioni.

## 🌟 Risultati principali
Numero totale di squadre: 20

Numero totale di partite analizzate: 380

Eventi totali processati: 607.656

Feature chiave analizzate:

Coordinate spaziali degli eventi (x, y, endX, endY)

Eventi correlati e giocatori coinvolti

Riconoscimento di eventi chiave come tiri, gol e passaggi

## 📊 Esempi di visualizzazioni
🔥 Heatmap degli eventi sul campo
📌 Traccia le posizioni degli eventi per analizzare le aree di gioco più utilizzate.

📈 Statistiche delle squadre
📌 Confronta le performance delle diverse squadre della Premier League.

## 🤝 Contributi
Hai idee o suggerimenti per migliorare il progetto?
Sentiti libero di aprire una issue o inviare una pull request!

## 📧 Contatti
Autore: Luigi Mascolo
Email: luigi.mascolo@example.com
LinkedIn: linkedin.com/in/luigimascolo

## 📜 Licenza
Questo progetto è distribuito sotto licenza MIT.
Sentiti libero di utilizzarlo e modificarlo secondo le tue necessità.
