# Digital Biomarkers of Cognitive Function in Older Adults

## Overview

This project investigates whether wearable-derived physical activity features provide information about cognitive performance in adults aged 60 years and older beyond demographic characteristics.

Using publicly available NHANES 2011–2014 data, the project integrates wrist-worn accelerometer measurements with standardized cognitive assessments to engineer interpretable digital biomarkers and evaluate their associations with cognitive performance.

The analysis uses NHANES 2013–2014 for initial model development and NHANES 2011–2012 as an independent replication cohort. Predictive modeling will subsequently evaluate whether wearable-derived features improve out-of-sample prediction of cognitive performance beyond demographic variables alone.

## Research Question

Do wearable-derived physical activity features provide information about cognitive performance beyond age, sex, and education in adults aged 60 years and older?

## Hypothesis

Higher wearable-measured physical activity will be associated with better cognitive performance after accounting for age, sex, and education.

Exploratory analyses will also evaluate whether day-to-day activity variability provides additional information beyond overall activity level.

## Dataset

**National Health and Nutrition Examination Survey (NHANES), 2011–2014**

Two survey cycles are used:

- **2013–2014:** Primary analysis/model-development cohort
- **2011–2012:** Independent replication cohort

The analysis integrates:

- Cognitive Functioning data
- Physical Activity Monitor data
- Demographic data

Participants are adults aged 60 years and older with available cognitive assessments and sufficient wearable monitoring data.

## Outcomes

### Primary Outcome

- Digit Symbol Substitution Test (DSST)

### Secondary Outcomes

- Animal Fluency
- CERAD word learning and delayed recall

Secondary cognitive outcomes will be explored after completion of the primary DSST analysis.

## Candidate Digital Biomarkers

### Primary Features

- Mean daily activity
- Day-to-day activity variability
- Relative activity variability (coefficient of variation)

### Exploratory Features

- Wake-wear duration
- Sleep-wear duration
- Additional rest-activity features

More granular rest-activity and circadian features may be explored in future analyses using higher-resolution accelerometer data.

## Analysis

The project follows the following pipeline:

1. Data acquisition and quality control
2. Data cleaning and participant selection
3. Wearable feature engineering
4. Exploratory data analysis
5. Demographic baseline modeling
6. Adjusted statistical modeling of wearable biomarkers
7. Independent replication using NHANES 2011–2012
8. Predictive modeling and model evaluation
9. Interpretation of digital biomarkers

### Primary Statistical Models

**Baseline model:**

DSST ~ Age + Sex + Education

**Wearable model:**

DSST ~ Age + Sex + Education + Mean Daily Activity

Additional wearable features are evaluated to determine whether they provide information beyond mean activity.

## Preliminary Findings

Initial analysis of the NHANES 2013–2014 cohort included 1,386 adults aged 60–80 years with valid DSST, demographic, and wearable data.

Mean daily wearable-measured activity was positively associated with DSST performance after adjustment for age, sex, and education.

Adding mean daily activity to the demographic baseline model increased explained variance from approximately 37.7% to 39.0%.

Relative day-to-day activity variability did not provide substantial additional explanatory value beyond mean activity.

These findings are preliminary and will be evaluated for reproducibility using the independent NHANES 2011–2012 cohort.

## Repository Structure

```text
cognitivefunction/
│
├── README.md
│
├── data/
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_replication_2011_2012.ipynb
│   └── 03_predictive_modeling.ipynb
│
├── literature/
│   └── literature_review.md
│
├── results/
│   ├── figures/
│   └── tables/
│
└── src/
