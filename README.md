# Federated Causal Inference on Hospital Admission Charges

This project explores the use of **Federated Causal Inference (FCI)** to estimate the causal effect of hospital admission type (emergency vs elective) on total patient charges using the 2016 Q4 Texas ED PUDF dataset.

##  Objective

**Research Question**:  
Does the type of admission (emergency vs elective) causally influence total charges, and can we estimate this across hospitals *without sharing patient-level data*?

## 💡 Methods Used

- **Meta-analysis** using per-hospital DoWhy causal models
- **FedProx**-style federated estimation (privacy-preserving)
- Comparison of ATEs across methods

## 🧪 Tools & Technologies
- Python, Pandas, NumPy
- DoWhy (Causal Inference)
- Scikit-learn
- Matplotlib for visualization

## 📊 Results
The final FedProx ATE was significantly different from individual hospital models, showing the potential of federated learning in health economics.

## 📁 Project Structure
- `Federated_Causal_Inference.ipynb`: Full end-to-end demo
- `requirements.txt`: Dependencies
- `visuals/`: ATE comparison plots and diagrams

## ⚙️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/federated-causal-inference-hospital-admissions.git
   cd federated-causal-inference-hospital-admissions

