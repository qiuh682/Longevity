# Biomarkers and Aging Clocks: Comprehensive Catalog
# Phase 1 Output | Epigenetic Clocks, Proteomic Clocks, and Aging Biomarkers

> **Data Source Note:** This document is compiled from training knowledge through May 2025. All details are sourced from peer-reviewed publications, commercial product disclosures, and conference presentations. Items marked [VERIFY] would benefit from live confirmation for the most current pricing, availability, or validation data.

---

## PART 1: EPIGENETIC (DNA METHYLATION) CLOCKS

---

### 1.1 Horvath Clock (Multi-Tissue Clock)

| Field | Detail |
|-------|--------|
| **Name** | Horvath Multi-Tissue DNAm Age Clock |
| **Type** | First-generation epigenetic clock (chronological age predictor) |
| **Developer/Originator** | Steve Horvath, University of California Los Angeles (UCLA) |
| **Year Introduced** | 2013 |
| **Measurement Method** | DNA methylation levels at 353 CpG sites, measured via Illumina 450K or EPIC array from blood, saliva, or tissue samples. Uses an elastic net regression model trained on 8,000 samples across 51 cell types and tissues. |
| **What It Measures** | Predicts chronological age from methylation patterns. The deviation between DNAm age and chronological age is called "epigenetic age acceleration" (EAA). Positive EAA = biologically older; negative EAA = biologically younger. |
| **Validation Status** | Extensively validated in >100 independent cohorts. Median absolute error ~3.6 years across tissues. The most widely used and cited epigenetic clock. |
| **Correlation with Mortality** | Moderate. EAA of +5 years associated with ~15-20% increased mortality risk after adjusting for traditional risk factors. However, later clocks (GrimAge, PhenoAge) are stronger mortality predictors. |
| **Sensitivity to Interventions** | Moderate. Shown to respond to: caloric restriction (reduced in some studies), growth hormone + DHEA + metformin (TRIIM trial, -2.5 years), lifestyle interventions (Fitzgerald et al. 2021, -3.23 years), some supplements (CaAKG). Less sensitive than DunedinPACE to short-term interventions. |
| **Commercial Availability** | Available through multiple providers: TruDiagnostic (TruAge), Elysium Health (Index), myDNAge, Chronomics, GlycanAge (different platform). Also available through academic labs. |
| **Cost (approx.)** | $200-$500 per test (consumer); varies by provider |
| **Key Publications** | Horvath S. DNA methylation age of human tissues and cell types. *Genome Biol*. 2013;14(10):R115. DOI: 10.1186/gb-2013-14-10-r115 |
| **Strengths** | Multi-tissue applicability (works across nearly all tissue types and cell types); massive validation base; most-cited clock; well-understood properties |
| **Limitations** | Trained to predict chronological age, not biological aging per se; weaker predictor of mortality than second-generation clocks; less sensitive to interventions; does not capture all aspects of biological aging; some CpGs are in regions of uncertain biological significance |

---

### 1.2 Hannum Clock

| Field | Detail |
|-------|--------|
| **Name** | Hannum Blood-Based DNAm Age Clock |
| **Type** | First-generation epigenetic clock (chronological age predictor) |
| **Developer/Originator** | Gregory Hannum, University of California San Diego (UCSD) |
| **Year Introduced** | 2013 |
| **Measurement Method** | DNA methylation levels at 71 CpG sites from whole blood, measured via Illumina 450K or EPIC array. Elastic net regression trained on 656 blood samples. |
| **What It Measures** | Predicts chronological age from blood DNA methylation. Similar to Horvath clock but blood-specific and uses fewer CpGs. |
| **Validation Status** | Well-validated in blood samples across multiple cohorts. Median absolute error ~4.9 years in validation sets. |
| **Correlation with Mortality** | Similar to Horvath clock. Moderate correlation with all-cause mortality. Outperformed by GrimAge and PhenoAge. |
| **Sensitivity to Interventions** | Similar to Horvath clock. Responds to some lifestyle and pharmacological interventions. |
| **Commercial Availability** | Included in most commercial epigenetic testing panels (TruDiagnostic, Elysium, myDNAge) |
| **Cost (approx.)** | Typically included in panels costing $200-$500 |
| **Key Publications** | Hannum G, et al. Genome-wide methylation profiles reveal quantitative views of human aging rates. *Mol Cell*. 2013;49(2):359-367. DOI: 10.1016/j.molcel.2012.10.016 |
| **Strengths** | Simpler model (71 CpGs); blood-specific optimization; well-validated |
| **Limitations** | Blood-specific only (does not work well on other tissues); first-generation clock with limitations similar to Horvath; weaker mortality prediction than second-generation clocks |

---

### 1.3 PhenoAge (Levine Clock)

