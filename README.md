# CariSurg MedTech Pathways Portfolio

This repository contains my portfolio work for the CariSurg MedTech Pathways Programme 2026. It includes healthcare data cleaning, clinical data visualization, clinical context writing, digital triage workflow design, and research proposal development focused on AI-assisted emergency department triage.

---

## Who This Project Is For

This repository is intended for CariSurg tutors, reviewers, and anyone interested in beginner-friendly healthcare AI portfolio work. It is designed to show how emergency triage data can be cleaned, explored, documented, and connected to clinical decision-making.

---

## Project Overview

The project focuses on emergency department triage data and healthcare AI concepts.

The Week 0 work includes cleaning gender and pulse data, creating clinical visualizations, explaining the clinical importance of vital signs, and designing a digital triage workflow.

The Week 1 and Week 2 submissions develop a research proposal on AI-assisted emergency department triage in resource-constrained settings.

---

## Repository Structure

```text
Carisurg_MedTech_Pathways_Portfolio/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
│
├── data/
│   └── README.md
│
├── docs/
│   ├── README.md
│   ├── Assignment4_Pulse_Clinical_Context.md
│   ├── Assignment5_FiO2_Clinical_Context.md
│   ├── Assignment5_Updated_SpO2_Clinical_Context.md
│   ├── Assignment6_Digital_Triage_System.md
│   ├── Week 1 Final Submission Vishal Baboolal.pdf
│   └── Week 2 Final Submission Vishal Baboolal.pdf
│
├── notebooks/
│   ├── README.md
│   ├── Assignment1_GenderCleaning.ipynb
│   ├── Assignment2_PulseCleaning.ipynb
│   └── Assignment3_Data_Visualization.ipynb
│
└── screenshots/
```

---

## Main Contents

* `notebooks/` contains the Python notebooks for data cleaning and visualization.
* `docs/` contains clinical context write-ups, the digital triage system design, and research proposal submissions.
* `data/` is reserved for datasets and includes instructions on where to place the dataset locally.
* `screenshots/` contains visual evidence of notebook outputs and assignment work.

---

## Installation

To run the notebooks locally, clone the repository and install the required Python packages:

```bash
git clone https://github.com/VishalB210/Carisurg_MedTech_Pathways_Portfolio.git
cd Carisurg_MedTech_Pathways_Portfolio
pip install -r requirements.txt
```

Alternatively, the notebooks can be opened and run in Google Colab.

---

## How to Run the Notebooks

1. Open a notebook from the `notebooks/` folder.
2. Upload the required emergency triage dataset when prompted.
3. Run the notebook cells from top to bottom.
4. Review the cleaned outputs, summary statistics, and visualizations.

Example notebooks:

```text
notebooks/Assignment1_GenderCleaning.ipynb
notebooks/Assignment2_PulseCleaning.ipynb
notebooks/Assignment3_Data_Visualization.ipynb
```

---

## Data Instructions

The `data/` folder is intentionally kept empty except for its README file.

Dataset files are not included in this repository. To run the notebooks, place the required dataset file in the `data/` folder locally, or upload the dataset directly when using Google Colab.

Expected local structure:

```text
data/
└── EmergencyTriageDataset_Reduced_Dirty.csv
```

Cleaned datasets generated during notebook execution should be saved locally or exported as needed, but they are not required to be stored in this repository.

---

## Week 0 Work

Week 0 focused on:

* Cleaning inconsistent gender values
* Cleaning pulse values and handling missing or unrealistic readings
* Creating pulse distribution and age-versus-pulse visualizations
* Explaining the clinical importance of pulse rate, FiO₂, and SpO₂
* Designing a digital emergency triage workflow

---

## Week 1 Final Submission

The Week 1 final submission focused on an AI-assisted emergency department triage decision support proposal for a resource-constrained setting.

File:

```text
docs/Week 1 Final Submission Vishal Baboolal.pdf
```

---

## Week 2 Final Submission

The Week 2 final submission updated the research proposal using Zotero-managed citations and an automatically generated APA 7th edition bibliography.

The final proposal includes seven peer-reviewed sources related to AI-assisted emergency department triage, external validation, workflow integration, clinical usefulness, and Caribbean emergency department patient flow.

File:

```text
docs/Week 2 Final Submission Vishal Baboolal.pdf
```

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* GitHub
* Zotero
* Microsoft Word

---

## Author

**Vishal Baboolal**
Electrical & Computer Engineering Student
The University of the West Indies, St. Augustine
CariSurg MedTech Pathways Programme 2026
