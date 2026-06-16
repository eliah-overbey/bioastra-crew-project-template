# Analysis Directory

This directory contains the code and computational workflows used to perform analyses for this project.

The exact structure of this directory will vary depending on the needs of the project.

At a minimum, most projects should include a `scripts/` directory containing reusable analysis code.

Additional directories may be added as appropriate.

---

## scripts/

Reusable code used throughout the project.

Examples:

* Data preprocessing
* Statistical analyses
* Figure generation
* Machine learning models
* Utility functions

Document scripts using the README contained within the `scripts/` directory.

---

## notebooks/ (Optional)

Create this directory if your project uses Jupyter Notebooks.

Examples:

* Exploratory data analysis
* Data visualization
* Interactive prototyping
* Preliminary analyses

Example files:

```text
exploratory_analysis.ipynb
pca_analysis.ipynb
figure_generation.ipynb
```

Whenever possible, analyses that need to be reproduced should ultimately be migrated into reusable scripts.

---

## workflows/ (Optional)

Create this directory if your project uses analysis pipelines that combine multiple scripts or processing steps.

Examples:

* RNA-seq processing pipelines
* Multi-step data processing workflows
* Machine learning training pipelines
* Automated report generation

Example files:

```text
analysis_pipeline.md
rnaseq_workflow.sh
snakemake_pipeline.smk
nextflow_pipeline.nf
```

Document the order of operations and dependencies between analysis steps.

---

## Additional Directories

Fellows are encouraged to create additional subdirectories as needed.

Examples:

```text
analysis/
├── scripts/
├── notebooks/
├── workflows/
├── figures/
├── models/
└── utilities/
```

The goal is not to enforce a rigid structure, but to organize analyses in a way that another researcher can easily understand, reproduce, and extend, a requirement for publication at most journals.
