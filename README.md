# CodeAlpha Task 2 — Exploratory Data Analysis

## Project

**Bridging the Opportunity Gap: A Data-Driven Analysis of Somali Youth Participation in International Opportunities**

### Project Aim
Understand Somali youths’ awareness, experiences, barriers, and support needs regarding international opportunities.

### Task Objective
Analyze survey data to identify important patterns and potential factors affecting access and application.

## Dataset

The analysis uses the **Somali Youth & International Opportunities Survey**, containing **80 responses**.

The survey covers:
- Awareness and familiarity with international opportunities
- Sources of opportunity information
- Application experience and guidance
- Confidence in finding and applying for opportunities
- Application barriers
- Future interest
- Support needs

## Analysis

### 1. Data Cleaning
- Reviewed the dataset structure and variables.
- Removed irrelevant administrative fields.
- Checked duplicates and missing values.
- Preserved missing responses caused by survey branching.

### 2. Exploratory Data Analysis
- Analyzed respondent characteristics and survey responses.
- Examined awareness, information access, application experience, and confidence.
- Identified common application barriers and support needs.
- Used tables and visualizations to summarize response patterns.

### 3. Statistical Analysis
- Used **Fisher’s exact test** for selected relationships involving:
  - Application guidance and application experience
  - Reliable information and application experience
- Results were interpreted together with contingency tables and sample sizes.

## How to Run

Install the required packages:

```bash
pip install pandas matplotlib scipy jupyter
```

Open the notebook and run the cells from top to bottom.

## Project Structure

```text
CodeAlpha_EDA_Concise_Cleaning_EDA_Statistical.ipynb
data/
├── raw/
└── cleaned/
visualizations/
```

## Limitations

- Findings describe the **80 survey respondents** and should not automatically be generalized to all Somali youth.
- The analysis is observational and does not establish causation.
- Missing responses caused by survey branching were not automatically imputed.
