# HR_Google_advacend_analytics_professional_certificate
Relazione finale basata sulla strategia PACE

1. Pianificazione (Plan)
Nella fase di pianificazione, ci siamo concentrati sull'identificazione del problema principale: la previsione del turnover dei dipendenti presso un'azienda utilizzando un dataset HR. Gli obiettivi erano:

Predire i dipendenti che avrebbero lasciato l'azienda.

Identificare le variabili chiave che influenzano la decisione di abbandonare l'azienda.

Proporre soluzioni pratiche per migliorare la retention.


Domande chiave da rispondere:

Quali fattori influenzano maggiormente il turnover dei dipendenti?

Come possiamo utilizzare le informazioni dai modelli predittivi per ridurre il tasso di abbandono?


Risorse necessarie:

Dataset HR contenente informazioni come livello di soddisfazione, ore medie mensili, numero di progetti, dipartimenti e salario.

Modelli di machine learning per l'analisi e la previsione.


2. Analisi (Analyze)
Durante questa fase abbiamo eseguito l'analisi esplorativa dei dati (EDA) e implementato modelli di machine learning:

Esplorazione dei dati: Abbiamo esplorato la distribuzione della variabile target (left) e verificato la presenza di valori mancanti.

Modelli utilizzati: Logistic Regression, Random Forest, Decision Tree, e XGBoost sono stati addestrati e confrontati in base alle performance (Accuracy, Precision, Recall, F1-Score, ROC-AUC).


Risultati chiave:

Random Forest e XGBoost sono risultati i modelli migliori con performance predittive molto alte (Accuracy > 98%).

La soddisfazione del dipendente e le ore medie mensili si sono rivelate le variabili più influenti nella previsione del turnover.


3. Costruzione (Construct)
Durante la fase di costruzione, abbiamo implementato le seguenti attività:

Pulizia e trasformazione dei dati (gestione delle variabili categoriali e creazione di dummy variables).

Suddivisione del dataset in training e test set.

Addestramento e valutazione dei modelli utilizzati.


Modelli e performance:

Random Forest: Accuracy 0.9869, Precision 0.9913, Recall 0.9534, F1-Score 0.9719.

Logistic Regression: Accuracy 0.7851, ma con performance inferiore per Recall (0.3349).

XGBoost: Accuracy 0.9847, Precision 0.9808, Recall 0.9543.


4. Esecuzione (Execute)
Nella fase di esecuzione, abbiamo formulato raccomandazioni basate sui risultati dei modelli:

## Soddisfazione del dipendente: Implementare sondaggi regolari e migliorare le condizioni di lavoro per mantenere un livello di soddisfazione alto.

## Bilanciamento delle ore di lavoro: Introdurre politiche di flessibilità per ridurre le ore di lavoro e prevenire il burnout.

## Numero di progetti: Monitorare i carichi di lavoro e garantire che i dipendenti non siano sovraccaricati o sotto-utilizzati.

## Aumentare la competitività salariale: Rivedere periodicamente i salari per mantenere la competitività nel mercato.
