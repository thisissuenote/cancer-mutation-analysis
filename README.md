# cancer-mutation-analysis
1. Overview

Exploratory analysis of cancer mutation and clinical data using Python and pandas.

This project focuses on data cleaning, mutation analysis, and integration of clinical and genomic data.

2. Tools

Python

pandas

Jupyter Notebook

Plotly

3. Dataset

This project uses synthetic clinical and genetic mutation datasets generated for educational and portfolio purposes.

clinical.csv: Synthetic patient-level clinical information.

mutation.csv: Synthetic genetic mutation records.

The datasets do not represent actual patients or real clinical cases. They are intended for practicing data cleaning, exploratory data analysis, and integration of clinical and genomic data using Python.

4. Project Scope

This is a self-directed learning project focused on applying Python and pandas to a simulated cancer genomics dataset. The analysis is exploratory and does not support clinical decision-making.

5. Analysis Workflow

Inspect clinical and mutation datasets.

Identify missing values and duplicate mutation records.

Remove duplicate mutation records.

Merge clinical and mutation data using patient_id.

Explore mutation counts by gene and patient.

Analyze the distribution of mutation consequences.

Explore mutation patterns across age groups and cancer stages.

6. Data Handling

Duplicate mutation records are removed before downstream analyses.

Records with missing consequence values are excluded from consequence-distribution analysis.

Clinical data are used as the base when merging datasets, preserving patients listed in the clinical dataset.

The absence of a recorded mutation does not necessarily confirm that a patient has no mutations.

7. Repository Structure

```text
cancer-mutation-analysis/
├── README.md
├── cancer-mutation-analysis.ipynb
└── data/
    ├── clinical.csv
    └── mutation.csv
```

8. Limitations

This is an exploratory data analysis project. Results depend on the completeness and quality of the available data and should not be interpreted as clinical conclusions.