| Field | Detail |
|-------|--------|
| **Name** | DNAm PhenoAge |
| **Type** | Second-generation epigenetic clock (trained on phenotypic/mortality data) |
| **Developer/Originator** | Morgan Levine (Yale, now Altos Labs), Steve Horvath (UCLA) |
| **Year Introduced** | 2018 |
| **Measurement Method** | Two-step process: (1) A composite "phenotypic age" is calculated from 9 clinical biomarkers (albumin, creatinine, glucose, CRP, lymphocyte %, mean cell volume, RDW, alkaline phosphatase, WBC count) + chronological age. (2) A DNA methylation predictor of this phenotypic age is then built using 513 CpG sites via elastic net regression. Blood-based, Illumina 450K/EPIC. |
| **What It Measures** | Estimates biological age as reflected by clinical biomarkers associated with mortality risk. Captures physiological dysregulation rather than just chronological age. |
| **Validation Status** | Validated in multiple large cohorts (InCHIANTI, WHI, NHANES). Significantly better predictor of mortality, morbidity, and physiological decline than first-generation clocks. |
| **Correlation with Mortality** | Strong. PhenoAge acceleration significantly predicts all-cause mortality (HR ~1.04-1.05 per year of acceleration in many cohorts), cardiovascular disease, cancer, and multi-morbidity. Substantially better than Horvath or Hannum clocks. |
| **Sensitivity to Interventions** | Moderate to good. Has shown response to caloric restriction, weight loss interventions, and some pharmacological agents. The clinical biomarker basis makes it more responsive to metabolic and physiological changes. |
| **Commercial Availability** | Available through TruDiagnostic, Elysium, and other providers. Also calculable from clinical lab panels (the phenotypic age component). |
| **Cost (approx.)** | $200-$500 (as part of epigenetic testing panel) |
| **Key Publications** | Levine ME, et al. An epigenetic biomarker of aging for lifespan and healthspan. *Aging (Albany NY)*. 2018;10(4):573-591. DOI: 10.18632/aging.101414 |
| **Strengths** | Trained on mortality-relevant phenotypic data; stronger mortality prediction than first-generation clocks; captures physiological dysregulation; the phenotypic age component can be calculated from standard blood tests |
| **Limitations** | Blood-based only; the CpG predictor is a surrogate for clinical biomarkers, introducing an extra layer of approximation; some of the clinical biomarkers used can be affected by acute illness, potentially introducing noise |

---

### 1.4 GrimAge (and GrimAge2)

| Field | Detail |
|-------|--------|
| **Name** | DNAm GrimAge / GrimAge2 |
| **Type** | Second-generation epigenetic clock (trained on mortality data) |
| **Developer/Originator** | Ake Lu, Steve Horvath (UCLA) |
| **Year Introduced** | 2019 (GrimAge); 2022 (GrimAge2) |
| **Measurement Method** | Uses DNA methylation surrogates for 7 plasma proteins (adrenomedullin, beta-2 microglobulin, cystatin C, GDF-15, leptin, PAI-1, TIMP-1) and smoking pack-years, plus chronological age. 1,030 CpG sites in total. Measured from blood via Illumina EPIC array. Cox proportional hazards model trained to predict time to death. GrimAge2 is an updated version with improved accuracy. |
| **What It Measures** | Predicts time to death (mortality risk). The methylation surrogates for plasma proteins capture systemic biological aging processes (inflammation, renal function, metabolic health, vascular function). |
| **Validation Status** | Extensively validated as the strongest epigenetic predictor of mortality and age-related disease. Validated in Framingham Heart Study, Women's Health Initiative, InCHIANTI, and multiple other cohorts. GrimAge2 further improved on the original. |
| **Correlation with Mortality** | Very strong. GrimAge acceleration is the strongest epigenetic predictor of all-cause mortality among all published clocks. Also strongly predicts coronary heart disease, cancer, type 2 diabetes, COPD, and multi-morbidity. HR ~1.07-1.10 per year of GrimAge acceleration. |
| **Sensitivity to Interventions** | Good. Has shown response to: caloric restriction (CALERIE trial), weight loss, exercise, smoking cessation. Being used as a primary endpoint in the PEARL rapamycin trial and other longevity trials. Considered one of the best clock endpoints for clinical trials. |
| **Commercial Availability** | Available through TruDiagnostic (TruAge Complete panel includes GrimAge2), and select academic labs. |
| **Cost (approx.)** | $250-$500 (as part of comprehensive panel) |
| **Key Publications** | Lu AT, et al. DNA methylation GrimAge strongly predicts lifespan and healthspan. *Aging (Albany NY)*. 2019;11(2):303-327. DOI: 10.18632/aging.101684; Lu AT, et al. DNA methylation GrimAge version 2. *Aging (Albany NY)*. 2022;14(23):9484-9549. DOI: 10.18632/aging.204434 |
| **Strengths** | Strongest mortality predictor among epigenetic clocks; captures smoking exposure; includes methylation surrogates for clinically relevant proteins; good sensitivity to interventions; selected as primary endpoint for major aging trials |
| **Limitations** | Blood-based only; relies on surrogates for proteins rather than direct protein measurement; smoking component may dominate in some populations; more complex model than first-generation clocks; requires Illumina EPIC array data |

---

### 1.5 DunedinPACE (Pace of Aging)

