# Literature Review

## Wearable-Derived Physical Activity as a Digital Biomarker of Cognitive Function in Older Adults

### Background

Age-related cognitive impairment creates a need for scalable approaches to assessing cognitive health outside periodic clinical testing. Standardized cognitive assessments remain important for measuring domains such as memory, executive function, processing speed, and verbal fluency, but they provide discrete measurements rather than continuous observations of everyday behavior. Digital biomarkers offer a complementary approach by using objective measures collected through digital devices to characterize behavioral or physiological processes related to health.

Wearable technologies are particularly relevant because they can measure physical activity, sleep, gait, and rest-activity patterns continuously in free-living environments. Recent work in mild cognitive impairment and early Alzheimer's disease has increasingly investigated these signals as potential digital biomarkers. A 2026 scoping review of 109 studies found that rest/activity measures were the most frequently investigated wearable-derived biomarker domain, followed by speech and gait. However, relatively few studies evaluated diagnostic or prognostic performance, highlighting an important gap between identifying digital correlates of cognition and demonstrating clinically useful prediction.

### Physical Activity and Cognitive Function

A substantial literature supports an association between physical activity and cognitive function in older adults. A systematic review of objectively measured physical activity found that greater activity and lower sedentary behavior were generally associated with better global cognitive performance. Among cross-sectional studies, total physical activity produced a median standardized association of approximately β = 0.174, suggesting a positive but modest relationship.

Longitudinal evidence is similarly cautious. A 2024 systematic review and meta-analysis including 104 studies and more than 341,000 participants found that physical activity was associated with better late-life cognition and reduced cognitive impairment or decline. However, effect sizes were small, and associations were not consistently stronger in studies with longer follow-up. These results suggest that physical activity is relevant to cognitive health while also emphasizing that it is unlikely to function as a strong standalone predictor.

### Objective Accelerometry and NHANES

Objective accelerometry offers several advantages over self-reported physical activity because it directly quantifies movement during everyday life. NHANES 2011–2014 is particularly valuable for studying this relationship because adults aged 60 years and older completed standardized cognitive assessments while participants also wore wrist accelerometers over multiple days.

Zheng et al. used NHANES 2011–2014 to evaluate Monitor-Independent Movement Summary (MIMS) metrics against cognitive performance. Higher Daily MIMS and peak 30-minute MIMS were associated with better DSST and Animal Fluency performance after adjustment for covariates. Each additional 1,000 units of Daily MIMS was associated with approximately 0.67 points higher DSST performance. These findings provide a direct methodological precedent for treating wearable-measured daily activity as a candidate digital biomarker of cognitive function.

Other NHANES studies suggest that the temporal organization of activity may also contain relevant information. Research examining rest-activity rhythm parameters found that measures including interdaily stability, relative amplitude, and least-active-period activity were associated with performance on DSST, Animal Fluency, and CERAD measures. These findings suggest that overall activity volume may represent only one component of a broader behavioral phenotype that includes circadian and temporal activity structure.

### Digital Biomarkers and Predictive Modeling

Demonstrating an association between a wearable-derived feature and cognition is different from demonstrating that the feature meaningfully improves prediction. This distinction is increasingly important in digital biomarker research.

Sakal et al. used NHANES wearable data and machine-learning models to classify older adults with poor versus normal cognitive performance. Models performed best for cognitive performance measured by DSST, which assesses processing speed, working memory, and sustained attention, compared with memory and verbal-fluency outcomes. The study demonstrated that wearable-derived activity, sleep, and light-related features can contribute to cognitive classification. At the same time, traditional characteristics such as age and education remained major contributors to predictive performance.

This distinction is consistent with broader reviews of digital biomarker technologies. Digital biomarkers have shown promise for identifying mild cognitive impairment and dementia, but methodological heterogeneity, limited independent validation, and differences across devices and feature definitions remain substantial challenges. Recent reviews therefore emphasize the need for reproducible feature engineering, external validation, and direct comparison against simpler demographic or clinical baselines.

### Rationale for the Current Study

The existing literature supports wearable-measured physical activity as a plausible digital correlate of cognitive function, but it also suggests that effect sizes are generally modest. A key question is therefore not simply whether activity and cognition are statistically associated, but whether wearable-derived activity provides information beyond demographic characteristics that are already strongly related to cognitive performance.

