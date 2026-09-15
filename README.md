# FedSentry
## Federated Learning - Based Intrusion Detection System​ for Heterogeneous and Distributed Networks

### File Structure 🗃️
```
FedSentry/
│
├── data/                           # Dataset storage
│   ├── raw/                        # Original files
│   ├── processed/                  # Preprocessed partitions (IID, non-IID)
│
├── notebooks/                      # Jupyter experiments
│   ├── preprocessing.ipynb         # Data cleaning, feature engineering
│   ├── baseline_centralized.ipynb  # Centralized IDS training
│   ├── federated_training.ipynb    # FL experiments (FedAvg, FedProx)
│
├── src/                            # Core source code
│   ├── preprocessing/              # Scripts for cleaning, encoding, partitioning
│   ├── models/                     # CNN, BiLSTM, XGBoost implementations
│   ├── federated/                  # Flower/PySyft FL setup
│   ├── evaluation/                 # Metrics, confusion matrix, plots
│   └── utils/                      # Helper functions (logging, configs)
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