| Field | Detail |
|-------|--------|
| **Name** | DunedinPACE (Pace of Aging Calculated from the Epigenome) |
| **Type** | Third-generation epigenetic clock (pace-of-aging measure, not a biological age estimate) |
| **Developer/Originator** | Daniel Belsky (Columbia University), Avshalom Caspi, Terrie Moffitt (Duke University) |
| **Year Introduced** | 2022 |
| **Measurement Method** | Uses DNA methylation levels at 173 CpG sites (Illumina EPIC array, blood). Trained on the Dunedin Longitudinal Study -- a birth cohort of 1,037 individuals followed from age 3 to 45 with 19 repeated measures of organ-system function over 20+ years. DunedinPACE measures the RATE of biological aging, not biological age itself. |
| **What It Measures** | Pace of aging: how fast a person is aging at the time of measurement. A value of 1.0 = aging at the normative rate (1 biological year per calendar year). Values >1.0 = aging faster; <1.0 = aging slower. For example, a value of 1.2 means aging at 1.2 biological years per calendar year. This is fundamentally different from biological age clocks, which estimate cumulative aging. |
| **Validation Status** | Validated in multiple cohorts (Framingham Heart Study Offspring, Normative Aging Study, CALERIE trial, UK Understanding Society, E-Risk Longitudinal Twin Study). Strongly predicts morbidity, disability, and mortality. Shown to be sensitive to caloric restriction in the CALERIE trial. |
| **Correlation with Mortality** | Strong. DunedinPACE predicts all-cause mortality, cardiovascular mortality, and cancer mortality. Each 0.1-unit increase in DunedinPACE associated with ~10-15% increased mortality risk [VERIFY exact HR]. Comparable to or better than GrimAge for some outcomes. |
| **Sensitivity to Interventions** | **Excellent -- this is its key advantage.** DunedinPACE was specifically designed to be sensitive to changes in the rate of aging. Validated sensitivity: (1) CALERIE 2-year caloric restriction trial reduced DunedinPACE by ~2-3% (slowed pace of aging); (2) Responds to lifestyle modifications; (3) Being used as an endpoint in multiple longevity clinical trials. Because it measures rate rather than cumulative damage, it is more responsive to interventions over shorter time periods than biological age clocks. |
| **Commercial Availability** | Available through TruDiagnostic (TruAge panel), and academically through the Belsky lab. |
| **Cost (approx.)** | $200-$500 (as part of TruDiagnostic panel) |
| **Key Publications** | Belsky DW, et al. DunedinPACE, a DNA methylation biomarker of the pace of aging. *eLife*. 2022;11:e73420. DOI: 10.7554/eLife.73420; Belsky DW, et al. Quantification of the pace of biological aging in humans through a blood test, the DunedinPoAm DNA methylation algorithm. *eLife*. 2020;9:e54870. DOI: 10.7554/eLife.54870 |
| **Strengths** | Measures rate of aging (not cumulative age) -- more clinically actionable; most sensitive to interventions among current clocks; trained on actual longitudinal aging data (not just cross-sectional age prediction); captures multi-organ-system decline; ideal for clinical trial endpoints |
| **Limitations** | Blood-based only; requires Illumina EPIC array; newer with less validation history than Horvath/GrimAge; the Dunedin cohort is predominantly European-ancestry, potentially limiting generalizability; rate measurement may have higher test-retest variability than cumulative measures |

---

### 1.6 DNAmTL (DNA Methylation Telomere Length)

| Field | Detail |
|-------|--------|
| **Name** | DNAmTL (DNA Methylation-based Telomere Length estimator) |
| **Type** | Specialized epigenetic measure (telomere length proxy) |
| **Developer/Originator** | Ake Lu, Steve Horvath (UCLA) |
| **Year Introduced** | 2019 |
| **Measurement Method** | Uses 140 CpG sites from Illumina 450K/EPIC array to estimate leukocyte telomere length (LTL) from DNA methylation patterns. Trained on directly measured LTL data. |
| **What It Measures** | Estimates telomere length from methylation data. Since methylation and telomere length are both affected by aging, this provides a complementary view of biological aging through the lens of telomere attrition. |
| **Validation Status** | Validated against directly measured telomere length by qPCR and terminal restriction fragment analysis. Predicts mortality and some age-related diseases independently of other epigenetic clocks. |
| **Correlation with Mortality** | Moderate. Shorter DNAmTL predicts increased mortality risk, coronary heart disease, and some cancers. Provides independent predictive information beyond chronological age and other epigenetic clocks. |
| **Sensitivity to Interventions** | Limited data. May respond to telomerase-activating interventions, but sensitivity to general longevity interventions (rapamycin, metformin, etc.) is less well-characterized. |
| **Commercial Availability** | Included in some comprehensive epigenetic testing panels (TruDiagnostic TruAge Complete) |
| **Cost (approx.)** | Included in panels ($250-$500) |
| **Key Publications** | Lu AT, et al. DNA methylation-based estimator of telomere length. *Aging (Albany NY)*. 2019;11(16):5895-5923. DOI: 10.18632/aging.102173 |

---

### 1.7 Skin & Blood Clock (Horvath 2018)

| Field | Detail |
|-------|--------|
| **Name** | Horvath Skin & Blood Clock |
| **Type** | Specialized first-generation clock |
| **Developer/Originator** | Steve Horvath (UCLA) |
| **Year Introduced** | 2018 |
| **Measurement Method** | Uses 391 CpG sites from Illumina EPIC array, trained specifically on skin and blood samples (including fibroblasts, keratinocytes, buccal cells, blood, dermis, epidermis). |
| **What It Measures** | Chronological age with special accuracy for skin-related cell types and blood. Designed to overcome limitations of the original Horvath clock for skin cells. |
| **Validation Status** | Validated in skin fibroblasts, blood, and buccal cells. Used in reprogramming studies to measure rejuvenation. |
| **Key Publications** | Horvath S, et al. Epigenetic clock for skin and blood cells applied to Hutchinson Gilford Progeria Syndrome and ex vivo studies. *Aging (Albany NY)*. 2018;10(7):1758-1775. DOI: 10.18632/aging.101508 |
| **Significance** | Particularly important for reprogramming research, as it accurately tracks age in fibroblasts used in Yamanaka factor experiments. Used by Gill et al. (2022) to demonstrate ~30-year rejuvenation in human fibroblasts. |

---

## PART 2: PROTEOMIC CLOCKS AND PROTEIN-BASED BIOMARKERS

---

### 2.1 SomaScan Proteomic Clock (Lehallier/Wyss-Coray)

