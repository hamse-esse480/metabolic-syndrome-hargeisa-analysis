# Metabolic Syndrome Analysis — Hargeisa

## Project Overview
An Excel-based descriptive analysis of demographic, behavioral, and selected clinical/metabolic measurements in an adult dataset described in the project materials as being from Hargeisa, Somaliland.

## Tool
- Microsoft Excel

## Dataset and Source Status
The repository's exact source citation, collection period, sampling method, codebook, and diagnostic algorithm are not documented. The workbook summary describes 494 observations and a Yes/No outcome labelled metabolic syndrome, but these details and the origin of the outcome have not been independently verified in this README review.

The [International Diabetes Federation (IDF) consensus definition](https://idf.org/media/uploads/2023/05/attachments-30.pdf) requires central obesity (usually assessed by waist circumference, with specified exceptions) plus at least two of four factors: raised triglycerides, reduced HDL cholesterol, raised blood pressure, or raised fasting plasma glucose. Other harmonized definitions use three of five components. The criteria used must be identified before the outcome can be interpreted as a clinical classification.

The variables listed in the existing project notes include age, gender, education, exercise, smoking, khat use, systolic blood pressure, BMI, and fasting blood sugar. This list alone does not establish that the required diagnostic criteria were available or applied. Do not describe the recorded Yes/No outcome as a clinically confirmed diagnosis unless the original source and classification method support that interpretation.

## Analysis Workflow
- Check the original source and variable definitions
- Validate record counts, duplicate IDs, missing values, and value ranges
- Summarize participant characteristics
- Describe the dataset's recorded outcome only after confirming its meaning
- Recalculate group summaries and report denominators for all percentages

## Results and Verification Status
The previously reported figures—including 286/494 (57.9%) recorded as Yes, age and BMI means, and subgroup comparisons—have not been independently recalculated in this README review. The 57.9% figure must not be presented as verified clinical prevalence until the source data, diagnostic definition, and outcome-generation method are confirmed and the calculations are reproduced.

## Limitations
- Document the original dataset source, collection period, sampling method, and codebook.
- State whether the outcome was supplied by the source or derived in the workbook.
- Record the exact diagnostic criteria, cut-offs, required component combination, and handling of missing component values.
- Descriptive group differences do not establish causality or independent associations.
- Check that the public workbook contains no direct identifiers or sensitive individual-level information.

## Project Files
- [Dashboard preview](<./Dashboard3%20.png>)
- [Excel data-cleaning workbook](<./Data%20Cleaning%20.xlsx>)

## Project Purpose
This project demonstrates Excel-based data validation, descriptive analysis, comparison of recorded outcome groups, and responsible interpretation of health data.

## Reference
- International Diabetes Federation. [The IDF consensus worldwide definition of the metabolic syndrome](https://idf.org/media/uploads/2023/05/attachments-30.pdf).
- Endotext. [Criteria for Diagnosis of the Metabolic Syndrome](https://www.ncbi.nlm.nih.gov/books/NBK278936/table/metabolic-syndrome.T.criteria_for_diagno/).
