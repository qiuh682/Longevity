# Longevity Science Research Tracker — Claude Code Prompts
# 长寿科学研究追踪器 — Claude Code 提示词

## Overview / 概览
- **Goal:** Build a comprehensive, up-to-date longevity research tracker with a deep technical review and curated intervention database
- **Type:** Multi-prompt (3 phases)
- **Domain:** Longevity science / biogerontology research synthesis
- **Audience:** Researcher-level, deep technical depth
- **Time Frame:** 2023–2025 breakthroughs (with foundational context)

## Handoff Method / 交接方式
- File-based: Each phase outputs files that feed into the next
- Phase 1 → `research_notes/` folder of raw findings
- Phase 2 → `longevity_interventions_database.csv`
- Phase 3 → `longevity_research_review.md` (final report)

---

## Prompt 1: Research & Data Collection

### Context
You are a biogerontology research analyst building a comprehensive knowledge base on longevity science breakthroughs from 2023–2025. Your audience is a researcher who needs technically rigorous, citation-rich content. You will conduct extensive web searches to gather the latest findings, clinical trial data, and company pipeline information.

### Instructions

**Step 1: Search systematically across the 12 hallmarks of aging.** For each hallmark, search for recent breakthroughs (2023–2025):

1. Genomic instability
2. Telomere attrition
3. Epigenetic alterations
4. Loss of proteostasis
5. Disabled macroautophagy
6. Deregulated nutrient-sensing
7. Mitochondrial dysfunction
8. Cellular senescence
9. Stem cell exhaustion
10. Altered intercellular communication
11. Chronic inflammation (inflammaging)
12. Dysbiosis

For each hallmark, search using queries like:
- `[hallmark name] aging breakthrough 2024 2025`
- `[hallmark name] longevity intervention clinical trial`
- `[hallmark name] anti-aging drug development`

**Step 2: Search for specific compounds and interventions.** Cover at minimum:

- **Senolytics:** Dasatinib + Quercetin (D+Q), Fisetin, Navitoclax (ABT-263), UBX1325, Unity Biotechnology pipeline
- **mTOR inhibitors:** Rapamycin/Sirolimus, Everolimus, RTB101 (resTORbio/Antos)
- **NAD+ precursors:** NMN, NR (Nicotinamide Riboside), CD38 inhibitors
- **Metformin:** TAME trial, MILES trial results
- **Epigenetic reprogramming:** Yamanaka factors (OSKM/OSK), partial reprogramming, Turn Bio, Altos Labs, Life Biosciences, Retro Biosciences
- **GLP-1 agonists:** Semaglutide, Tirzepatide — emerging longevity/aging data
- **Spermidine, alpha-ketoglutarate, taurine, glycine+NAC (GlyNAC)**
- **Gene therapies:** Telomerase (TERT), Follistatin, Klotho, SIRT6 overexpression
- **Plasma exchange / young blood factors:** Alkahest, Elevian (GDF11)
- **Autophagy activators:** Spermidine, Trehalose, TFEB activators
- **Mitochondrial therapies:** Urolithin A (Amazentis/Timeline), SS-31 (Elamipretide), mitochondrial transplantation
- **Inflammaging targets:** IL-6 inhibitors, TNF-alpha, cGAS-STING pathway modulators
- **Epigenetic clocks:** GrimAge, DunedinPACE, OmicAge — as endpoints/biomarkers

For each compound, search for:
- Mechanism of action
- Key preclinical results (with species, lifespan extension %, healthspan data)
- Clinical trial status (phase, NCT number, endpoints, results if available)
- Safety/adverse event profile
- Key publications (author, journal, year, DOI if possible)

**Step 3: Search for all companies active in longevity.** Include:

- **Well-funded startups:** Altos Labs, Calico (Google/Alphabet), Retro Biosciences, NewLimit, Turn Biotechnologies, Life Biosciences, Loyal (dog aging), Cellarity, Shift Bioscience, Rejuvenate Bio, Cambrian Biopharma, BioAge Labs, Rubedo Life Sciences, Oisín Biotechnologies, Senolytic Therapeutics, Dorian Therapeutics
- **Pharma with aging programs:** Novartis (rapamycin analogs), AbbVie (Calico partner), Unity Biotechnology, resTORbio/Antos (acquired), Amazentis/Nestlé (Urolithin A), Alkahest/Grifols
- **Diagnostics/Biomarkers:** TruDiagnostic, Elysium Health, InsideTracker, GlycanAge, Tally Health (David Sinclair)
- **AI-driven longevity:** Insilico Medicine, Deep Longevity, Gero AI

