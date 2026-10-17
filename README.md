# cancer-mutation-analysis
1. Overview

Exploratory analysis of cancer mutation and clinical data using Python and pandas.

This project focuses on data cleaning, mutation analysis, and integration of clinical and genomic data.

2. Tools

Python

pandas

Jupyter Notebook

Plotly

3. Analysis Workflow

Inspect clinical and mutation datasets.

Identify missing values and duplicate mutation records.

Remove duplicate mutation records.

Merge clinical and mutation data using patient_id.

Explore mutation counts by gene and patient.

Analyze the distribution of mutation consequences.

Explore mutation patterns across age groups and cancer stages.

4. Data Handling

Duplicate mutation records are removed before downstream analyses.

Records with missing consequence values are excluded from consequence-distribution analysis.

Clinical data are used as the base when merging datasets, preserving patients listed in the clinical dataset.

The absence of a recorded mutation does not necessarily confirm that a patient has no mutations.

5. Repository Structure

cancer-mutation-analysis/

├── README.md

├── cancer-mutation-analysis.ipynb

└── data/
    ├── clinical.csv
    └── mutation.csv

6. Limitations

This is an exploratory data analysis project. Results depend on the completeness and quality of the available data and should not be interpreted as clinical conclusions.
