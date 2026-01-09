# 📊 Visualizzazione Scientifica in Astronomia

## Descrizione del progetto

Questo progetto si concentra sullo studio del rapporto tra le emissioni elettromagnetiche nello spettro visibile e nello spettro X di corpi celesti, utilizzando tecniche di visualizzazione scientifica applicate a dati astronomici. In particolare, l’analisi riguarda la relazione tra luminosità visibile e luminosità X, due grandezze fondamentali per comprendere i processi fisici che regolano l’emissione delle sorgenti astronomiche.

I dati osservativi in astronomia sono spesso caratterizzati da un’elevata complessità, con valori distribuiti su ampi intervalli e numerose variabili coinvolte. Per questo motivo, la visualizzazione scientifica rappresenta uno strumento chiave per esplorare i dataset e mettere in evidenza correlazioni, strutture di densità, pattern e possibili anomalie che non emergono immediatamente da un’analisi numerica.

Nel corso del progetto sono state adottate diverse tecniche di visualizzazione, tra cui scatter plot in scala logaritmica, mappe di densità e analisi delle distribuzioni monovariate, con l’obiettivo di valutare l’efficacia di ciascun approccio nell’interpretare i dati. È stato inoltre sperimentato un metodo di clustering basato sulla densità (DBSCAN) per verificare la presenza di raggruppamenti significativi tra le osservazioni.

Il progetto è stato sviluppato nell’ambito del corso Visualizzazione Scientifica (A.A. 2025/2026) e mira a mostrare come un uso consapevole delle tecniche di visualizzazione possa supportare l’analisi e l’interpretazione di fenomeni astronomici complessi.


Le slide della presentazione finale sono disponibili qui:  
[Visualizza la presentazione](https://www.canva.com/design/DAG6fLkFpy0/INrlAEsH5qZ0NVXHWp1zSA/view?utm_content=DAG6fLkFpy0&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h1f700ca13d)

---

##  🎯 Obiettivi

Gli obiettivi principali del progetto sono:

- Esplorare le relazioni tra variabili astronomiche tramite visualizzazioni efficaci
- Individuare pattern, densità e anomalie nei dati
- Valutare l’efficacia di diverse tecniche di visualizzazione
- Analizzare l’applicabilità di metodi di clustering su dati astronomici


---


## 📁 Dataset

Sono stati utilizzati dataset astronomici pubblici provenienti da fonti ufficiali:

- [SIMBAD Astronomical Database](https://simbad.cds.unistra.fr/simbad/)   
- [EXTraS Public Archive](https://extras.inaf.it)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/93/low+resolution+spectrometer)

I dati contengono misure osservative legate a luminosità e proprietà fisiche di oggetti celesti.

---


## 🧹 Preparazione dei dati

Prima della fase di visualizzazione, i dati sono stati sottoposti a:

- Pulizia e rimozione di valori mancanti o non validi
- Selezione delle variabili più rilevanti
- Applicazione di scale logaritmiche per gestire ampi intervalli di valori

Questi passaggi sono risultati fondamentali per ottenere visualizzazioni leggibili e significative.


---


## 📈 Tecniche di visualizzazione

Nel progetto sono state utilizzate diverse tecniche:

- Scatter plot in scala log–log per l’analisi delle correlazioni
- Heatmap e grafici di densità per evidenziare le concentrazioni dei dati
- Istogrammi bidimensionali per lo studio delle distribuzioni
- Distribuzioni monovariate (istogrammi e funzioni di distribuzione cumulativa)
- Boxplot logaritmico che analizza la distribuzione della luminosità per ogni ID Type

Ogni visualizzazione è stata scelta in funzione dello specifico obiettivo analitico.

---


## 🧑‍💻 Tecnologie utilizzate

- Python per l’analisi e la visualizzazione dei dati
- NumPy e Pandas per la manipolazione e l’organizzazione dei dataset
- Matplotlib e Seaborn per la creazione di grafici scientifici
- scikit-learn per l’analisi di clustering (DBSCAN)
- SciPy per la stima di densità tramite kernel (KDE)
- Canva per la realizzazione della presentazione finale


## 👥 Autori

- Daniele del Pozzo
- Andrea Rossi
- Mohamed El Jaouhari