For each company, search for:
- Founding date, funding raised, key investors
- Core technology platform / approach
- Pipeline compounds and development stage
- Key publications or data releases (2023–2025)
- Partnerships and collaborations

**Step 4: Search for clinical trial data specifically.**
- Search ClinicalTrials.gov via web for: `longevity aging clinical trial 2024 2025`
- Search for: `senolytic clinical trial results`, `rapamycin aging trial`, `NAD clinical trial`, `metformin TAME trial update`, `epigenetic reprogramming human trial`
- Capture: NCT number, phase, sponsor, enrollment, primary endpoints, status, any published results

**Step 5: Search for landmark review papers and meta-analyses.**
- `hallmarks of aging 2023 update Lopez-Otin`
- `longevity interventions systematic review 2024`
- `anti-aging clinical trials review`
- `epigenetic clock aging biomarker review`
- `senolytic therapy review 2024 2025`

**Step 6: Organize all findings into structured notes.**

Create a folder `research_notes/` with the following files:
- `hallmarks_findings.md` — findings organized by each of the 12 hallmarks
- `compounds_data.md` — each compound with MOA, preclinical, clinical, safety, citations
- `companies_landscape.md` — each company with profile, pipeline, funding, data
- `clinical_trials.md` — table of all relevant trials with NCT#, phase, status, results
- `key_publications.md` — annotated bibliography of the most important papers
- `biomarkers_clocks.md` — epigenetic clocks, aging biomarkers, validation data

### Expected Output
A `research_notes/` folder containing 6 detailed markdown files with comprehensive, citation-rich research data. Each file should contain extensive detail — err on the side of capturing more rather than less. Include URLs, DOIs, and full citation info wherever possible.

### Quality Criteria
- [ ] All 12 hallmarks covered with recent findings
- [ ] At minimum 20+ compounds/interventions documented
- [ ] At minimum 30+ companies profiled
- [ ] At minimum 20+ clinical trials catalogued
- [ ] All claims have citations with year and source
- [ ] Data is from 2023–2025 unless foundational context requires earlier references

### Handoff
- Output: `research_notes/` folder (6 files)
- Next prompt input: Phase 2 reads all files from `research_notes/`

---

## Prompt 2: Database / CSV Construction

### Context
You are building a curated longevity interventions database from research notes previously collected. You have a `research_notes/` folder containing 6 detailed markdown files covering hallmarks of aging, compounds, companies, clinical trials, publications, and biomarkers. Your task is to structure this into comprehensive, well-organized CSV files suitable for researcher use and downstream analysis.

### Instructions

**Step 1: Read all files in `research_notes/` to load context.**

Read each file thoroughly:
- `research_notes/hallmarks_findings.md`
- `research_notes/compounds_data.md`
- `research_notes/companies_landscape.md`
- `research_notes/clinical_trials.md`
- `research_notes/key_publications.md`
- `research_notes/biomarkers_clocks.md`

**Step 2: Create `interventions_database.csv`**

Columns:
```
Intervention_Name, Category, Subcategory, Mechanism_of_Action, Target_Hallmark(s), Preclinical_Evidence_Summary, Lifespan_Extension_Pct, Species_Tested, Clinical_Trial_Phase, NCT_Number, Clinical_Endpoints, Clinical_Results_Summary, Safety_Profile, Key_Publication, Publication_Year, DOI_or_URL, Evidence_Grade, Notes
```

Evidence_Grade scale:
- **A** — Strong clinical evidence (Phase 2/3 results, human RCT data)
- **B** — Moderate clinical evidence (Phase 1, pilot human studies)
- **C** — Strong preclinical evidence (multiple species, robust lifespan extension)
- **D** — Early preclinical (single species or in vitro only)
- **E** — Theoretical / mechanism-based only

Populate with ALL interventions found in research notes. Each compound/intervention gets its own row. If a compound targets multiple hallmarks, list them semicolon-separated.

**Step 3: Create `companies_database.csv`**

Columns:
```
Company_Name, Founded, Headquarters, Total_Funding_USD, Key_Investors, Core_Technology, Approach_Category, Pipeline_Compounds, Lead_Program_Stage, Key_Partnerships, Notable_Publications, Website, Last_Updated, Notes
```

Approach_Category options: Senolytics, Epigenetic Reprogramming, NAD+ Biology, mTOR Modulation, Gene Therapy, Plasma/Parabiosis, AI Drug Discovery, Diagnostics/Biomarkers, Multi-target, Other

**Step 4: Create `clinical_trials_database.csv`**

Columns:
```
NCT_Number, Trial_Title, Sponsor, Phase, Status, Intervention, Condition_Indication, Target_Population, Enrollment, Primary_Endpoint, Secondary_Endpoints, Start_Date, Estimated_Completion, Results_Available, Key_Findings, Publication_Reference, URL
```

**Step 5: Create `publications_database.csv`**

Columns:
```
First_Author, Title, Journal, Year, DOI_or_URL, Study_Type, Topic_Category, Key_Findings_Summary, Impact_Factor_Approx, Citation_Count_Approx, Relevance_Notes
```

Study_Type options: Review, Meta-analysis, RCT, Observational, Preclinical_Animal, Preclinical_InVitro, Commentary, Preprint

**Step 6: Create `biomarkers_database.csv`**

Columns:
```
Biomarker_Name, Type, Developer, Measurement_Method, Validated_In_Humans, Correlation_With_Mortality, Sensitivity_To_Interventions, Commercial_Availability, Cost_Approx, Key_Publication, Year, Notes
```

**Step 7: Validate and cross-reference.**
- Ensure every compound in `interventions_database.csv` that has a trial is also in `clinical_trials_database.csv`
- Ensure every company in `companies_database.csv` has its compounds represented in `interventions_database.csv`
- Ensure key publications are consistently cited across files
- Check for missing data and mark fields as "Unknown" or "Not reported" rather than leaving blank

**Step 8: Create `README_database.md`**

Write a brief README explaining:
- What each CSV contains
- Column definitions
- Evidence grading methodology
- How to use the database
- Date of last update
- Known limitations

### Expected Output
```
longevity_database/
├── interventions_database.csv
├── companies_database.csv
├── clinical_trials_database.csv
├── publications_database.csv
├── biomarkers_database.csv
└── README_database.md
```

### Quality Criteria
- [ ] All CSVs properly formatted (no broken rows, consistent delimiters)
- [ ] At minimum 20+ rows in interventions_database.csv
- [ ] At minimum 30+ rows in companies_database.csv
- [ ] At minimum 20+ rows in clinical_trials_database.csv
- [ ] Cross-referencing validated
- [ ] No blank fields — use "Unknown" / "Not reported" / "N/A"
- [ ] README is complete and accurate

### Handoff
- Output: `longevity_database/` folder (5 CSVs + README)
- Next prompt input: Phase 3 reads `research_notes/` AND `longevity_database/` to write the full review

---

## Prompt 3: Deep Technical Review — Report Generation

### Context
You are writing a comprehensive, technically rigorous review of the longevity science landscape (2023–2025) targeted at researchers. You have two data sources:

1. `research_notes/` — 6 detailed markdown files with raw research findings
2. `longevity_database/` — 5 structured CSV files + README with curated data

Your task is to synthesize these into a publication-quality deep technical review document in markdown format (~30+ pages). Write in an authoritative academic tone appropriate for a researcher audience. Be precise, cite everything, and do not oversimplify.

### Instructions

**Step 1: Read all source materials.**

Read every file in:
- `research_notes/` (all 6 files)
- `longevity_database/` (all 5 CSVs + README)

**Step 2: Write the full review document with the following structure.**

Create `longevity_research_review.md` with this structure:

