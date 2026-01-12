# Dataset for: Using active learning methods to develop social and pedagogical competence in future special educators

## Associated publication
This repository provides the research dataset supporting the manuscript:

**Toktarbekova, K., Kalykbayeva, A., Stelmakh, S., Autayeva, A., Paylozyan, Zh., Tyulyupergeneva, R.**  
*Using active learning methods to develop social and pedagogical competence in future special educators.*

The dataset is prepared in accordance with **Taylor & Francis data sharing and data availability policies**.

---

## Study context
The study employed a block-randomized quasi-experimental design to evaluate a comprehensive active learning model in the training of future specialists in special and inclusive education.

- **Sample size:** N = 112 undergraduate students  
- **Groups:** Experimental (n = 56) and Control (n = 56)  
- **Population:** Female students, Years 2–4, Special Pedagogics program  
- **Institution:** Sarsen Amanzholov East Kazakhstan University  
- **Intervention duration:** 10 weeks  

The intervention integrated:
- Problem-based learning (PBL),
- Pedagogical simulations (including mixed-reality scenarios),
- Cooperative project-based learning,
- Mobile learning and reflective micro-assignments.

---

## Dataset description
The dataset is provided as a single Excel workbook containing de-identified, analysis-ready data aligned with all quantitative and qualitative results reported in the article.

**Main file:**
- `data/raw/ActiveLearning_SpecialEd_Database.xlsx`

The dataset enables verification and replication of descriptive statistics, pre–post comparisons, between-group analyses, regression models, and qualitative coding summaries reported in the manuscript.

---

## File and sheet overview

### Core quantitative data
- **Participants** – anonymized participant IDs, group assignment, age, and year of study.
- **SPC_Scores** – social and pedagogical competence scores at two timepoints (PRE and POST), including:
  - Empathy  
  - Teamwork  
  - Adaptability  
  - Social Responsibility  
  - Integral Competence Index
- **Derived_Deltas** – post–pre change scores for all competence indicators.

### Secondary outcomes
- **MSLQ_Post** – motivational and self-regulation indicators (Intrinsic Motivation, Task Value, Self-Efficacy, Metacognitive Regulation).
- **GPA** – academic performance (grade point average).

### Process and implementation data
- **DoseByMethod** – intensity of student participation in each active learning format (minutes, sessions attended, completion rate).
- **Sessions** – weekly intervention structure by instructional format.
- **Attendance_EXP** – attendance records for the experimental group.

### Qualitative component
- **Diaries_EXP** – metadata for reflective learning diaries (week, length, anonymized identifiers).
- **Coding** – thematic coding of reflective diaries (two independent raters), including:
  - Empathic Understanding  
  - Collaboration and Group Role  
  - Adaptive Strategies  
  - Social Responsibility  
  - Professional Identity  

### Reference and verification sheets
- **Ref_Groups, Ref_Timepoints, Ref_Methods, Ref_Themes** – controlled vocabularies.
- **Summary_PRE, Summary_POST** – descriptive summaries (means and standard deviations).
- **Targets** – reference statistics used to align the dataset with reported manuscript tables.

---

## Variable conventions
- **Group codes:** `EXP` (experimental), `CTRL` (control)
- **Timepoints:** `PRE` (baseline, Week 1), `POST` (end of intervention, Week 10)
- All questionnaire scales use **5-point Likert metrics**.
- The **Integral Competence Index** is calculated as the arithmetic mean of the four subscales.

---

## Reproducibility and linkage to manuscript tables
The dataset structure allows direct reproduction of all tables and figures reported in the article, including:
- baseline group comparability,
- within-group pre–post changes,
- between-group comparisons of change scores,
- ANCOVA and regression analyses,
- effect size estimation,
- frequency analysis of qualitative codes.

Derived variables (e.g., Δ Post–Pre) are provided to support transparent verification of reported effects.

---

## Ethics and participant protection
The study protocol was reviewed and approved by the Ethics Committee of the Faculty of Psychology and Education at Sarsen Amanzholov East Kazakhstan University.

To comply with ethical standards:
- all data are anonymized and de-identified;
- no personal identifiers are included;
- full raw reflective diary texts are not publicly disclosed due to their sensitive educational content.

---

## Data availability statement (Taylor & Francis compliant)
This dataset is **available from the corresponding authors upon reasonable request**.

Public access to the full dataset is restricted to protect participant privacy and to comply with institutional ethical requirements. De-identified and aggregated data, as well as analysis-ready subsets necessary for verification or secondary research, can be provided upon request.

---

## Intended use and limitations
The dataset is intended for:
- transparency and verification of published findings,
- methodological illustration of active learning research designs,
- secondary analysis using aggregated or de-identified data.

It is not intended for identification of individual participants or institutions.

---

## License
The dataset is shared for scholarly, non-commercial research use.  
Recommended license: **Creative Commons Attribution 4.0 International (CC BY 4.0)**, subject to ethical restrictions described above.

---

## Citation
If using this dataset, please cite the associated article.  
If referencing the dataset repository, cite as:

Toktarbekova, K., Kalykbayeva, A., Stelmakh, S., Autayeva, A., Paylozyan, Zh., & Tyulyupergeneva, R.  
*Dataset for “Using active learning methods to develop social and pedagogical competence in future special educators”*. GitHub repository.

---

## Correspondence
For data access requests and inquiries:

- **Autayeva Akbota** – akbota-n@mail.ru  
- **Tyulyupergeneva Raushan** – raushan.zh@list.ru
