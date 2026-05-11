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
└── data/                                # findings documentation
    ├── METHODOLOGY.md
    ├── 01_background_companies.xlsx
    ├── 01_background_participants.xlsx
    ├── 02_regulatory_context.xlsx
    ├── 03_software_development.xlsx
    ├── 04_ai_implementation.xlsx
    ├── 05_challenges_prioritization.xlsx
    └── 06_good_practices.xlsx
```

## Data Description

Response data are organized into **six workbooks** that mirror the sections of the questionnaire:

| File | Section | Content |
|---|---|---|
| `01_background_companies.xlsx` | 1. Background — Companies | Company size, location(s), target market(s), medical software and AI activity. |
| `01_background_participants.xlsx` | 1. Background — Participants | Role, age range, years of professional experience in software engineering. |
| `02_regulatory_context.xlsx` | 2. Regulatory and Organizational Context | Knowledge of regulations/standards (ISO 13485, IEC 62304, IEC 82304, ISO 14971, IEC 81001-5-1, EU MDR, 21 CFR, FDA guidances, GDPR, HIPAA, EU AI Act, ISO/IEC 42001 and ISO/IEC 23894), perceived regulatory ambiguity, documentation burden, EU–US divergence, areas where guidance is most needed. |
| `03_software_development.xlsx` | 3. Development Processes | Software development methodology, agile-vs-regulatory tension, traceability-matrix components, regulatory automation, impact of certification on timelines/costs, impact on lifecycle. |
| `04_ai_implementation.xlsx` | 4. AI: Data, Bias, Generalization | Open-ended technical challenges, data availability and governance, subgroup performance evaluation frequency, bias-mitigation techniques, presence of a PCCP/ACP. |
| `05_challenges_prioritization.xlsx` | 5. Prioritization of Challenges | Most demanding software and AI lifecycle phases for compliance, regulatory ambiguity, documentation strategies, intensity of literature-derived challenges, proposed solutions. |
| `06_good_practices.xlsx` | 6. Support and Needs | Methodological adjustments needed for the next 12 months, good practices producing positive results, most useful resources. |

Each workbook contains one sheet per question, named after the question topic. Likert-scale items use the original 1–4 labels (e.g., `4 - High`, `2 - Disagree`). Multi-selection items use one column per option with `Yes`/`No` values. Open-ended items contain free-text answers, and all entries have been reviewed and anonymized. No organization name, product name, jurisdiction-revealing detail, or other identifier is retained.

A more detailed **codebook** is available in [`data/METHODOLOGY.md`](./data/METHODOLOGY.md), including the methodology, exact wording of each question, the corresponding scale, and the encoding conventions.

## Key Findings

High-level results:

- **94.3%** of respondents perceive the documentation burden as a moderate-to-high challenge.
- **86.1%** identify the reconciliation of agile methodologies with regulatory requirements as challenging.
- **91.7%** consider the regulatory differences between the EU and the US to be a significant strategic obstacle.
- **94.1%** report basic or no knowledge of AI-specific standards (ISO/IEC 42001, ISO/IEC 23894).
- **88.9%** have no formally defined Predetermined Change Control Plan (PCCP) or Algorithm Change Plan (ACP).
- **80.6%** of organizations report no form of regulatory automation.
- The most demanded resources are **practical regulatory guides (75.0%)** and **compliance checklists (69.4%)**.

## Reproducibility

The artifacts in this repository allow independent researchers to:

1. Inspect the **exact wording** of every question (`docs/questionnaire.pdf`) and the **Participant Information** (`docs/participant-information.pdf`) to assess instrument validity.
3. Re-analyze the aggregated responses (`data/*.xlsx`) using any tool of choice (Excel, Python/pandas, R, SPSS).
4. Replicate the questionnaire in other contexts (e.g., other jurisdictions, other regulated industries) under the terms of the CC BY 4.0 licence.

## How to Cite

If you use this dataset or the questionnaire, please cite the accompanying paper. A `CITATION.cff` file is provided so that GitHub displays a "Cite this repository" button automatically.

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
