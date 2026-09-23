# Traumacare_Post-registration_learners

This repository contains the code, resources  and possibly anonymised data used for analysing paper-based questionnaires collected during the two multimodal trauma-focused anatomy sessions created and delivered at the *Human Anatomy Unit, University of Birmingham* for post-registration nurses and allied healthcare professionals enrolled on Trauma Care modules with the University Hospitals Birmingham NHS Trust and validated by Buckinghamshire New University visiting the University of Birmingham.

## Repository Structure
- **`notebook/`** – python notebook containing codes used for analysis and figure generation.  
- **`Data/`** – An anonymised dataset when approved on request will be uploaded here.
- **`Supplementary/`** – contains tables, content analsyis and final figures.    

## Teaching Design and Aim
The sessions included a thorax and limbs anatomy session and a neuroanatomy session, both delivered using a combination of donor specimens, digital anatomy platforms, radiological images, anatomical models, structured learning activities and clinically applied case-based discussion.
The evaluation focused on three main areas:
- Learner-reported anatomical knowledge before and after the teaching sessions.
- Perceived usefulness of the teaching resources used during the sessions.
- Learner-reported clinical applicability of the knowledge gained.

## Methods Summary
Quantitative analyses were conducted using `python` 3.11.8. Figures were generated using `matplotlib` 3.10.0, in addition to manually constructing a sunburst chart using Matplotlib wedge patches. Quantitative data were summarised descriptively using counts, percentages, medians and interquartile ranges. Likert-scale responses were treated as ordinal data. Mann–Whitney U tests were performed using  `scipy` 1.15.2 as an exploratory comparison of unmatched pre-session and post-session ordinal ratings. Rank-biserial correlation was calculated as an effect size, with positive values indicating higher post-session ratings. Holm-adjusted p-values were calculated manually in `python` as a sensitivity analysis to account for multiple comparisons across knowledge domains examined. 

Open-ended responses were analysed using a descriptive content analysis to explore learners’ overall perceptions of the trauma-focused anatomy session. Verbatim comments were retained throughout the analysis to preserve participants’ wording and to support transparency between the raw data, subthemes and final themes. Theme and subtheme frequencies were calculated descriptively to summarise the distribution of coded comments. 


## Ethical Statement
Only consented responses were included in the analysis. Donor specimens were used within the governance arrangements of the University of Birmingham Human Anatomy Unit and in accordance with institutional procedures for anatomy teaching. Institutional ethics was obtained from the University of Birmimgham (ERN_5382-Nov2025). 


## Citation
Once the Mauscript is accepted, the DOI or URL to the paper will be attached here.
Please cite:
