# Preauricular-Sinus-Survey-Data-
 This is a survey and analysis of preauricular sinus occurrence among 302 respondents across communities in Akwa Ibom State, Nigeria. Explores prevalence, demographics (age, sex, ethnicity), family history, and awareness of the condition using self-reported survey data collected May–June 2025
# Preauricular Sinus Prevalence Survey — Akwa Ibom State, Nigeria

## Overview

A preauricular sinus (also called an auricular pit or preauricular dimple) is a small, congenital pit or opening typically found just in front of the ear, near the junction of the tragus and the helix. It arises from incomplete fusion of the auricular hillocks during embryonic development of the outer ear. Most cases are asymptomatic and go unnoticed, but the sinus can occasionally become infected, discharge, or form a cyst, sometimes requiring medical or surgical attention.

This repository contains survey data and exploratory analysis examining the occurrence and characteristics of preauricular sinus among individuals across selected communities in **Akwa Ibom State, Nigeria**. The dataset was collected as part of a medical research project and is analyzed here to explore patterns in prevalence, demographics, family history, and awareness of the condition within the sampled population.

## Study Objective

To document the occurrence of preauricular sinus among residents of selected Akwa Ibom communities and describe how it varies by age, sex, ethnicity, location, and family history, while assessing general awareness of the condition among respondents.

## Study Area and Population

Data were collected from respondents across several Local Government Areas (LGAs) and communities in Akwa Ibom State, including Uyo, Etinan, Itu, Abak, Ikot Ekpene, Obot Akara, Ikot Enwang, Nsit Ibom, Onna, Etim Ekpo, Uruan, Ikot Abasi, Ibeno, Essien Udim, and Nsit Ubium, among others — spanning **191 distinct villages/communities** in total. The two dominant ethnic groups represented are **Ibibio** and **Annang**, the major indigenous groups of the state.

## Methodology

- **Design:** Cross-sectional survey based on self-reported responses.
- **Sample size:** 302 respondents.
- **Data collection period:** May – June 2025.
- **Data collection tool:** Structured questionnaire capturing demographic information and details related to preauricular pit presence, location, symptoms, and family history.
- **Sampling approach:** Convenience/community-based sampling across the listed LGAs (not a randomized population-representative sample).

### Variables collected

| Category | Variables |
|---|---|
| Demographics | Age group, sex, ethnic group, LGA/village, education level, occupation |
| Clinical | Presence of auricular pit/dimple, position of pit (left/right/both ears), age of awareness, presence of symptoms, ear symptom experienced |
| Family history | Family member with same symptoms, relationship to respondent, family history of ear deformity |
| Care-seeking | Any medical treatment received, type of treatment offered |
| Awareness | Whether the respondent was aware of the condition before the survey |

## Repository Structure

```
├── data/
│   └── PREAURICULAR_SINUS_SURVEY_DATA.xlsx   # Raw survey responses (302 records, 21 variables)
├── charts/
│   ├── age_distribution.png
│   ├── ethnicity_distribution.png
│   ├── sex_distribution.png
│   ├── position_of_pit.png
│   ├── family_history.png
│   ├── awareness_of_condition.png
│   └── village_lga_distribution.png
├── README.md
```

## Charts

The following charts, generated from the pivot tables and dashboard in the Excel file, visualize key patterns in the survey data.

**Age distribution of respondents with a preauricular pit**
![Age distribution](charts/age_distribution.png)

**Distribution by ethnicity (Ibibio vs. Annang)**
![Ethnicity distribution](charts/ethnicity_distribution.png)

**Distribution by sex**
![Sex distribution](charts/sex_distribution.png)

**Position of pit (left ear, right ear, both ears)**
![Position of pit](charts/position_of_pit.png)

**Family history of similar symptoms**
![Family history](charts/family_history.png)

**Awareness of the condition before the survey**
![Awareness of condition](charts/awareness_of_condition.png)

**Distribution by village/LGA**
![Village/LGA distribution](charts/village_lga_distribution.png)

*(Add/rename files above to match the exact charts exported from the Excel dashboard. Any chart not listed here can simply be added to the `charts/` folder and linked using the same `![Title](charts/filename.png)` format.)*

## Summary of Key Findings

Out of 302 respondents:

- **53 (≈17.5%)** reported having a preauricular pit/dimple; 248 reported not having one, and 1 response was unknown.
- **Sex:** 181 female and 121 male respondents.
- **Ethnicity:** 195 Ibibio and 107 Annang respondents.
- **Age:** The large majority of respondents (284) were aged 18–35, with smaller representation from the 36–60 (16) and 60+ (2) age brackets.
- **Education:** Most respondents (268) had attained tertiary education.
- **Laterality (among those with a pit):** Right ear (25), left ear (21), and both ears (8) were reported.
- **Family history:** Most respondents were unsure of any family history of similar symptoms (228 "unknown"), while smaller numbers reported affected siblings, other relatives, mothers, fathers, or grandparents.
- **Awareness:** Prior to the survey, 155 respondents were not aware of the condition, 72 were aware, and 75 were unsure.

*(Note: these figures reflect the surveyed sample only and should not be interpreted as population-level prevalence estimates — see Limitations below.)*

## Tools Used

- Microsoft Excel (data entry, pivot tables, initial dashboard)
- Python (pandas, matplotlib/seaborn) for data cleaning and exploratory analysis

## Limitations

- The sample was drawn via convenience sampling rather than random/population-based sampling, so findings should not be generalized to the broader population of Akwa Ibom State.
- Pit presence and symptom data were self-reported rather than clinically verified through physical examination.
- The age distribution skews heavily toward the 18–35 bracket, limiting insight into prevalence in older age groups.
- Some fields (e.g., village name spelling, family history) contain inconsistent entries or a high proportion of "Unknown" responses, which were addressed during data cleaning.

## How to Reproduce

1. Clone this repository.
2. Open `data/PREAURICULAR_SINUS_SURVEY_DATA.xlsx`.
3. Review the **PIVOT TABLE** and **DASHBOARD** sheets, which contain the summary tables and charts underlying the visuals in the `charts/` folder above.

## License / Attribution]
This project is open for reference and educational use. If you find it helpful, feel free to star ⭐ the repo and share it with your team.

