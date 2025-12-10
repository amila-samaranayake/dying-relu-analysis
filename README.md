# Dying ReLU Problem – Mathematical and Experimental Analysis

This repository contains the full implementation and experimental analysis for the MSc Data Science tutorial:

**“The Dying ReLU Problem: A Mathematical and Experimental Study of Permanent Neuron Inactivity”**

The project investigates why ReLU neurons permanently stop learning in deep neural networks, supported by mathematical derivations, simulation-based experiments, and visual analysis.

---

## 📌 Contents

- `Simulation_Dying_ReLU_Problem.ipynb` – Jupyter notebook containing:
  - Deep MLP implementation  
  - Dead neuron monitoring  
  - ReLU vs Leaky ReLU vs ELU comparison  
  - Figure generation  

- `Dying_ReLU_Analysis_Report.pdf` – Final tutorial report  

- `figures/` – All figures used in the report:
  - Training loss and validation accuracy  
  - Layer-wise dead neuron analysis  
  - Average dead neuron comparison  
  - Activation heatmap visualisation  

---

## 🛠 Requirements

This project uses Python with the following key libraries:

- Python 3.9+  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- scikit-learn  

To install the dependencies:

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

---

## ▶ How to Run the Experiments

1. Clone the repository:

```bash
git clone https://github.com/your-username/dying-relu-analysis.git
cd dying-relu-analysis
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open and run:

```
Simulation_Dying_ReLU_Problem.ipynb
```

Running all cells will:
- Train the deep MLP models  
- Track dead neurons across layers  
- Generate all figures used in the report  

---

## 🧠 Key Topics Covered

- ReLU activation and zero-gradient behaviour  
- Mathematical proof of permanent neuron inactivity  
- Layer-wise dead neuron tracking  
- Comparison with Leaky ReLU and ELU  
- Internal activation heatmap visualisation  

---

## 👤 Author

**Amila Samaranayake**  
MSc Data Science

