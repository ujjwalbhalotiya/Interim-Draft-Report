# Processed Variable Dictionary and Combined Dataset – World Bank Global Findex Database (2025)

## Overview

This repository contains a **processed variable dictionary** and a **combined reference dataset** developed from the **World Bank Global Findex Database (2025)** and the **World Bank Country and Lending Groups dataset**.

These resources were prepared as part of the research project:

**Application of Machine Learning for Predicting Financial Exclusion and Evaluating the Impact of Digital Connectivity on Financial Exclusion**

The repository supports transparent and reproducible research by documenting available variables, their characteristics, selection decisions, and their relevance for statistical and machine learning analyses.

---

# Repository Contents

| File | Description |
|------|-------------|
| `VariablesDocumentation.xlsx` | Processed variable dictionary containing variable metadata, descriptions, selection status, and documented inclusion/exclusion decisions for Global Findex variables. |
| `combined_dataset.csv` | Reference dataset created by integrating the Global Findex Database with the World Bank Country and Lending Groups dataset. |
| `WeightedDAnalytics_Interim.py` | Python script containing interim  data analysis procedures, including analysis steps involving survey weights and exploratory data processing, along with model evaluation of research question. |
| `data_compilation_code.py` | Python script used for compiling and integrating datasets, including merging Global Findex data with country income classification data. |
---

# Data Sources

## 1. World Bank Global Findex Database (2025)

The Global Findex Database provides internationally comparable survey data on financial inclusion indicators, including:

- Account ownership
- Savings
- Borrowing
- Digital payments
- Mobile money
- Insurance
- Financial resilience
- Other financial behaviours

**Dataset:**
```
GlobalFindexDatabase2025.csv
```

**Source:**

https://www.worldbank.org/en/publication/globalfindex/download-data

---

## 2. World Bank Country and Lending Groups

The World Bank Country and Lending Groups dataset provides official country income classifications. These classifications were used to assign income group categories to economies included in the Global Findex Database.

Income categories include:

- Low Income
- Lower Middle Income
- Upper Middle Income
- High Income

**Dataset:**
```
CountryIncomeGroup.xlsx
```

**Source:**

https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups

---

## 3. World Bank Global Findex Data Dictionary

The official Global Findex Data Dictionary provides:

- Variable definitions
- Survey questions
- Response categories
- Metadata information

**Document:**
```
DataDictionary.pdf
```

**Source:**

https://microdata.worldbank.org/catalog/7860/get-microdata

---


# Repository Purpose

This repository was developed to:

- Document variables available in the Global Findex Database.
- Provide a transparent record of variable selection and modification decisions.
- Support reproducible research practices.

---

# Disclaimer

This repository contains:

- A processed variable dictionary.
- A combined reference dataset derived from publicly available World Bank datasets.