| Field | Detail |
|-------|--------|
| **Name** | Plasma Proteomic Age (various implementations) |
| **Type** | Proteomic clock |
| **Developer/Originator** | Benoit Lehallier, Tony Wyss-Coray (Stanford University) |
| **Year Introduced** | 2019 |
| **Measurement Method** | Measures ~3,000-5,000 plasma proteins using the SomaScan aptamer-based proteomics platform (SomaLogic). Machine learning model predicts biological age from protein levels. |
| **What It Measures** | Biological age based on the plasma proteome. Captures systemic protein changes associated with aging, including inflammation, immune function, tissue damage, and metabolic function. |
| **Validation Status** | Validated in the Stanford/VA cohort (~4,263 people aged 18-95). Found non-linear aging waves at ages ~34, 60, and 78. Replicated in independent cohorts. |
| **Correlation with Mortality** | Not yet comprehensively validated for mortality prediction in the same way as GrimAge, but proteomic age acceleration associates with adverse health outcomes. |
| **Sensitivity to Interventions** | Potentially high -- proteins are rapidly turned over and responsive to physiological changes. However, intervention sensitivity has not been as thoroughly validated as for DunedinPACE. |
| **Commercial Availability** | Not directly available as a consumer product. SomaLogic provides research-grade proteomic services. Some longevity clinics offer proteomic aging panels. |
| **Cost (approx.)** | ~$1,000-$2,500+ for full SomaScan panel (research/clinical grade); not typically consumer-accessible |
| **Key Publications** | Lehallier B, et al. Undulating changes in human plasma proteome profiles across the lifespan. *Nat Med*. 2019;25(12):1843-1850. DOI: 10.1038/s41591-019-0673-2; Oh HS, et al. Organ aging signatures in the plasma proteome track health and disease. *Nature*. 2023;624:164-172. DOI: 10.1038/s41586-023-06802-1 [VERIFY DOI] |
| **Strengths** | Captures organ-specific aging signals (the Oh et al. 2023 study identified distinct aging signatures for 11 organs); directly measures functional proteins; potentially more mechanistically informative than methylation clocks |
| **Limitations** | Expensive; requires specialized platform; less validation history than epigenetic clocks; plasma proteins can be affected by acute illness, fasting state, and time of day |

---

### 2.2 Organ-Specific Proteomic Aging (Oh et al. 2023)

