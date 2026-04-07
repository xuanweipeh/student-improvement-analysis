# Student Improvement Analysis in A-Level Chemistry Tutoring

## Project Overview
This project analyses anonymised tutoring outcome data from a small group of A-Level Chemistry students. The goal is to examine student progress from initial to final grades and to evaluate tutoring outcomes through multiple analytical perspectives rather than a single metric.

## Objectives
- Analyse how students moved from their initial to final grades
- Compare different ways of measuring academic progress
- Show why a single success metric may not fully capture student performance

## Dataset
The dataset contains anonymised student-level records with the following columns:
- `Student_ID`
- `Initial_Grade`
- `Final_Grade`

Grades are based on the A-Level grading scale and were mapped into ordinal numeric values for analysis.

## Methods
This project uses several complementary methods:
- **Grade transition matrix** to show movement from initial to final grades
- **Raw improvement analysis** to measure grade changes numerically
- **Gap closure analysis** to account for differences in starting point
- **Initial vs final grade distribution** to compare overall outcome shifts

## Key Findings
- Students showed clear upward movement from their initial to final grades
- Raw improvement alone was not sufficient to evaluate performance fairly, since students with lower starting grades had more room for visible gains
- Gap closure provided a useful complementary perspective by accounting for the remaining distance to the top grade
- Final outcomes were concentrated in the top grade bands, with all students finishing at either B or A

## Limitations
- The dataset is small, so the findings are more illustrative than broadly generalisable
- The analysis is limited to initial and final grades only
- Grade-based improvement metrics are influenced by students’ starting points
- The findings should be interpreted as an exploratory analysis rather than a complete explanation of student performance

## Future Work
Future extensions of this project could involve collecting a larger sample of student outcomes over time to study grade transition patterns more robustly. With more data, the analysis could also be extended toward transition proportion modelling or simple predictive approaches for final grade outcomes.

## Files
- `student_improvement_analysis.ipynb` — main analysis notebook
- `README.md` — project overview and summary
- `requirements.txt` — Python dependencies

## Note on Data Privacy
The dataset is based on anonymised real tutoring outcomes. To protect student privacy, raw data is not publicly shared unless fully anonymised and appropriate to disclose.

## Tools Used
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook