# Longevity Research Database - README

## Overview

This database is a curated, structured collection of longevity science data covering pharmacological interventions, companies, clinical trials, publications, and aging biomarkers. It is designed for researchers, clinicians, and analysts who need a consolidated reference for the longevity and biogerontology field with a focus on breakthroughs from 2023 through 2025.

The database comprises five CSV files, each covering a distinct domain of longevity research. All data is sourced from peer-reviewed publications, clinical trial registries (ClinicalTrials.gov), company disclosures, and conference presentations. Fields that could not be confirmed are marked "Unknown" or "Not reported" rather than left blank.

---

## File Descriptions

### 1. interventions_database.csv

A comprehensive catalog of pharmacological and non-pharmacological longevity interventions, including senolytics, mTOR modulators, NAD+ precursors, epigenetic reprogramming, GLP-1 agonists, mitochondrial therapies, gene therapies, and emerging compounds.

**Columns:**

| Column | Definition |
|--------|-----------|
| `Intervention_Name` | Common name of the compound or intervention |
| `Category` | Broad intervention class (e.g., Senolytic, mTOR Modulator, NAD+ Precursor) |
| `Subcategory` | More specific classification within the category |
| `Mechanism_of_Action` | Brief description of how the intervention acts on aging biology |
| `Target_Hallmark(s)` | Which of the 12 hallmarks of aging are targeted; semicolon-separated if multiple |
| `Preclinical_Evidence_Summary` | Summary of animal model and in vitro data |
| `Lifespan_Extension_Pct` | Reported lifespan extension in preclinical models (percentage), or "N/A" |
| `Species_Tested` | Animal species used in preclinical studies (e.g., mouse, C. elegans, Drosophila) |
| `Clinical_Trial_Phase` | Highest clinical trial phase reached (Phase 1, 2, 3, or "Preclinical") |
| `NCT_Number` | ClinicalTrials.gov identifier, or "N/A" if no registered trial |
| `Clinical_Endpoints` | Primary endpoints used in clinical trials |
| `Clinical_Results_Summary` | Key findings from clinical studies, or "Not yet reported" |
| `Safety_Profile` | Known adverse effects and safety considerations |
| `Key_Publication` | Primary reference (Author, Journal, Year) |
| `Publication_Year` | Year of key publication |
| `DOI_or_URL` | Digital Object Identifier or URL for the key publication |
| `Evidence_Grade` | Evidence strength grade (A through E; see methodology below) |
| `Notes` | Additional context, caveats, or cross-references |

---

### 2. companies_database.csv

Profiles of companies active in the longevity and aging research space, including well-funded startups, pharmaceutical companies with aging programs, diagnostics companies, and AI-driven longevity platforms.

**Columns:**

| Column | Definition |
|--------|-----------|
| `Company_Name` | Official company name |
| `Founded` | Year the company was founded |
| `Headquarters` | City and country of primary headquarters |
| `Total_Funding_USD` | Total known funding raised in US dollars |
| `Key_Investors` | Major investors and funding sources |
| `Core_Technology` | Description of the company's primary technology platform |
| `Approach_Category` | Classification of the company's approach (e.g., Senolytics, Epigenetic Reprogramming, NAD+ Biology, mTOR Modulation, Gene Therapy, Plasma/Parabiosis, AI Drug Discovery, Diagnostics/Biomarkers, Multi-target, Other) |
| `Pipeline_Compounds` | Key compounds or products in development |
| `Lead_Program_Stage` | Development stage of the most advanced program |
| `Key_Partnerships` | Notable collaborations and partnerships |
| `Notable_Publications` | Key publications from the company or its scientists |
| `Website` | Company website URL |
| `Last_Updated` | Date the entry was last verified |
| `Notes` | Additional context |

---

### 3. clinical_trials_database.csv

A catalog of clinical trials relevant to longevity, aging, and geroprotective interventions, drawn from ClinicalTrials.gov and published results.

**Columns:**

| Column | Definition |
|--------|-----------|
| `NCT_Number` | ClinicalTrials.gov registration number |
| `Trial_Title` | Official or descriptive trial title |
| `Sponsor` | Organization or principal investigator sponsoring the trial |
| `Phase` | Clinical trial phase (Phase 1, 2, 3, or Phase 1/2, etc.) |
| `Status` | Current trial status (Recruiting, Active, Completed, Terminated, etc.) |
| `Intervention` | Drug, compound, or procedure being tested, including dosing if known |
| `Condition_Indication` | Target condition or aging-related indication |
| `Target_Population` | Description of enrolled participants (age range, health status, sample size criteria) |
| `Enrollment` | Number of participants enrolled or targeted |
| `Primary_Endpoint` | Primary outcome measure |
| `Secondary_Endpoints` | Secondary outcome measures |
| `Start_Date` | Trial start date |
| `Estimated_Completion` | Estimated or actual completion date |
| `Results_Available` | Whether results have been published (Yes/No/Partial) |
| `Key_Findings` | Summary of findings if results are available |
| `Publication_Reference` | Citation for published results |
| `URL` | Link to ClinicalTrials.gov entry or publication |