| Field | Detail |
|-------|--------|
| **Name** | Organ-Specific Plasma Proteomic Age |
| **Type** | Multi-organ proteomic clock |
| **Developer/Originator** | Hamilton Oh, Tony Wyss-Coray (Stanford University) |
| **Year Introduced** | 2023 |
| **Measurement Method** | Uses organ-enriched proteins from the SomaScan platform to generate organ-specific aging scores for 11 major organs: brain, heart, liver, kidney, lung, intestine, muscle, pancreas, immune system, fat, and vasculature. Each organ has its own aging clock based on proteins primarily produced by that organ. |
| **What It Measures** | Organ-by-organ biological age. Identifies which organs are aging faster or slower than expected. Enables detection of organ-specific accelerated aging that may precede clinical disease. |
| **Validation Status** | Validated in the UK Biobank (~5,000 samples) and independent cohorts. Organ-specific age acceleration predicted organ-specific disease (e.g., accelerated brain age predicted Alzheimer's risk; accelerated heart age predicted heart failure). |
| **Correlation with Mortality** | Multi-organ accelerated aging (accelerated aging in multiple organs simultaneously) was the strongest predictor of all-cause mortality -- ~50% increased mortality risk for individuals with accelerated aging in multiple organs. |
| **Key Findings** | ~1 in 5 apparently healthy adults aged 50+ had significantly accelerated aging in at least one organ. Organ aging was not always coordinated -- an individual could have accelerated brain aging but normal heart aging. This has important implications for personalized longevity interventions. |
| **Key Publications** | Oh HS, et al. Organ aging signatures in the plasma proteome track health and disease. *Nature*. 2023;624:164-172. DOI: 10.1038/s41586-023-06802-1 [VERIFY] |
| **Significance for Longevity Field** | Shifts the paradigm from "whole-body biological age" to "organ-specific aging profiles." Enables targeted interventions for the most rapidly aging organs. Could be used to select patients for organ-specific longevity trials. |

---

### 2.3 GDF-15 (Growth Differentiation Factor 15)

| Field | Detail |
|-------|--------|
| **Name** | GDF-15 |
| **Type** | Single protein biomarker of aging/stress |
| **Developer/Originator** | Multiple groups; heavily studied as an aging biomarker since ~2015 |
| **Measurement Method** | Standard immunoassay (ELISA) or multiplex platforms (Olink, SomaScan) from blood sample. Straightforward clinical lab test. |
| **What It Measures** | GDF-15 is a stress-responsive cytokine that rises dramatically with age, disease, and cellular stress. It is produced by multiple cell types in response to mitochondrial dysfunction, inflammation, and tissue damage. Levels increase ~2-5 fold between ages 30 and 80. |
| **Validation Status** | Extensively validated as a biomarker of aging and age-related disease. Among the strongest single protein predictors of all-cause mortality. |
| **Correlation with Mortality** | Very strong. GDF-15 is one of the single most powerful protein predictors of all-cause mortality, cardiovascular mortality, and cancer mortality. Each doubling of GDF-15 associated with ~1.5-2x increased mortality risk in many cohorts. Also predicts heart failure, CKD progression, and frailty. |
| **Sensitivity to Interventions** | Responds to: exercise (typically increases acutely, may decrease with training), weight loss, metformin (may reduce), GLP-1 agonists (reduce). Used as a secondary endpoint in some aging trials. |
| **Commercial Availability** | Available as a standard clinical lab test from Quest, Labcorp, and others. Included in many research panels. |
| **Cost (approx.)** | $50-$200 (clinical lab test); included in research multiplex panels |
| **Key Publications** | Wiklund FE, et al. Macrophage inhibitory cytokine-1 (MIC-1/GDF15): a new marker of all-cause mortality. *Aging Cell*. 2010;9(6):1057-1064. DOI: 10.1111/j.1474-9726.2010.00629.x |
| **Significance** | GDF-15 is a component of GrimAge (as one of the methylation-proxied proteins). Its direct measurement provides additional information. Increasingly viewed as a "sentinel biomarker" of multi-system aging. |

---

## PART 3: COMPOSITE BIOMARKER PANELS AND FUNCTIONAL MEASURES

---

### 3.1 TruAge (TruDiagnostic)

| Field | Detail |
|-------|--------|
| **Name** | TruAge |
| **Type** | Commercial comprehensive epigenetic aging panel |
| **Developer/Originator** | TruDiagnostic (Lexington, KY; CEO: Ryan Smith) |
| **Measurement Method** | Blood sample (mail-in kit). DNA extracted and run on Illumina EPIC array. Calculates multiple epigenetic clocks simultaneously: Horvath (multi-tissue), Hannum, PhenoAge, GrimAge/GrimAge2, DunedinPACE, DNAmTL, immune cell composition, and proprietary OMICm Age. |
| **What It Measures** | Provides a comprehensive epigenetic aging profile including biological age, pace of aging, telomere length estimate, immune age, and organ-specific aging signals. |
| **Validation Status** | Uses validated academic clocks (Horvath, GrimAge, DunedinPACE). TruDiagnostic has published validation studies and has the largest consumer epigenetic testing dataset. |
| **Commercial Availability** | Direct-to-consumer via trudiagnostic.com and through longevity clinicians. |
| **Cost (approx.)** | TruAge COMPLETE: ~$499; TruAge PACE: ~$229 (DunedinPACE + core clocks); discounts for multi-test packages [VERIFY current pricing] |
| **Key Features** | Most comprehensive commercial aging clock panel; includes DunedinPACE (exclusive commercial license); longitudinal tracking capability; reports designed for consumers and clinicians |
| **Key Publications** | TruDiagnostic has published technical validation papers and collaborated on multiple aging studies (e.g., the CaAKG biological age study, Demidenko et al. 2021). |

---

### 3.2 Elysium Index

| Field | Detail |
|-------|--------|
| **Name** | Elysium Index |
| **Type** | Commercial epigenetic aging test |
| **Developer/Originator** | Elysium Health (co-founded by Leonard Guarente, MIT) |
| **Measurement Method** | Saliva sample (mail-in kit). DNA methylation analysis via Illumina array. Calculates biological age and rate of aging. |
| **What It Measures** | Biological age (cumulative aging measure) and rate of aging (pace measure). |
| **Validation Status** | Based on validated clock algorithms. Elysium has published some validation data. |
| **Commercial Availability** | Direct-to-consumer via elysiumhealth.com |
| **Cost (approx.)** | ~$299 per test [VERIFY current pricing] |
| **Key Features** | Integration with Elysium's supplement products (Basis NR + pterostilbene); longitudinal tracking; consumer-friendly reporting |
| **Limitations** | Saliva-based (which can have different methylation patterns than blood); less comprehensive than TruDiagnostic panel; potential conflict of interest as Elysium sells supplements that they then measure |

---

### 3.3 InsideTracker (InnerAge)

| Field | Detail |
|-------|--------|
| **Name** | InsideTracker InnerAge |
| **Type** | Blood biomarker-based biological age (not epigenetic) |
| **Developer/Originator** | InsideTracker (co-founded by Gil Blander, MIT) |
| **Measurement Method** | Standard blood panel measuring ~40+ biomarkers (glucose, hsCRP, LDL, HDL, triglycerides, HbA1c, albumin, creatinine, liver enzymes, CBC, hormones, vitamins, etc.). Machine learning algorithm calculates "InnerAge" from these biomarkers. |
| **What It Measures** | Biological age based on blood biomarker profile. Provides actionable recommendations to improve specific biomarkers through diet, exercise, and supplementation. |
| **Validation Status** | Proprietary algorithm. Less rigorously validated in peer-reviewed literature than epigenetic clocks. Based on known associations between blood biomarkers and aging/mortality. |
| **Correlation with Mortality** | Indirect -- the individual biomarkers (CRP, glucose, etc.) are each validated mortality predictors. The composite "InnerAge" algorithm is proprietary and less externally validated. |
| **Commercial Availability** | Direct-to-consumer via insidetracker.com. Can use lab results from standard blood draws. |
| **Cost (approx.)** | $189-$589 depending on panel comprehensiveness [VERIFY] |
| **Strengths** | Actionable recommendations; uses standard blood biomarkers (no specialized array needed); frequent testing feasible; tracks progress over time; integration with wearable data |
| **Limitations** | Proprietary algorithm with limited peer-reviewed validation; based on blood biomarkers rather than deeper molecular aging measures; acute illness, fasting, hydration can significantly affect results |

---

### 3.4 GlycanAge

| Field | Detail |
|-------|--------|
| **Name** | GlycanAge |
| **Type** | Glycomic aging biomarker |
| **Developer/Originator** | Genos Ltd (Zagreb, Croatia); Scientific advisor: Gordan Lauc |
| **Year Introduced** | ~2018 (commercial) |
| **Measurement Method** | Blood sample analyzed by ultra-performance liquid chromatography (UPLC) for the glycan profile of immunoglobulin G (IgG). IgG glycosylation changes with age and inflammation: younger individuals have more galactosylated and sialylated glycans; older individuals have more agalactosylated (pro-inflammatory) glycans. |
| **What It Measures** | Biological age based on the inflammatory status of the immune system as reflected by IgG glycosylation patterns. High GlycanAge indicates a pro-inflammatory immune state associated with accelerated aging. |
| **Validation Status** | Validated in multiple cohorts (>100,000 samples). IgG glycan changes with age are well-documented in the literature. GlycanAge correlates with chronological age, inflammatory markers, and disease risk. |
| **Correlation with Mortality** | Not as extensively validated for mortality prediction as epigenetic clocks. Better validated for immune aging and inflammatory status. |
| **Sensitivity to Interventions** | Responsive to: lifestyle changes (diet, exercise, stress reduction), weight loss, and potentially supplements. Some evidence of response to anti-inflammatory interventions. Changes can be detected within 3-6 months. |
| **Commercial Availability** | Direct-to-consumer via glycanage.com |
| **Cost (approx.)** | ~$299-$399 per test [VERIFY] |
| **Key Publications** | Kristic J, et al. Glycans are a novel biomarker of chronological and biological ages. *J Gerontol A Biol Sci Med Sci*. 2014;69(7):779-789. DOI: 10.1093/gerona/glt190 |
| **Strengths** | Unique glycomic perspective; captures immune/inflammatory aging; responsive to lifestyle changes; well-established glycobiology foundation |
| **Limitations** | Measures a single dimension of aging (immune/inflammatory); less comprehensive than multi-omic panels; niche technology (glycomics less widely used than genomics or proteomics) |

---

### 3.5 Tally Health (Sinclair Lab)

| Field | Detail |
|-------|--------|
| **Name** | TallyAge |
| **Type** | Epigenetic aging test + personalized recommendations |
| **Developer/Originator** | Tally Health (co-founded by David Sinclair, Harvard) |
| **Measurement Method** | Cheek swab (buccal sample). DNA methylation analysis using a custom panel. Proprietary clock algorithm (CheekAge, published 2024 [VERIFY]). |
| **What It Measures** | Biological age from buccal cell methylation. Provides personalized recommendations for lifestyle, diet, and supplementation to slow biological aging. |
| **Validation Status** | CheekAge was reported to predict mortality in validation cohorts [VERIFY for publication details]. Less externally validated than established academic clocks. |
| **Commercial Availability** | Direct-to-consumer via tallyhealth.com |
| **Cost (approx.)** | ~$229 per test; subscription model ~$99/month for ongoing testing + recommendations [VERIFY] |
| **Key Features** | Non-invasive (cheek swab, no blood draw); gamified/consumer-friendly interface; personalized action plans; subscription model for longitudinal tracking |
| **Limitations** | Buccal-based (may not reflect systemic aging); proprietary algorithm with limited independent validation; David Sinclair's commercial involvement raises conflict-of-interest concerns similar to his NMN ventures |

---

## PART 4: EMERGING AND SPECIALIZED CLOCKS

---

### 4.1 OmicAge / OMICm Age

| Field | Detail |
|-------|--------|
| **Name** | OmicAge (also referred to as OMICm Age) |
| **Type** | Multi-omic aging clock |
| **Developer/Originator** | TruDiagnostic / collaborators [VERIFY exact origins] |
| **Year Introduced** | 2023-2024 [VERIFY] |
| **Measurement Method** | Integrates DNA methylation data with other omic layers (metabolomics, proteomics) and clinical biomarkers to create a more comprehensive aging estimate. Specific methodology may vary. |
| **What It Measures** | A composite biological age that integrates multiple molecular dimensions of aging, potentially capturing more information than any single-omic clock. |
| **Validation Status** | Early validation reported; less extensively validated than established epigenetic clocks [VERIFY for published validation studies] |
| **Commercial Availability** | Available through TruDiagnostic as part of comprehensive panels [VERIFY] |
| **Key Publications** | [VERIFY for specific publication] |
| **Significance** | Represents the trend toward multi-omic integration for more accurate biological age estimation. The hypothesis is that combining multiple molecular modalities captures more aspects of aging than any single measure. |

---

### 4.2 Metabolomic Clocks

| Field | Detail |
|-------|--------|
| **Name** | Various metabolomic age predictors |
| **Type** | Metabolomic clock |
| **Developers** | Multiple groups (Robinson et al. 2020; van den Akker et al. 2020) |
| **Measurement Method** | Plasma or serum metabolomics (LC-MS/MS or NMR spectroscopy) measuring hundreds to thousands of small molecules. Machine learning models trained to predict age or mortality from metabolomic profiles. |
| **What It Measures** | Biological age based on the metabolome -- the comprehensive set of small molecules in blood, reflecting metabolic pathway activity, mitochondrial function, gut microbiome metabolism, and systemic homeostasis. |
| **Validation Status** | Multiple metabolomic age predictors published and validated in independent cohorts. Generally less predictive of mortality than the best epigenetic clocks. |
| **Key Publications** | Robinson O, et al. Determinants of accelerated metabolomic and epigenetic aging in a UK cohort. *Aging Cell*. 2020;19(6):e13149. DOI: 10.1111/acel.13149 [VERIFY] |
| **Strengths** | Captures real-time metabolic state; potentially very responsive to interventions; metabolites are the functional readout of gene expression and enzymatic activity |
| **Limitations** | Highly variable (affected by diet, fasting state, time of day, exercise, medications); less established than epigenetic clocks; no dominant standardized clock model; more expensive testing |

---

### 4.3 Transcriptomic Clocks (RNAge)

| Field | Detail |
|-------|--------|
| **Name** | Various transcriptomic age predictors (e.g., RNAge) |
| **Type** | Transcriptomic clock |
| **Developers** | Multiple groups |
| **Measurement Method** | Whole blood or tissue RNA-seq or microarray gene expression profiling. Machine learning models trained to predict age from gene expression patterns. |
| **What It Measures** | Biological age based on gene expression patterns. Captures transcriptomic dysregulation that occurs with aging, including changes in immune, inflammatory, metabolic, and stress response genes. |
| **Validation Status** | Several models published and validated. Generally less robust than epigenetic clocks for age prediction, partly due to higher variability in gene expression measurements. |
| **Strengths** | Directly reflects gene activity; can be tissue-specific; captures functional changes |
| **Limitations** | RNA is unstable and expression varies widely with environmental factors; less reproducible than DNA methylation; not yet standardized for clinical use |

---

### 4.4 Immune Age (Immunosenescence Markers)

| Field | Detail |
|-------|--------|
| **Name** | Immune Age / T-cell Aging Clock |
| **Type** | Immunological aging biomarker |
| **Developers** | Multiple groups; integrated into TruDiagnostic panels via DNA methylation deconvolution |
| **Measurement Method** | Can be measured by: (1) Flow cytometry of T-cell subsets (naive vs. memory, CD4/CD8 ratio, PD-1/KLRG1 expression on T cells); (2) DNA methylation-based immune cell deconvolution (estimates proportions of naive T cells, memory T cells, B cells, NK cells, monocytes from methylation data). |
| **What It Measures** | The age of the immune system, characterized by: declining naive T cell frequency, increased memory/senescent T cells, inverted CD4/CD8 ratio, reduced thymic output, increased inflammatory monocytes. These changes (collectively "immunosenescence") increase susceptibility to infections, cancer, and autoimmunity. |
| **Validation Status** | Well-validated. Immune aging is one of the best-characterized aspects of biological aging. Specific immune parameters predict mortality and vaccine response in elderly. |
| **Sensitivity to Interventions** | Responsive to: mTOR inhibitors (Mannick et al. showed everolimus rejuvenated immune function), thymic regeneration therapies (TRIIM trial), exercise, nutrition. |
| **Key Publications** | Sayed N, et al. An inflammatory aging clock (iAge) based on deep learning tracks multi-morbidity, immunosenescence, frailty and cardiovascular aging. *Nat Aging*. 2021;1:598-615. DOI: 10.1038/s43587-021-00082-y |
| **Significance** | Immune aging is directly clinically relevant (infections, cancer, vaccine efficacy). The Mannick everolimus studies and the TRIIM trial specifically targeted and demonstrated immune rejuvenation. |

---

### 4.5 Inflammatory Age (iAge)

| Field | Detail |
|-------|--------|
| **Name** | iAge (Inflammatory Age) |
| **Type** | Inflammatory aging clock |
| **Developer/Originator** | Nazish Sayed, David Furman (Stanford/Buck Institute); commercialized by Edifice Health |
| **Year Introduced** | 2021 |
| **Measurement Method** | Measures ~50 inflammatory cytokines and chemokines in blood (using Luminex multiplex or similar platform). Deep learning model calculates inflammatory age. The key driver of iAge was identified as CXCL9 (a chemokine associated with T-cell immune responses and vascular aging). |
| **What It Measures** | Inflammatory age -- the degree of chronic, low-grade inflammation (inflammaging) in the system. Higher iAge = more inflammation = accelerated aging. |
| **Validation Status** | Validated in the Stanford 1000 Immunomes cohort and replicated in additional cohorts. Predicts cardiovascular aging, multi-morbidity, and frailty independently of chronological age. |
| **Correlation with Mortality** | Moderate to strong. iAge acceleration associated with cardiovascular disease, immune decline, and multi-morbidity. |
| **Commercial Availability** | Available through Edifice Health (edificehealth.com) [VERIFY current status and pricing] |
| **Cost (approx.)** | ~$500-$1,000 [VERIFY] |
| **Key Publications** | Sayed N, et al. An inflammatory aging clock (iAge) based on deep learning tracks multi-morbidity, immunosenescence, frailty and cardiovascular aging. *Nat Aging*. 2021;1:598-615. DOI: 10.1038/s43587-021-00082-y |

---

## PART 5: FUNCTIONAL AND CLINICAL AGING BIOMARKERS

---

### 5.1 Frailty Index (Fried / Rockwood)

| Field | Detail |
|-------|--------|
| **Name** | Fried Frailty Phenotype / Rockwood Frailty Index |
| **Type** | Clinical functional assessment |
| **Developers** | Linda Fried (Columbia); Kenneth Rockwood (Dalhousie) |
| **Measurement Method** | Fried Phenotype: 5 criteria -- unintentional weight loss, exhaustion, low physical activity, slow gait speed, weak grip strength. 0 criteria = robust; 1-2 = pre-frail; 3+ = frail. Rockwood Index: deficits across 30-70 health variables (accumulation of deficits model). Score 0-1. |
| **What It Measures** | Overall functional aging and vulnerability to adverse health outcomes. Captures the clinical manifestation of biological aging. |
| **Validation Status** | Extensively validated over 20+ years. Frailty predicts falls, hospitalization, disability, and mortality. Used globally in clinical settings and research. |
| **Correlation with Mortality** | Very strong. Frailty (either Fried or Rockwood) is one of the strongest clinical predictors of mortality in older adults, independent of age, comorbidities, and disability. |
| **Use in Clinical Trials** | Used as an inclusion criterion and endpoint in senolytic trials (D+Q, fisetin) and other aging trials. |
| **Cost** | Free -- clinical assessment; no lab test needed |
| **Key Publications** | Fried LP, et al. Frailty in older adults: evidence for a phenotype. *J Gerontol A Biol Sci Med Sci*. 2001;56(3):M146-M156. |

---

### 5.2 Grip Strength

| Field | Detail |
|-------|--------|
| **Name** | Hand Grip Strength |
| **Type** | Physical function biomarker |
| **Measurement Method** | Measured with a handheld dynamometer (e.g., Jamar). Maximum force in kg. |
| **What It Measures** | Upper body muscle strength, reflecting overall sarcopenia and physical function decline. Simple, inexpensive, and widely used. |
| **Validation Status** | Extensively validated. Among the strongest single physical function predictors of mortality in older adults. |
| **Correlation with Mortality** | Very strong. Low grip strength predicts all-cause mortality, cardiovascular mortality, and disability. Each 5 kg decline in grip strength associated with ~15-20% increased mortality risk. |
| **Sensitivity to Interventions** | Responsive to exercise, nutritional interventions, and potentially pharmacological geroprotective agents (GlyNAC, urolithin A). |
| **Cost** | ~$25-$50 for a dynamometer; free to administer |

---

### 5.3 Gait Speed

| Field | Detail |
|-------|--------|
| **Name** | Usual Gait Speed |
| **Type** | Physical function biomarker |
| **Measurement Method** | Timed walk over a standardized distance (typically 4 meters or 6 meters). Measured in meters per second (m/s). |
| **What It Measures** | Walking speed, reflecting lower body strength, balance, coordination, and overall physical function. Called the "sixth vital sign" in geriatrics. |
| **Validation Status** | Extremely well-validated. One of the most robust predictors of outcomes in older adults. |
| **Correlation with Mortality** | Very strong. Gait speed <0.8 m/s associated with significantly increased mortality. Each 0.1 m/s increase associated with ~12% reduced mortality risk. Gait speed <0.6 m/s is associated with very high risk. |
| **Sensitivity to Interventions** | Responsive to exercise, D+Q (used as endpoint in frailty trials), GlyNAC, and physical therapy. |
| **Cost** | Free -- requires only a stopwatch and a hallway |
| **Key Publications** | Studenski S, et al. Gait speed and survival in older adults. *JAMA*. 2011;305(1):50-58. DOI: 10.1001/jama.2010.1923 |

---

## PART 6: USE AS CLINICAL TRIAL ENDPOINTS

---

### Summary of Biomarker Suitability for Aging Clinical Trials

| Biomarker | FDA Acceptance as Endpoint | Sensitivity Window | Advantages | Disadvantages |
|-----------|---------------------------|-------------------|------------|---------------|
| GrimAge/GrimAge2 | Not yet accepted; strong candidate | 6-12 months | Strongest mortality predictor; validated | Blood-only; requires specialized array |
| DunedinPACE | Not yet accepted; strongest candidate for pace-of-aging | 3-6 months | Measures rate of aging; most sensitive to interventions | Newer; less validation history |
| PhenoAge | Not yet accepted | 3-6 months | Clinical biomarker basis; intuitive | Blood-only; affected by acute illness |
| Composite clinical (gait speed, grip, SPPB) | Accepted by FDA as functional endpoints | 3-12 months | Direct clinical relevance; validated; cheap | Insensitive to molecular changes; large trials needed |
| SASP markers (IL-6, MMP, PAI-1) | Exploratory biomarkers only | 1-3 months | Directly reflects senolytic mechanism | Variable; not specific to senescence |
| NAD+ metabolites | Exploratory biomarkers only | 1-4 weeks | Directly reflects NMN/NR intervention | Does not predict clinical outcomes reliably |
| p16INK4a (tissue) | Exploratory | Requires biopsy | Direct senescent cell marker | Invasive; tissue-specific; variable measurement |
| Frailty index | Accepted by FDA (composite functional) | 3-12 months | Clinical relevance; validated | Subjective components; floor/ceiling effects |
| Proteomic age | Exploratory | 1-6 months | Organ-specific; mechanistic insight | Expensive; early validation stage |

### Key Trial Design Considerations

1. **TAME trial** uses a composite disease endpoint (first occurrence of CV event, cancer, dementia, or death) as primary, with biological aging biomarkers as secondary endpoints. This is the FDA-accepted gold standard.

2. **PEARL trial** uses epigenetic clocks (GrimAge, DunedinPACE) as primary endpoints -- a novel approach that could accelerate aging drug development if validated.

3. **Senolytic trials** typically use SASP marker reduction as mechanism-of-action endpoints and functional measures (gait speed, 6-minute walk) as clinical endpoints.

4. **The field consensus** is moving toward DunedinPACE as the preferred epigenetic endpoint for shorter trials (able to detect changes in 6-12 months) and GrimAge for longer trials (>12 months).

5. **Multi-modal approaches** combining epigenetic, proteomic, functional, and clinical endpoints are increasingly recommended for comprehensive aging trial assessment.

---

## COMPARATIVE SUMMARY TABLE

| Clock/Biomarker | Type | Year | CpGs/Features | Mortality Prediction | Intervention Sensitivity | Commercial? | Cost |
|----------------|------|------|---------------|---------------------|------------------------|-------------|------|
| Horvath | Epigenetic (1st gen) | 2013 | 353 CpGs | Moderate | Moderate | Yes | $200-500 |
| Hannum | Epigenetic (1st gen) | 2013 | 71 CpGs | Moderate | Moderate | Yes | $200-500 |
| PhenoAge | Epigenetic (2nd gen) | 2018 | 513 CpGs | Strong | Moderate-Good | Yes | $200-500 |
| GrimAge/2 | Epigenetic (2nd gen) | 2019/2022 | 1030 CpGs | Very Strong | Good | Yes | $250-500 |
| DunedinPACE | Epigenetic (3rd gen) | 2022 | 173 CpGs | Strong | Excellent | Yes | $229-500 |
| DNAmTL | Epigenetic (specialized) | 2019 | 140 CpGs | Moderate | Limited data | Yes | In panels |
| Proteomic Age | Proteomic | 2019 | ~3000 proteins | Moderate-Strong | Good (theoretical) | Research | $1000-2500 |
| Organ-Specific | Proteomic | 2023 | Organ proteins | Strong (multi-organ) | Unknown | Research | $1000-2500 |
| iAge | Inflammatory | 2021 | ~50 cytokines | Moderate-Strong | Moderate | Limited | $500-1000 |
| GlycanAge | Glycomic | 2014 | IgG glycans | Moderate | Moderate | Yes | $299-399 |
| GDF-15 | Single protein | ~2010 | 1 protein | Very Strong | Good | Yes | $50-200 |
| Gait Speed | Functional | 2001 | N/A | Very Strong | Good | Free | Free |
| Grip Strength | Functional | Various | N/A | Very Strong | Good | Free | ~$30 |
| Frailty Index | Clinical composite | 2001 | 5-70 items | Very Strong | Good | Free | Free |

---

*Document compiled: February 2025*
*Data currency: Through May 2025 training data*
*Items marked [VERIFY] should be confirmed with live search for current pricing, availability, or latest validation studies*