```
# The Longevity Science Landscape 2023–2025: A Comprehensive Technical Review

## Table of Contents

## 1. Executive Summary (~1 page)
- Key breakthroughs of 2023–2025
- State of the field summary
- Most promising near-term clinical opportunities
- Major funding and industry trends

## 2. Introduction (~2 pages)
- Historical context: from caloric restriction to hallmarks of aging
- The 2023 updated hallmarks framework (López-Otín et al.)
- Shift from lifespan to healthspan focus
- Regulatory landscape evolution (FDA aging as indication discussions)
- Scope and methodology of this review

## 3. The Hallmarks of Aging: Recent Advances (~8-10 pages)
For EACH of the 12 hallmarks, write a subsection covering:
- Mechanistic overview (brief, assume researcher knowledge)
- Key breakthroughs 2023–2025
- Therapeutic targets identified
- Cross-talk with other hallmarks
- Open questions and controversies

### 3.1 Genomic Instability
### 3.2 Telomere Attrition
### 3.3 Epigenetic Alterations
### 3.4 Loss of Proteostasis
### 3.5 Disabled Macroautophagy
### 3.6 Deregulated Nutrient-Sensing
### 3.7 Mitochondrial Dysfunction
### 3.8 Cellular Senescence
### 3.9 Stem Cell Exhaustion
### 3.10 Altered Intercellular Communication
### 3.11 Chronic Inflammation (Inflammaging)
### 3.12 Dysbiosis

## 4. Pharmacological Interventions: Evidence Review (~6-8 pages)
Organize by intervention class:

### 4.1 Senolytics and Senomorphics
- D+Q, Fisetin, Navitoclax, UBX1325
- Clinical trial results and ongoing studies
- Safety concerns and therapeutic windows

### 4.2 mTOR Pathway Modulators
- Rapamycin and rapalogs
- Dose-response relationships
- PEARL trial, AgelessRx studies, other clinical data

### 4.3 NAD+ Metabolism
- NMN, NR, CD38 inhibition
- Clinical trial data (dosing, bioavailability, efficacy)
- Controversies (cancer concern debate)

### 4.4 Metformin
- TAME trial update
- Epidemiological evidence
- Mechanisms beyond glucose control

### 4.5 Epigenetic Reprogramming
- Yamanaka factor approaches (OSK, OSKM)
- In vivo partial reprogramming results
- Safety and tumorigenesis risk
- Chemical reprogramming alternatives

### 4.6 GLP-1 Receptor Agonists
- Emerging aging/longevity data
- MACE reduction, organ protection, potential geroprotective effects
- Mechanistic hypotheses

### 4.7 Mitochondrial-Targeted Therapies
- Urolithin A, SS-31/Elamipretide
- Clinical evidence for mitochondrial function restoration

### 4.8 Emerging and Novel Interventions
- Taurine, GlyNAC, Spermidine, Alpha-ketoglutarate
- Gene therapies (TERT, Klotho, Follistatin, SIRT6)
- Plasma exchange and young blood factors
- Autophagy modulators

### 4.9 Combination and Synergistic Approaches
- Rationale for polypharmacy in aging
- Notable combination studies

## 5. Biomarkers and Aging Clocks (~3-4 pages)
### 5.1 Epigenetic Clocks (Horvath, Hannum, GrimAge, DunedinPACE)
### 5.2 Proteomic and Metabolomic Clocks
### 5.3 Composite Biomarker Panels
### 5.4 Clinical Utility and Validation Status
### 5.5 Use as Clinical Trial Endpoints

## 6. Industry Landscape (~4-5 pages)
### 6.1 Funding Trends and Investment Analysis
### 6.2 Major Players: Profiles and Pipeline Analysis
  - Altos Labs, Calico, Retro Biosciences, NewLimit, etc.
### 6.3 Big Pharma Entry and Partnerships
### 6.4 AI and Computational Approaches
  - Insilico Medicine, Deep Longevity, Gero AI
### 6.5 Diagnostics and Consumer-Facing Companies
### 6.6 Regulatory Developments and FDA Engagement

## 7. Clinical Trial Landscape (~3-4 pages)
### 7.1 Overview of Active and Completed Trials
### 7.2 Key Results from 2023–2025
### 7.3 Trial Design Challenges in Aging Research
### 7.4 Emerging Endpoints and Surrogate Markers
### 7.5 Notable Failures and Lessons Learned

## 8. Discussion (~2-3 pages)
### 8.1 Most Promising Near-Term Opportunities
### 8.2 Translational Gaps and Challenges
### 8.3 Safety and Ethical Considerations
### 8.4 The Healthspan vs. Lifespan Debate
### 8.5 Convergence of AI and Longevity Science

## 9. Future Directions (~1-2 pages)
### 9.1 Predicted Breakthroughs 2025–2028
### 9.2 Technologies to Watch
### 9.3 Key Unanswered Questions

## 10. Conclusion (~0.5 page)

## 11. References
- Full citation list, numbered, formatted as:
  [N] Author(s). Title. Journal. Year;Volume(Issue):Pages. DOI/URL
- Aim for 100+ references minimum

## Appendix A: Intervention Evidence Summary Table
(Reproduce key data from interventions_database.csv in markdown table format)

## Appendix B: Company Pipeline Summary Table
(Reproduce key data from companies_database.csv in markdown table format)

## Appendix C: Active Clinical Trials Table
(Reproduce key data from clinical_trials_database.csv in markdown table format)
```