---

### 4. publications_database.csv

An annotated bibliography of the most important peer-reviewed publications in longevity science, covering landmark reviews, clinical trial results, preclinical findings, and methodological advances.

**Columns:**

| Column | Definition |
|--------|-----------|
| `First_Author` | First author surname and initials |
| `Title` | Full publication title |
| `Journal` | Journal name |
| `Year` | Publication year |
| `DOI_or_URL` | Digital Object Identifier or URL |
| `Study_Type` | Classification of the study (Review, Meta-analysis, RCT, Observational, Preclinical_Animal, Preclinical_InVitro, Commentary, Preprint) |
| `Topic_Category` | Primary topic area (e.g., Senolytics, Epigenetic Clocks, mTOR, NAD+, Hallmarks of Aging) |
| `Key_Findings_Summary` | Brief summary of the main results or conclusions |
| `Impact_Factor_Approx` | Approximate journal impact factor at time of publication |
| `Citation_Count_Approx` | Approximate citation count (as of last database update) |
| `Relevance_Notes` | Why this publication is included and how it relates to the broader longevity field |

---

### 5. biomarkers_database.csv

A catalog of aging biomarkers and biological age clocks, including epigenetic clocks (1st, 2nd, and 3rd generation), proteomic clocks, glycomic biomarkers, AI-based aging predictors, and functional/clinical measures of aging.

**Columns:**

| Column | Definition |
|--------|-----------|
| `Biomarker_Name` | Name of the biomarker or aging clock |
| `Type` | Classification (e.g., Epigenetic 1st/2nd/3rd generation, Proteomic, Glycomic, AI/Wearable, AI/Multi-omic, Clinical/Functional, Single protein biomarker) |
| `Developer` | Original developer(s) and institutional affiliation |
| `Measurement_Method` | Technical description of how the biomarker is measured (sample type, platform, features used) |
| `Validated_In_Humans` | Whether the biomarker has been validated in human cohorts (Yes / Partially / No) |
| `Correlation_With_Mortality` | Strength of association with all-cause mortality (Very Strong / Strong / Moderate / Weak / Unknown). "Very Strong" indicates hazard ratios consistently above 1.07 per unit acceleration or equivalent, validated in multiple large cohorts. "Strong" indicates consistent association in at least two large cohorts. "Moderate" indicates statistically significant but weaker or less replicated associations. |
| `Sensitivity_To_Interventions` | How responsive the biomarker is to geroprotective interventions (Excellent / High / Moderate / Low / Unknown). Includes specific interventions shown to produce measurable changes where data is available. |
| `Commercial_Availability` | Whether the biomarker is commercially available and through which provider(s), or "Research only" / "No" |
| `Cost_Approx` | Approximate cost per test in US dollars |
| `Key_Publication` | Primary reference (Author, Title abbreviation, Journal, Year) |
| `Year` | Year the biomarker was introduced or first published |
| `Notes` | Additional context including strengths, limitations, and clinical trial usage |

---

## Evidence Grading Methodology

All interventions in `interventions_database.csv` are assigned an evidence grade on an A-through-E scale reflecting the strength and maturity of supporting evidence. This grading is also referenced in contextual notes across other files.

| Grade | Label | Criteria |
|-------|-------|----------|
| **A** | Strong clinical evidence | Phase 2 or Phase 3 randomized controlled trial (RCT) data available in humans. Statistically significant primary endpoints met. Results published in peer-reviewed journals. |
| **B** | Moderate clinical evidence | Phase 1 or pilot human studies completed. Preliminary human efficacy or biomarker data available. May include well-designed observational studies with large sample sizes. |
| **C** | Strong preclinical evidence | Robust preclinical data in multiple species (typically mice plus at least one additional model). Significant lifespan or healthspan extension demonstrated. Mechanism of action well-characterized. |
| **D** | Early preclinical evidence | Single-species preclinical data (usually mice only) or primarily in vitro evidence. Mechanism of action partially characterized. Limited replication across laboratories. |
| **E** | Theoretical or mechanism-based | Intervention is supported by theoretical rationale or mechanistic pathway data only. No significant preclinical lifespan data available. May include very early-stage compounds with target validation but no in vivo aging studies. |

