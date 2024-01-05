# Machine Learning Mini-Contest - Predizione della Resa di Biocarburanti

La società moderna dipende fortemente dal petrolio, e nonostante i progressi nelle energie rinnovabili, il nostro quotidiano e l'industria utilizzano ancora combustibili fossili. L'obiettivo finale è costruire una società basata interamente su energie sostenibili, ma nel frattempo, le industrie cercano alternative che supportino il processo di transizione energetica. Una possibile soluzione è l'utilizzo di biocarburanti, combustibili compatibili con macchinari progettati per i combustibili fossili ma ottenuti tramite l'elaborazione di altre fonti invece che dal petrolio. Tra le molte opzioni, il trattamento della materia prima grezza (ad esempio, tramite la pirolessi) rappresenta un approccio promettente per produrre biocarburanti da rifiuti vegetali grezzi (agricoli, legnosi, ecc.).

Tuttavia, uno dei problemi di questo approccio è l'alta variabilità dell'efficienza di trasformazione, influenzata da fattori legati alle caratteristiche del materiale di origine, alle fasi di pre-elaborazione, al tipo di stoccaggio, alla manipolazione, eccetera. L'obiettivo del secondo Mini-Contest di Machine Learning (MC2) per l'anno accademico 2023/2024 è prevedere il rapporto di resa (previsione numerica) per un dato campione di materia prima grezza descritto dalle sue proprietà e caratteristiche.

## Regole del Contest
Ogni studente deve predire (regressione) il rapporto di resa realizzando uno o più modelli di previsione utilizzando tecniche di analisi dati e machine learning. La misura delle prestazioni da minimizzare è il Mean Absolute Error (MAE). È obbligatorio per lo studente che otterrà le migliori prestazioni sul dataset di test discutere i passaggi del processo seguiti per sviluppare il modello finale.
**PS:** Utilizzare solo modelli spiegati prima dell'inizio della challenge (evitare modelli di boosting e random forest).

## KNIME Student Challenge
Questa sfida è ufficialmente supportata da KNIME, l'azienda open-source specializzata in Data Science, come parte del Programma KNIME per la Gamification dell'Apprendimento. 

## Formato di Invio
Per ogni riga nel dataset, i file di invio devono contenere due colonne: *ID* e *yield*. Il primo è l'identificatore unico dell'istanza, mentre il secondo è il valore previsto. Il file di invio dovrebbe apparire come segue:

```
ID,yield
1,25.6
2,19.7
```
## Soluzione Proposta:
![MC2 Regression](https://github.com/FrancescoPanariello/MC-Regression/assets/72973754/2c8d65a4-e1f7-4f27-b4f4-16afec0302e2)

