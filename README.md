# Regulatory and Engineering Challenges in AI-Based Medical Software Development in SMEs — Empirical Study

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://img.shields.io/badge/DOI-pending-blue.svg)]()

This repository contains the **research instruments and aggregated/anonymized response data** from an empirical study on the technical and regulatory challenges faced by Small and Medium-sized Enterprises (SMEs) in the development of Artificial Intelligence and Machine Learning Software as a Medical Device (AI/ML-SaMD).

The study is part of a Ph.D in Informatics Engineering at the **Centre for Informatics and Systems of the University of Coimbra (CISUC)**, Faculty of Sciences and Technology, University of Coimbra (FCTUC), Portugal.

## Study at a Glance

- **Design:** Mixed-methods (quantitative and qualitative) empirical study.
- **Instrument:** Anonymous online questionnaire deployed in LimeSurvey (multiple-choice, multi-selection, 4-point Likert-scale, and open-ended items). Estimated completion time: 30 minutes.
- **Sample:** 36 valid responses from professionals affiliated with organizations active in the development of medical software.
- **Geographic scope:** Organizations from 17 countries, targeting the European Union (EU) and/or the United States (US).
- **Ethics approval:** Ethics Committee for Research of the University of Coimbra (CEIUC), reference **CEIUC_R-23-02/2025**. Favourable ethical opinion issued within its remit.
- **Legal basis (GDPR):** Article 6(1)(a) — explicit consent of the participants. No special-category personal data (Article 9) were collected.

## Research Questions (RQs)

- **RQ1.** What are the main technical challenges encountered by organizations, particularly SMEs, in the development and validation of AI/ML-SaMD?
- **RQ2.** Which regulatory and organizational obstacles most strongly constrain the regulatory pathway of AI/ML-SaMD in SMEs targeting the EU and the US?
- **RQ3.** To what extent do current development methodologies and regulatory automation practices support compliance throughout the medical software lifecycle?
- **RQ4.** Which resources, good practices, and methodological adjustments are perceived by industry practitioners as most useful to overcome the identified challenges?

## Repository Structure

```
.
├── README.md                            # this file
├── LICENSE                              # CC BY 4.0
├── CITATION.cff                         # citation metadata
│
├── docs/                                # study instruments and ethics material
│   ├── participant-information.pdf
│   └── questionnaire.pdf
│
└── data/                                
    ├── README.md
    └── results-tables-and-figures.xlsx  # findings documentation (tables and figures)
```

## Reproducibility

The artifacts in this repository allow independent researchers to:

1. Inspect the **exact wording** of every question (`docs/questionnaire.pdf`) and the **Participant Information** (`docs/participant-information.pdf`) to assess instrument validity.
3. Re-analyze the aggregated responses (`data/results-tables-and-figures.xlsx`) using any tool of choice (Excel, Python/pandas, R, SPSS).
4. Replicate the questionnaire in other contexts (e.g., other jurisdictions, other regulated industries) under the terms of the CC BY 4.0 licence.

## How to Cite

If you use this dataset or the questionnaire, please cite the accompanying paper. 

Suggested citation (BibTeX):

```bibtex
@misc{batista2026aisamdchallenges,
  author       = {Batista, Stephanie and de Carvalho, Paulo and Bernardino, Jorge},
  title        = {Empirical Study for Software as a Medical Device Development: What Are the Main Regulatory and Engineering Challenges for SMEs?},
  year         = {2026},
  howpublished = {GitHub repository},
  url          = {https://github.com/stephanie-batista-CISUC/ai-samd-sme-challenges}
}
```

## License

- **Data, questionnaire, and documentation:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE). You are free to share and adapt, provided that appropriate credit is given.

## Data Protection and Ethics

- This study was reviewed and received a favourable opinion from the **Ethics Committee for Research of the University of Coimbra (CEIUC)**, reference **CEIUC_R-23-02/2025**.
- The **Centre for Informatics and Systems of the University of Coimbra (CISUC)** is the data controller.
- Participation was voluntary, anonymous, and confidential. Participants could withdraw at any time without justification.
- The legal basis for processing is the participant's explicit consent under **Article 6(1)(a) GDPR**. **No special-category data** (Article 9 GDPR) were collected.
- The dataset published here contains **only aggregated and anonymized responses**. No personal data, no information that could identify a participant or an organization is included.
- Data subjects may exercise their rights under the GDPR, or lodge a complaint with the Portuguese Data Protection Authority (CNPD, Rua de São Bento 148, 1200-821 Lisbon, geral@cnpd.pt), by contacting the principal investigator below.

## Acknowledgments

We thank all participants who contributed their time and expertise to this study, and the international forums and professional networks that supported participant recruitment.