**Grading notes:**
- Grades reflect the state of evidence as of February 2025.
- A single intervention may have different grades for different indications; the grade assigned reflects the longevity or aging-specific evidence, not evidence for other therapeutic areas.
- Negative or null trial results do not automatically lower the grade; they are noted in the `Clinical_Results_Summary` and `Notes` fields.
- Epidemiological data alone (without interventional studies) generally supports a maximum grade of B.

---

## Usage Guide

### Getting Started

1. **Open CSV files** in any spreadsheet application (Microsoft Excel, Google Sheets, LibreOffice Calc) or import into data analysis tools (Python/pandas, R).
2. **Use UTF-8 encoding** when opening files to ensure correct rendering of special characters in author names, journal titles, and compound names.
3. **Fields containing commas** are enclosed in double quotes per CSV standard. Most spreadsheet applications handle this automatically.

### Common Use Cases

- **Finding interventions by hallmark:** Filter `interventions_database.csv` by `Target_Hallmark(s)` to identify compounds targeting a specific aging mechanism.
- **Assessing clinical readiness:** Sort `interventions_database.csv` by `Evidence_Grade` (A is strongest) and `Clinical_Trial_Phase` to identify the most clinically advanced interventions.
- **Identifying biomarkers for a trial:** Use `biomarkers_database.csv` and filter by `Sensitivity_To_Interventions` (Excellent or High) and `Correlation_With_Mortality` (Strong or Very Strong) to select endpoint biomarkers.
- **Company landscape analysis:** Use `companies_database.csv` filtered by `Approach_Category` to map the competitive landscape for a specific therapeutic modality.
- **Cross-referencing trials and compounds:** Use `NCT_Number` as a linking key between `interventions_database.csv` and `clinical_trials_database.csv`.
- **Building a reading list:** Use `publications_database.csv` sorted by `Year` and filtered by `Topic_Category` for a curated bibliography on any sub-field.

### Cross-Referencing Between Files

The five CSV files are designed to be cross-referenced:

- Every compound in `interventions_database.csv` that has a registered clinical trial should have a corresponding entry in `clinical_trials_database.csv` (linked by `NCT_Number`).
- Every company in `companies_database.csv` should have its key pipeline compounds represented in `interventions_database.csv` (linked by compound or intervention name).
- Key publications cited in intervention, company, and biomarker entries should appear in `publications_database.csv` (linked by author/year or DOI).
- Biomarkers listed in `biomarkers_database.csv` that are used as clinical trial endpoints should be referenced in the corresponding `clinical_trials_database.csv` entries.

---

## Limitations

1. **Knowledge cutoff.** This database reflects information available through early 2025 (training data through May 2025). Clinical trial statuses, company funding amounts, pricing, and product availability may have changed since compilation.

2. **Pricing approximations.** All cost figures (`Cost_Approx`) are approximate and based on publicly available pricing at the time of compilation. Prices vary by provider, geography, insurance coverage, and volume. Fields marked with ranges (e.g., "$200-$500") indicate known variability across providers.

3. **Validation variability.** The `Validated_In_Humans` and `Correlation_With_Mortality` fields for biomarkers reflect the published literature. Validation rigor varies substantially between biomarkers: some (GrimAge, DunedinPACE) have been validated in multiple large prospective cohorts, while others have only proprietary or limited validation data.

4. **Evidence grading subjectivity.** While the A-through-E grading scale is defined by objective criteria, borderline cases require judgment. Grades represent the assessment of the database curators and may differ from other classification systems.

5. **Publication bias.** The database preferentially captures published positive results. Negative or null findings may be underrepresented, particularly for proprietary compounds where sponsors control data release.

6. **Commercial conflicts.** Several biomarker entries (TallyAge, Elysium Index, TruAge) are products from companies that also sell related supplements or services. This potential conflict of interest is noted in the `Notes` field but should be considered when evaluating claims.

7. **Population generalizability.** Many biomarkers were developed and validated primarily in European-ancestry populations. Performance in other ancestry groups may differ and is less well-characterized.

8. **Not a clinical recommendation.** This database is an informational research tool. It does not constitute medical advice, and no intervention should be undertaken based solely on the information contained here without consultation with qualified healthcare professionals.

9. **Incomplete cross-referencing.** While efforts have been made to maintain consistency across all five CSV files, some cross-references may be incomplete, particularly for newer entries added during database expansion.

---

## Last Updated

**February 2025**

Data sources: Peer-reviewed literature, ClinicalTrials.gov, company public disclosures, conference abstracts, and structured training data through May 2025. Items requiring live verification for the most current status are noted in individual entries.

---

*Longevity Research Database v1.0 -- Compiled as part of the Longevity Science Research Tracker project.*