**Step 3: Writing Guidelines**

Follow these rules strictly:

1. **Tone:** Authoritative, precise, academic. Write as if for a top-tier review journal (Nature Reviews Drug Discovery, Cell, Ageing Research Reviews).
2. **Citations:** Cite EVERY factual claim with a numbered reference [N]. Do not make uncited assertions about data or findings.
3. **Data precision:** Include specific numbers — lifespan extension percentages, p-values, hazard ratios, confidence intervals, sample sizes, doses — wherever available from your source materials.
4. **Balance:** Present evidence fairly. Note conflicting results, failed trials, and controversies alongside positive findings.
5. **Figures/Tables description:** Where a figure or table would be informative, include a markdown table or describe what a figure would show (e.g., "Figure 1: Timeline of key longevity clinical trials 2023–2025").
6. **Cross-referencing:** Reference the appendix tables where relevant (e.g., "see Appendix A for full evidence summary").
7. **Length:** Target 30–40 pages of dense content. Each major section should be thorough, not superficial.
8. **Recency priority:** Lead with 2024–2025 findings, contextualize with 2023 and earlier landmark results.

**Step 4: Quality check.**

After writing, review the document for:
- Completeness (all sections filled with substantive content)
- Citation consistency (all references numbered and listed)
- Cross-referencing accuracy (appendix tables match text claims)
- No hallmark left underrepresented
- Technical accuracy (mechanisms, trial phases, compound names correct)

### Expected Output
```
longevity_research_review.md  (~30-40 pages, 100+ references, 3 appendix tables)
```

### Quality Criteria
- [ ] 30+ pages of substantive content
- [ ] All 12 hallmarks covered in dedicated subsections
- [ ] 20+ compounds/interventions analyzed with evidence
- [ ] 30+ companies profiled
- [ ] 100+ numbered references with full citations
- [ ] 3 appendix tables populated from CSV data
- [ ] Academic tone consistent throughout
- [ ] Balanced treatment of evidence (including negative/null results)
- [ ] No uncited factual claims

---

## Usage Notes / 使用说明

### Execution Order
Run prompts sequentially:
1. **Prompt 1** → generates `research_notes/` (expect 30–60 min of searching)
2. **Prompt 2** → generates `longevity_database/` (reads from Phase 1 output)
3. **Prompt 3** → generates `longevity_research_review.md` (reads from Phase 1 + 2 output)

### Tips for Best Results
- Run each prompt in a fresh Claude Code session to maximize context window
- For Prompt 1, allow Claude Code to make many web search calls — this is the data-gathering phase
- For Prompt 2, verify CSV outputs open correctly in your spreadsheet tool
- For Prompt 3, if the output feels incomplete in any section, you can re-run with a targeted follow-up like: "Expand section 4.5 on epigenetic reprogramming with more detail from the research notes"
- After all 3 phases, do a final pass asking Claude Code: "Review the report for any missing citations, inconsistencies between the CSV data and report text, or sections that need more depth"

### Updating the Tracker
To refresh the database quarterly, re-run Prompt 1 with updated date ranges, then re-run Prompts 2 and 3. The structure is designed to be repeatable.

### Customization
- To narrow scope: edit the compound and company lists in Prompt 1
- To change output format: modify Prompt 2 for XLSX instead of CSV, or Prompt 3 for .docx
- To add a domain: add a new search block in Prompt 1 Step 2 (e.g., "Longevity in veterinary medicine")
