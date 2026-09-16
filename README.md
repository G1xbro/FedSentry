# FedSentry
## Federated Learning - Based Intrusion Detection System​ for Heterogeneous and Distributed Networks
### Research Goal
FedSentry aims to demonstrate how federated learning can enhance IDS scalability, privacy, and robustness in real-world IoT environments, addressing challenges of data heterogeneity, communication efficiency, and decentralized security.

### File Structure 🗃️
```
FedSentry/
│
├── data/                           # Dataset storage
│   ├── raw/                        # Original Dataset files
│   └── processed/                  # Preprocessed partitions (IID, Mild heteroginity, Moderate Heteroginity, Non - IID)
│
├── notebooks/                      # Jupyter experiments
│   ├── preprocessing.ipynb         # Data cleaning, feature engineering
│   ├── baseline_centralized.ipynb  # Centralized IDS training
│   └── federated_training.ipynb    # FL experiments (FedAvg, FedProx)
│
├── results/                        # Store evaluation outputs
│   ├── centralized/                # Centralized baseline metrics
│   ├── federated/                  # FL metrics under different heterogeneity
│   └── plots/                      # Graphs, charts, confusion matrices
│
├── dashboard/                      # Streamlit interface
│   ├── app.py                      
│   └── assets/                     
│
├── docs/                           # Documentation
│   ├── synopsis.md                 # Project synopsis
│   ├── methodology.md              # Detailed methodology
│   └── references.md               # Literature review notes
│
├── requirements.txt                # Python dependencies
├── README.md                       # Project overview
└── .gitignore

```