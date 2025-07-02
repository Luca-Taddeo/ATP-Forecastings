# 🎾 ATP Match Forecasting – Machine Learning & Visual Analytics

Questo progetto utilizza il Machine Learning per prevedere l'esito degli incontri tra i Top 10 tennisti ATP, con un focus sul torneo di Wimbledon. I dati storici delle ultime stagioni sono stati elaborati per stimare le probabilità di vittoria tra giocatori a confronto.

## 📌 Obiettivo

Sviluppare un modello predittivo utilizzando dati Relativi agli ultimi 25 anni di partite del circuito ATP, integrando i risultati in una dashboard interattiva.

## 📁 Contenuto del repository

- `ATP_Forecastings.ipynb`: notebook completo con il flusso di lavoro
- `README.md`: guida al progetto

## 🛠️ Tecnologie usate

- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- Jupyter Notebook
- Tableau Public (per dashboard)
- Git & GitHub

## ⚙️ Come eseguirlo

1. Clona il repository:
```bash
git clone https://github.com/Luca-Taddeo/ATP-Forecastings.git
cd ATP-Match-Forecasting
```

2. (Opzionale) Crea un ambiente virtuale:
```bash
python -m venv venv
source venv/bin/activate  # oppure: venv\Scripts\activate
```

3. Installa le dipendenze:
```bash
pip install -r requirements.txt
```

4. Avvia il notebook:
```bash
jupyter notebook ATP_Forecastings.ipynb
```

## 📊 Dashboard interattiva

Il progetto è completato da una dashboard pubblicata su Tableau Public, che permette di:

- Visualizzare i confronti tra tennisti
- Mostrare le probabilità di vittoria stimate dal modello
- Consultare statistiche storiche dei giocatori

🔗 **[Vai alla dashboard Tableau](https://public.tableau.com/views/ATPPrevisioniWimbledon/Dashboard1?:language=it-IT&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

## 📈 Esempio di output

| Match               | Prob. Vittoria P1 | Prob. Vittoria P2 |
|--------------------|------------------|-------------------|
| Djokovic vs Sinner | 64.3%            | 35.7%             |
| Alcaraz vs Medvedev| 51.9%            | 48.1%             |

## 👤 Autore

Progetto sviluppato da **Luca Taddeo**, Junior Data Analyst.  
🔗 [Visita il mio portfolio](https://sites.google.com/view/lucataddeoport/data-projects/atp-forecastings)
