# Progetto-Titanic
Descrizione del Progetto
Il progetto Titanic riguarda l'analisi di un dataset contenente informazioni sui passeggeri del Titanic, inclusi dati come sesso, classe, età e se sono sopravvissuti o meno. L'analisi si concentra sulla comprensione dei pattern relativi alla sopravvivenza dei passeggeri, con particolare attenzione a fattori come il sesso e la classe di viaggio. Il progetto utilizza diverse tecniche di analisi dei dati, tra cui la creazione di visualizzazioni, l'analisi delle correlazioni, e l'addestramento di modelli di machine learning per predire la sopravvivenza dei passeggeri.

Fasi dell'analisi
1. Preparazione dei Dati
Rimozione di colonne non necessarie: Le colonne PassengerId, Cabin, e Name sono state rimosse in quanto non utili per l'analisi.
Gestione dei valori mancanti: La colonna Age è stata riempita con la media dell'età per i passeggeri.
Descrizione dei dati: Vengono visualizzate statistiche descrittive sul dataset, incluse media, deviazione standard, minimi e massimi.
2. Visualizzazione dei Dati
Correlazione tra variabili: Utilizzo di una heatmap per visualizzare le correlazioni tra le variabili del dataset.
Distribuzione dei sopravvissuti: Un istogramma mostra la distribuzione dei passeggeri sopravvissuti e non sopravvissuti.
Distribuzione per classe: Visualizzazione della distribuzione dei sopravvissuti per classe (Pclass).
3. Analisi per Sesso e Classe
Sopravvivenza per sesso: Viene calcolata la percentuale di sopravvivenza per ciascun sesso (Donne e Uomini).
Sopravvivenza per classe e sesso: Calcolo della sopravvivenza media per ciascun sesso e classe.
Diagramma a torta: Un diagramma a torta visualizza la percentuale di sopravvissuti e non sopravvissuti per sesso.
4. Modellazione Predittiva
Modello di regressione logistica: Creazione di un modello di regressione logistica per prevedere la sopravvivenza basata su variabili come classe, sesso, età, e numero di parenti.
Creazione di un albero decisionale: Viene addestrato un albero decisionale per prevedere la sopravvivenza.
Valutazione del modello: Vengono utilizzate matrici di confusione per valutare le prestazioni dei modelli.
5. Esempi di Predizioni
Predizioni personalizzate: Il modello di regressione logistica viene utilizzato per fare previsioni su esempi specifici, come "Mario Rossi" e "Luigi Rossi", in base alle loro caratteristiche (classe, età, sesso, ecc.).
Tecnologie Utilizzate
Python: Linguaggio di programmazione utilizzato per l'analisi dei dati.
Pandas: Utilizzato per la manipolazione dei dati.
Matplotlib & Seaborn: Utilizzati per la creazione di visualizzazioni come heatmap, istogrammi e diagrammi a torta.
Scikit-learn: Utilizzato per l'addestramento dei modelli di machine learning (come regressione logistica, alberi decisionali e random forest).
