# Digital Biomarkers of Cognitive Function in Older Adults

## Overview
This project investigates whether wearable-derived activity and rest-activity features can predict cognitive performance in adults aged 60 years and older.

Using publicly available NHANES 2011–2014 data, the project integrates wrist-worn accelerometer measurements with standardized cognitive assessments to engineer interpretable digital biomarkers and evaluate their predictive value using statistical and machine-learning approaches.

## Research Question

Can wearable-derived activity and rest-activity features predict cognitive performance in adults aged 60 years and older?

## Hypothesis

Greater physical activity, greater activity intensity, and more stable rest-activity patterns will be associated with better cognitive performance.

## Dataset

National Health and Nutrition Examination Survey (NHANES), 2011–2014.

The analysis will combine:

- Cognitive Functioning data
- Physical Activity Monitor data
- Demographic data

## Outcomes

### Primary Outcome
- Digit Symbol Substitution Test (DSST)

### Secondary Outcomes
- Animal Fluency
- CERAD word learning and delayed recall

## Candidate Digital Biomarkers

- Mean daily activity
- Activity variability
- Activity intensity
- Wake/sleep wear duration
- Activity regularity
- Rest-activity rhythm measures

## Analysis

The analysis will follow this pipeline:

1. Data acquisition and quality control
2. Data cleaning
3. Wearable feature engineering
4. Exploratory data analysis
5. Statistical modeling
6. Machine-learning prediction
7. Model evaluation
8. Interpretation of digital biomarkers

## Repository Structure

```text
data/
    raw/
    processed/

notebooks/
    01_data_exploration.ipynb
    02_data_cleaning.ipynb
    03_feature_engineering.ipynb
    04_statistical_analysis.ipynb
    05_machine_learning.ipynb

literature/
results/
src/