The present project evaluates this question using two independent NHANES survey cohorts. NHANES 2013–2014 was used for the initial analysis, while NHANES 2011–2012 served as an independent replication cohort. Mean daily MIMS activity was engineered from wrist accelerometer data and evaluated against Digit Symbol Substitution Test performance after adjustment for age, sex, and education. Predictive models were then used to determine whether wearable-derived activity improved out-of-sample prediction beyond demographic variables alone.

### Relationship to the Current Findings

The results of this project are broadly consistent with previous research. Higher mean daily activity was significantly associated with better DSST performance in both NHANES cohorts after adjustment for age, sex, and education. The association was stronger in the 2013–2014 cohort than in the 2011–2012 replication cohort, but the direction was consistent across survey cycles.

These findings align closely with prior NHANES research demonstrating positive associations between Daily MIMS and DSST performance. However, the predictive analyses revealed a more nuanced result. Adding mean daily activity to demographic predictors produced only a small improvement in average cross-validated performance. Additional measures of day-to-day activity variability did not meaningfully improve prediction.

Together, these results reinforce an important distinction between association and predictive utility. Wearable-derived physical activity appears to contain reproducible information related to cognitive performance, but a single summary measure of daily activity provides only modest incremental predictive value beyond age, sex, and education. This finding is consistent with the broader literature, which generally reports small physical-activity–cognition effect sizes and identifies a need for richer and more rigorously validated digital biomarkers.

### Future Directions

Future analyses could evaluate higher-resolution wearable features that capture temporal structure rather than only overall activity volume. Candidate measures include interdaily stability, intradaily variability, relative amplitude, activity timing, sleep characteristics, and gait-derived features. These signals may capture aspects of daily behavior that are more closely related to cognitive status than mean activity alone.

Longitudinal datasets will also be necessary to determine whether wearable-derived features can predict future cognitive decline rather than cognitive performance measured at a single time point. Ultimately, the most useful digital biomarkers may arise from combining multiple behavioral and physiological domains rather than relying on any single wearable-derived feature.

## References

1. Zheng, et al. “Dose-Response Association Between Physical Activity (Daily MIMS, Peak 30-Minute MIMS) and Cognitive Function Among Older Adults: NHANES 2011–2014.” *Journals of Gerontology: Series A*, 2022.

2. Sakal, C., Li, T., Li, J., & Li, X. “Predicting poor performance on cognitive tests among older adults using wearable device data and machine learning: a feasibility study.” *npj Aging*, 10, 56, 2024. doi:10.1038/s41514-024-00177-x.

3. Sun, et al. “Association between rest-activity rhythm and cognitive function in the elderly: The U.S. National Health and Nutrition Examination Survey, 2011–2014.” 2023.

4. “Objectively assessed physical activity and sedentary behavior and global cognitive function in older adults: a systematic review.” 2021.

5. Iso-Markku, P., et al. “Physical Activity and Cognitive Decline Among Older Adults: A Systematic Review and Meta-Analysis.” *JAMA Network Open*, 7(2), e2354285, 2024.

6. Gramkow, M. H., et al. “Digital biomarkers in early Alzheimer's disease from wearable or portable technology: A scoping review.” *Journal of the Neurological Sciences*, 481, 125734, 2026.

7. Teh, S.-K., Rawtaer, I., & Tan, H. P. “Predictive Accuracy of Digital Biomarker Technologies for Detection of Mild Cognitive Impairment and Pre-Frailty Amongst Older Adults: A Systematic Review and Meta-Analysis.” *IEEE Journal of Biomedical and Health Informatics*, 26(8), 3638–3648, 2022.

8. Ding, Z., Lee, T.-L., & Chan, A. S. “Digital Cognitive Biomarker for Mild Cognitive Impairments and Dementia: A Systematic Review.” *Journal of Clinical Medicine*, 11(14), 4191, 2022.

9. “Sleep, sedentary activity, physical activity, and cognitive function among older adults: The National Health and Nutrition Examination Survey, 2011–2014.”

10. “Rest-activity rhythm and cognitive function in older adults: A scoping review and integrative framework.” 2024.
