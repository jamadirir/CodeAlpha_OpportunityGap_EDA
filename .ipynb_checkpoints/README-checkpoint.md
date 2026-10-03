# CodeAlpha Task 2 — Exploratory Data Analysis

This project analyzes responses from the Somali Youth & International Opportunities Survey. It explores respondents’ awareness, application experiences, reported barriers, and support needs.

## Project Contents

- `CodeAlpha_EDA_Concise_Cleaning_EDA_Statistical.ipynb` — data cleaning, exploratory data analysis (EDA), and statistical analysis.
- `data/raw/` — original survey CSV.
- `data/cleaned/` — cleaned survey dataset exported by the notebook.
- `visualizations/` — charts generated during the analysis.

## Analysis Overview

### 1. Data Cleaning
- Load the survey data and review its structure.
- Remove irrelevant administrative columns and prepare analysis variables.
- Check duplicate records and missing values.
- Preserve missing responses caused by survey branching; do not automatically impute them.

### 2. Exploratory Data Analysis (EDA)
- Summarize respondent characteristics and survey responses.
- Explore opportunity familiarity, application experience, information access, confidence, reported barriers, and support needs.
- Use tables and charts to describe patterns in the responses.

### 3. Statistical Analysis
- Apply Fisher’s exact test to selected comparisons between application experience and:
  - access to application guidance;
  - knowledge of reliable information sources.
- Interpret test results alongside contingency tables and sample sizes.
- A non-significant result means there is insufficient evidence of an association; it does not prove that no relationship exists.

## How to Run

1. Place the original survey CSV in `data/raw/`.
2. Install the required packages:

   ```bash
   pip install pandas matplotlib scipy jupyter
   ```

3. Open the notebook. Update the input path in the data-loading cell if your CSV filename differs.
4. Run the notebook from top to bottom. The cleaned dataset and charts will be saved to the project folders.

## Notes and Limitations

- Findings describe the survey respondents and should not be generalized to all Somali youth unless the sampling design supports that conclusion.
- The analysis is observational and does not establish causation.
- Make sure the notebook and CSV use the same latest responses before submitting.
