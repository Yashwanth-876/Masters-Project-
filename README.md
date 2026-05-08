# Master's Project

## Ricardian Model of Comparative Advantage with Bayesian Uncertainty Quantification

This project applies the classical Ricardian Model of Comparative Advantage to international agricultural trade scenarios and extends it using Bayesian uncertainty quantification. The analysis uses FAOSTAT data to study productivity, opportunity costs, Production Possibility Frontiers (PPF), Terms of Trade, and comparative advantage between countries.

---

## Project Overview

The project analyzes two bilateral trade models:

* China vs India (Rice and Wheat)
* USA vs India (Maize and Rice)

The classical Ricardian framework is further extended through Bayesian inference and Monte Carlo simulation to quantify uncertainty in comparative advantage conclusions.

The project includes:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Statistical interpretation
* Bayesian uncertainty quantification
* Monte Carlo simulation
* Visualization of productivity and opportunity cost analysis
* Ricardian Model-based analytical approach

The complete workflow is implemented using Python in Jupyter Notebook.

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---

## Dataset Information

The project uses multiple CSV datasets containing agricultural and climate-related information.

### Datasets Used

* `FAOSTAT_data_en_3-19-2026.csv`
* `FAOSTAT_data_en_4-30-2026.csv`
* `Ricardian Model 1.csv`

These datasets are used to compute productivity (yield), opportunity costs, comparative advantage, and Bayesian posterior distributions for agricultural trade analysis.

---

## Project Structure

```text
Masters-Project/
│
├── FAOSTAT_data_en_3-19-2026.csv
├── FAOSTAT_data_en_4-30-2026.csv
├── Ricardian Model 1.csv
├── Ricardian_Model_Final.ipynb
├── Mamidala_Yashwanth_Semester_Project.pdf
├── Mamidala_Yashwanth_Semester_Project.zip
└── README.md
```

---

## Key Objectives

* Perform data cleaning and preprocessing
* Analyze agricultural productivity datasets
* Apply statistical techniques for interpretation
* Visualize trends and relationships in data
* Apply the Ricardian Model using real-world FAOSTAT data
* Quantify uncertainty using Bayesian inference
* Estimate posterior comparative advantage probabilities using Monte Carlo simulation

---

## Methodology

The project follows these major steps:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Statistical Analysis
5. Data Visualization
6. Interpretation of Results

---

## Files Included

| File Name                                 | Description                               |
| ----------------------------------------- | ----------------------------------------- |
| `Ricardian_Model_Final.ipynb`             | Main Jupyter Notebook containing analysis |
| `FAOSTAT_data_en_3-19-2026.csv`           | Dataset file                              |
| `FAOSTAT_data_en_4-30-2026.csv`           | Dataset file                              |
| `Ricardian Model 1.csv`                   | Dataset file                              |
| `Mamidala_Yashwanth_Semester_Project.pdf` | Final project report                      |
| `Mamidala_Yashwanth_Semester_Project.zip` | LaTeX source files                        |

---

## Key Results

### Model 1: China vs India (Rice & Wheat)

* Opportunity costs were nearly identical
* No strong comparative advantage was observed
* Trade was not theoretically justified under the Ricardian framework

### Model 2: USA vs India (Maize & Rice)

* USA showed comparative advantage in Maize
* India showed comparative advantage in Rice
* Mutually beneficial trade conditions were identified

### Bayesian Extension

* Bayesian inference was applied using 64 years of historical yield data (1961–2024)
* Log-Normal priors and Normal-Normal conjugate updates were used
* Monte Carlo simulation with 100,000 draws quantified uncertainty
* Posterior probability of India having comparative advantage in Rice was estimated at 100%

---

## Research Highlights

* Classical Ricardian Trade Theory
* Bayesian Inference
* Monte Carlo Simulation
* Opportunity Cost Analysis
* Production Possibility Frontier (PPF)
* Terms of Trade
* Agricultural Productivity Analysis

---

## Academic Information

**Student:** Mamidala Yashwanth Reddy  
**Programme:** M.Sc. Statistics & Computing  
**Institution:** Banaras Hindu University  
**Supervisor:** Dr. Akanksha Gupta

---

## GitHub Repository

Repository Link:
[https://github.com/Yashwanth-876/Masters-Project-](https://github.com/Yashwanth-876/Masters-Project-)
