# 🌐 Computational Drug Discovery 🧬

Welcome to **Computational Drug Discovery**! This repository features a machine learning-driven approach to assist in identifying potential treatments for **Prostate Cancer** using pharmacology data from the ChEMBL database.

![License](https://img.shields.io/badge/license-MIT-brightgreen) 
![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-%E2%9C%85-brightgreen)
![Streamlit](https://img.shields.io/badge/Streamlit-%F0%9F%94%84-red)

---

## 🚀 Project Overview

This project contains several key components to support drug discovery efforts:

- **🔬 Drug Activity Prediction**: A machine learning model trained on ChEMBL data to predict the biological activity of potential drugs. It identifies critical properties for drug effectiveness.
- **⚛️ Drug Target Affinity Prediction**: Using clustering algorithms, the model predicts drug binding affinity scores, aiding pharmaceutical scientists in designing effective drugs.
- **💻 Drug Filtering with Lipinski’s Rule**: A Streamlit web app that filters FDA-approved drugs based on Lipinski's rule of five, a key guideline in drug discovery.

---

## 🌟 Key Features

- **🧠 Machine Learning Models**: Classification models with Mean Squared Error (MSE) as an evaluation metric, supporting prostate cancer drug candidate identification.
- **🎯 Drug Candidate Proposal**: Proposed three promising drugs for prostate cancer treatment based on protein target interactions.
- **🌐 Streamlit Web Application**: An interface to filter drug candidates based on Lipinski’s rule, aiding researchers in selecting drug compounds with favorable pharmacokinetic properties.

---

## 📂 Files and Folders

| Folder/File                            | Description                                                                                     |
|----------------------------------------|-------------------------------------------------------------------------------------------------|
| `1 - Prediction of drug based on Molecular Properties` | Code and data for predicting drug activity based on molecular properties.          |
| `2 - Streamlit App - Lipinski rule based`               | Contains the code for the Streamlit app, which filters drugs based on Lipinski’s rule. |
| `3 - Drug Binding Target Affinity Prediction`          | Code for clustering and predicting drug-protein binding affinity.                              |
| `PPT - Computational Drug Discovery.pptx`              | Presentation summarizing the project and key findings.                                         |
| `Report - Computational Drug Discovery.pdf`            | Comprehensive report detailing the methodology, results, and conclusions.                      |

---

## 🛠️ Installation and Usage

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/prajwalgurnule/Computational-Drug-Discovery.git
2. **Navigate to the project directory**:
   ```bash
   cd Computational-Drug-Discovery

3. **Install the required packages: Make sure you have Python and pip installed, then run**:
   ```bash
   pip install -r requirements.txt
4. **Run the Streamlit application: To launch the Streamlit web app that filters drugs based on Lipinski's rule, run**:
   ```bash
   streamlit run "2 - Streamlit App - Lipinski rule based"/app.py

---

## 📊 Methodology

- **Data Collection**: Pharmacology data was collected from the [ChEMBL database](https://www.ebi.ac.uk/chembl/).
- **Model Training**: Machine learning models were trained on ChEMBL data to predict drug activity, leveraging chemical and molecular property features.
- **Evaluation**: Models were evaluated using **Mean Squared Error (MSE)** as the primary metric, ensuring reliable and accurate predictions.
- **Drug Affinity Prediction**: Clustering methods were used to predict drug binding affinity scores, aiding in the design of drugs with high specificity and potency.
- **Streamlit Application**: A web application was deployed with [Streamlit](https://streamlit.io/) to help pharmaceutical researchers filter FDA-approved drugs based on **Lipinski's Rule of Five**.

---

## 🌱 Future Work

- **Enhanced Drug Prediction Models**: We plan to improve model accuracy and generalization by incorporating additional data sources and experimenting with advanced machine learning algorithms.
- **Extended Application for Other Diseases**: The model could be adapted for other cancer types and diseases, broadening the utility of this drug discovery pipeline.

---

## 📜 License

This project is open-source and licensed under the [MIT License](LICENSE).

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues) for open topics or to submit new ideas.

