# Group 7: Inflammaging Targets

> **Data Source Note:** Compiled from training knowledge through May 2025. Items marked [VERIFY] would benefit from live search confirmation.

---

## 7.1 cGAS-STING Pathway in Aging

### Biological Background

The cGAS-STING (cyclic GMP-AMP synthase -- stimulator of interferon genes) pathway is a cytosolic DNA sensing mechanism that has emerged as a central driver of age-related sterile inflammation (inflammaging).

**Normal function:** The cGAS-STING pathway evolved to detect cytosolic DNA from invading pathogens (viruses, bacteria). When cGAS detects double-stranded DNA in the cytoplasm:

1. **cGAS activation:** cGAS binds cytosolic dsDNA and catalyzes the synthesis of 2'3'-cyclic GMP-AMP (cGAMP)
2. **STING activation:** cGAMP binds to STING (an ER-resident adaptor protein), causing STING to translocate from ER to Golgi
3. **TBK1 activation:** STING recruits and activates TBK1 (TANK-binding kinase 1)
4. **IRF3 phosphorylation:** TBK1 phosphorylates IRF3, which dimerizes and translocates to the nucleus
5. **Type I interferon production:** IRF3 drives expression of type I interferons (IFN-alpha, IFN-beta) and interferon-stimulated genes (ISGs)
6. **NF-kB activation:** STING also activates NF-kB, driving production of pro-inflammatory cytokines (IL-6, TNF-alpha, IL-1beta)

### cGAS-STING in Aging

**Why does cGAS-STING become activated with aging?** Multiple sources of cytosolic DNA accumulate in aged cells:

1. **Mitochondrial DNA (mtDNA) leakage:**
   - Aged, damaged mitochondria leak mtDNA into the cytosol through BAX/BAK pores and mitochondrial permeability transition pore (mPTP)
   - mtDNA is recognized as "foreign" by cGAS because it resembles bacterial DNA
   - This is a major driver of age-related cGAS-STING activation

2. **Nuclear DNA damage and micronuclei:**
   - Genomic instability leads to formation of micronuclei (aberrant nuclear structures containing damaged chromosomes)
   - Micronuclei rupture releases nuclear DNA into the cytoplasm
   - cGAS localizes to ruptured micronuclei and triggers STING signaling

3. **LINE-1 retrotransposon derepression:**
   - Aging is associated with epigenetic derepression of LINE-1 (L1) retrotransposons
   - Active L1 elements produce cytosolic DNA intermediates (cDNA) during retrotransposition
   - L1-derived cytosolic DNA activates cGAS
   - SIRT6 decline with age contributes to L1 derepression (connecting to Section 5.4)
   - De Cecco et al. 2019 showed this is a major driver of inflammaging in aged mice

4. **Senescent cell SASP amplification:**
   - Senescent cells activate cGAS-STING due to cytoplasmic chromatin fragments (CCF)
   - cGAS-STING signaling amplifies the SASP, creating a positive feedback loop
   - Senescent cell --> CCF --> cGAS-STING --> SASP amplification --> paracrine senescence

5. **Nuclear envelope breakdown:**
   - Age-related loss of lamin B1 compromises nuclear envelope integrity
   - Nuclear DNA leaks into cytoplasm through nuclear envelope gaps

### Key Preclinical Results

| Study | Species | Key Finding | Reference |
|-------|---------|-------------|-----------|
| De Cecco et al. 2019 | Mouse | LINE-1 retrotransposon activation drives age-associated inflammation through cGAS-STING pathway; STING knockout or L1 reverse transcriptase inhibitors (e.g., lamivudine/3TC) reduced inflammaging and improved tissue function in aged mice | De Cecco M, et al. Nature. 2019;566(7742):73-78. DOI: 10.1038/s41586-019-0909-y |
| Dou et al. 2017 | Human cells + Mouse | Cytoplasmic chromatin fragments (CCF) in senescent cells activate cGAS-STING to drive SASP; cGAS knockout reduced SASP and paracrine senescence | Dou Z, et al. Nature. 2017;550(7676):402-406. DOI: 10.1038/nature24050 |
| Gulen et al. 2023 | Mouse | **KEY 2023 PAPER:** STING drives age-related inflammation and neurodegeneration; genetic or pharmacological STING inhibition in aged mice reduced inflammation, improved tissue function, improved cognitive function, and extended healthspan. STING inhibitor H-151 improved multiple aging phenotypes | Gulen MF, et al. Nature. 2023;620(7973):374-381. DOI: 10.1038/s41586-023-06373-1 |
| Haag et al. 2018 | Mouse | STING promotes cardiac inflammation and fibrosis after myocardial infarction; STING deletion is protective | Haag SM, et al. Immunity. 2018;49(1):158-167 |
| Decout et al. 2021 | Review | Comprehensive review of cGAS-STING in sterile inflammation and aging | Decout A, et al. Nat Rev Immunol. 2021;21(8):548-569. DOI: 10.1038/s41577-021-00524-z |

**The Gulen et al. 2023 Nature paper is the most important study linking cGAS-STING directly to aging:**
- Showed STING activation increases with age across multiple tissues
- STING drives age-related inflammation in brain, liver, kidney, fat
- Pharmacological STING inhibition (H-151) in aged mice:
  - Reduced neuroinflammation
  - Improved cognitive function
  - Reduced peripheral tissue inflammation
  - Improved physical function
- STING drives inflammaging partly through activation of NLRP3 inflammasome

### Therapeutic Approaches Targeting cGAS-STING in Aging

**1. STING inhibitors:**
- **H-151:** The most commonly used preclinical STING inhibitor; covalently modifies STING palmitoylation site
- **C-178, C-176:** Additional STING inhibitors
- Multiple pharmaceutical companies developing STING inhibitors for autoimmune/inflammatory conditions (these could be repurposed for aging)
- IFM Tre (acquired by Novartis), Nimbus Therapeutics, others developing STING pathway modulators [VERIFY]

**2. cGAS inhibitors:**
- **RU.521:** cGAS inhibitor
- **Aspirin:** Identified as a weak cGAS inhibitor (acetylates cGAS); another potential mechanism for aspirin's anti-inflammatory/cardioprotective effects
- **G150:** Selective cGAS inhibitor [VERIFY]

**3. Reverse transcriptase inhibitors (L1 targeting):**
- **Lamivudine (3TC):** FDA-approved NRTi (HIV/HBV drug) that inhibits L1 reverse transcriptase; reduced inflammaging in aged mice (De Cecco et al. 2019)
- **Other NRTIs:** Potentially repurposable for anti-aging (stavudine, tenofovir)
- This is a particularly attractive approach because NRTIs are already FDA-approved with well-characterized safety profiles

**4. Downstream pathway modulation:**
- **TBK1 inhibitors:** GSK8612 and others
- **IRF3 pathway modulators**
- **NF-kB inhibitors:** Broad category (many existing drugs)

### Clinical Trial Status (as of early 2025)

**No clinical trials specifically testing cGAS-STING inhibition for aging.**

**However, related trials:**
- STING agonists are in clinical trials for cancer (immunotherapy); these activate STING rather than inhibit it
- STING inhibitors are being developed for autoimmune conditions (lupus, Aicardi-Goutieres syndrome) and could eventually be repurposed for aging
- **Lamivudine for aging:** No registered trial specifically for aging, but the well-characterized safety profile and preclinical aging data make this an attractive repurposing candidate [VERIFY if any trial planned]

### 2023-2025 Developments

- **Gulen et al. 2023 Nature paper** established cGAS-STING as a bona fide aging target (not just correlational)
- Multiple pharmaceutical companies developing STING pathway modulators; the oncology STING agonist programs have generated extensive medicinal chemistry knowledge that can be leveraged for inhibitor development
- **L1 retrotransposon-aging connection:** Growing recognition that retrotransposon activation is a fundamental driver of inflammaging, connecting genomic instability to inflammation through cGAS-STING
- **Lamivudine repurposing interest:** Growing discussion in the longevity community about repurposing NRTIs for anti-aging, given the De Cecco et al. 2019 and subsequent data
- cGAS-STING identified as a key mediator connecting multiple hallmarks of aging (genomic instability, cellular senescence, mitochondrial dysfunction, inflammation)

### Safety Considerations for STING Inhibition

- **Immunosuppression risk:** STING is part of innate antiviral defense; chronic inhibition could increase susceptibility to viral infections
- **Cancer risk:** STING signaling contributes to anti-tumor immune surveillance; chronic inhibition could impair cancer immunity
- **Autoimmune benefit:** In patients with sterile inflammation-driven conditions, STING inhibition may be beneficial (balancing risk-benefit)
- **Tissue-specific effects:** Brain, liver, and other tissues may have different dependencies on STING signaling
- **NRTIs (lamivudine):** Well-characterized safety profile from HIV/HBV treatment; main concerns are renal toxicity (rare at low doses) and mitochondrial toxicity (class effect of NRTIs, generally manageable)

### Key Publications

1. De Cecco M, Ito T, Petrashen AP, et al. L1 drives IFN in senescent cells and promotes age-associated inflammation. *Nature*. 2019;566(7742):73-78. DOI: 10.1038/s41586-019-0909-y
2. Dou Z, Ghosh K, Vizioli MG, et al. Cytoplasmic chromatin triggers inflammation in senescence and cancer. *Nature*. 2017;550(7676):402-406. DOI: 10.1038/nature24050
3. Gulen MF, Samson N, Keller A, et al. cGAS-STING drives ageing-related inflammation and neurodegeneration. *Nature*. 2023;620(7973):374-381. DOI: 10.1038/s41586-023-06373-1
4. Decout A, Katz JD, Venkatraman S, Bhatti S. The cGAS-STING pathway as a therapeutic target in inflammatory diseases. *Nat Rev Immunol*. 2021;21(8):548-569. DOI: 10.1038/s41577-021-00524-z

---

## 7.2 IL-6 Inhibition and Inflammaging

### IL-6 in Aging

Interleukin-6 (IL-6) is one of the most consistently elevated cytokines in aged individuals and is a central mediator of chronic low-grade inflammation (inflammaging).

**IL-6 biology relevant to aging:**

1. **Sources of age-related IL-6 elevation:**
   - Senescent cells (IL-6 is a core SASP factor)
   - Visceral adipose tissue (adipose tissue macrophages)
   - Activated innate immune cells (monocytes, macrophages)
   - Endothelial cells
   - Gut microbiome-driven immune activation
   - cGAS-STING pathway activation (NF-kB-driven)

2. **IL-6 signaling pathways:**
   - **Classic signaling:** IL-6 binds membrane-bound IL-6R (expressed on hepatocytes, some immune cells); generally anti-inflammatory and regenerative
   - **Trans-signaling:** IL-6 binds soluble IL-6R (sIL-6R), and the complex signals through ubiquitous gp130; this is the pro-inflammatory, disease-promoting pathway
   - **Trans-presentation:** IL-6/IL-6R complex on one cell activates gp130 on an adjacent cell
   - **JAK/STAT3 activation:** All signaling modes activate JAK1/2 and STAT3 transcription factor

3. **Downstream effects of chronic IL-6 elevation:**
   - Acute phase response (CRP elevation)
   - Insulin resistance
   - Muscle wasting (sarcopenia)
   - Bone loss (osteoclast activation)
   - Cognitive decline (neuroinflammation)
   - Anemia of chronic disease
   - Immunosenescence (impaired adaptive immunity)
   - Thrombotic risk (fibrinogen elevation)
   - Fatigue and depression

4. **IL-6 as a biomarker:** IL-6 is one of the strongest predictors of:
   - All-cause mortality in older adults
   - Frailty
   - Disability
   - Cardiovascular events
   - Cancer mortality

### Therapeutic Approaches

**FDA-approved IL-6 pathway inhibitors:**

| Drug | Target | Approved Indications | Mechanism |
|------|--------|---------------------|-----------|
| **Tocilizumab (Actemra)** | IL-6R (blocks both classic and trans-signaling) | RA, GCA, COVID-19 cytokine storm, JIA, CRS | Humanized anti-IL-6R monoclonal antibody |
| **Sarilumab (Kevzara)** | IL-6R | RA | Human anti-IL-6R monoclonal antibody |
| **Siltuximab (Sylvant)** | IL-6 (binds IL-6 directly) | Multicentric Castleman disease | Chimeric anti-IL-6 monoclonal antibody |

**Selective trans-signaling inhibition:**
| Drug | Target | Status |
|------|--------|--------|
| **Olamkicept (sgp130Fc)** | Selectively blocks IL-6 trans-signaling (spares classic signaling) | Phase 2 for IBD; theoretical advantage for aging (blocks pathological signaling, preserves beneficial signaling) [VERIFY] |

### Preclinical Data for IL-6 Inhibition in Aging

| Study | Species | Key Finding | Reference |
|-------|---------|-------------|-----------|
| Ferrucci et al. 2005 | Human (observational) | IL-6 levels predict disability, mortality, and decline in physical function in older adults; dose-response relationship | Ferrucci L, et al. J Am Geriatr Soc. 2005;53:S17-18 [VERIFY exact citation] |
| O'Brien et al. 2014 | Human (observational, InCHIANTI) | Higher IL-6 associated with accelerated functional decline; inflammation mediates relationship between obesity and disability | [VERIFY exact citation] |
| McElvaney et al. 2021 | Human (COVID-19) | Tocilizumab reduced IL-6-driven organ damage in COVID-19; demonstrated safety of acute IL-6 blockade in elderly | McElvaney OJ, et al. Nat Med. 2021 [VERIFY] |
| Various | Mouse | Anti-IL-6 or IL-6 knockout in aged mice improves muscle function, reduces fibrosis, improves metabolic health | Multiple studies |

### Clinical Trial Status for Aging

**No registered clinical trials specifically testing IL-6 inhibition for aging/longevity as of early 2025.**

**Indirect evidence from disease trials in elderly populations:**
- Tocilizumab in rheumatoid arthritis (predominantly elderly patients): Consistent improvements in inflammatory markers, fatigue, anemia, bone density
- COVID-19 trials (RECOVERY, REMAP-CAP): Tocilizumab in elderly COVID patients reduced mortality and organ damage; demonstrated safety of IL-6 blockade in this population
- Giant cell arteritis (GCA) trials: Tocilizumab reduced disease activity and steroid need in patients >50 years

**Rationale for aging trial:**
- IL-6 is the most consistently elevated cytokine in aging
- FDA-approved drugs with established safety profiles exist
- Multiple tissue targets would benefit from IL-6 reduction
- Biomarker (IL-6 levels) is readily measurable and modifiable

**Barriers to aging trial:**
- Cost: Tocilizumab costs ~$1,000-2,000/month
- Immunosuppression risk: IL-6 is important for acute phase response and infection defense
- Infection susceptibility: Chronic IL-6 blockade increases risk of bacterial infections
- Long-term safety uncertainty: Effects of chronic IL-6 blockade in healthy older adults unknown
- Selective trans-signaling inhibition (olamkicept/sgp130Fc) might have a better risk-benefit ratio

### 2023-2025 Developments

- **Growing recognition of IL-6 as an "aging cytokine":** Multiple publications establishing IL-6 as a causal mediator (not just biomarker) of age-related decline
- **Olamkicept (sgp130Fc):** The selective trans-signaling inhibitor is in Phase 2 for IBD and could be a safer option for aging if proven effective. By blocking only pathological trans-signaling while preserving beneficial classic signaling, it may avoid the infection risk of complete IL-6R blockade [VERIFY for latest trial results]
- **IL-6 as a drug target for frailty:** Discussion in the geriatrics literature about targeting IL-6 specifically for frailty prevention [VERIFY specific publications]
- **Multi-pathway approaches:** Recognition that IL-6 is downstream of multiple aging pathways (senescence, cGAS-STING, metabolic dysfunction); targeting upstream drivers may be more effective than blocking IL-6 alone
- **Anti-aging JAK inhibitors:** JAK inhibitors (ruxolitinib, tofacitinib, baricitinib) block IL-6 signaling downstream of the receptor. These are FDA-approved for various inflammatory conditions and are being explored for:
  - Reducing SASP (JAK inhibitors are senomorphics)
  - Preclinical data shows ruxolitinib improves aged mouse frailty markers
  - JAK inhibitors have significant immunosuppression risks

### Safety of Chronic IL-6 Pathway Inhibition

**Tocilizumab (established safety from RA/GCA use):**
- **Infections:** Increased risk of serious infections (2-5% per year), including opportunistic infections
- **Neutropenia:** Dose-dependent; usually manageable
- **Hepatotoxicity:** Elevated transaminases (monitor LFTs)
- **GI perforation:** Small increased risk (especially with concurrent steroids/NSAIDs)
- **Hyperlipidemia:** Increases LDL cholesterol (paradoxically, without increasing CV events)
- **Immunosuppression:** Impairs acute phase response; can mask symptoms of infection (fever, CRP elevation)
- **Cost:** ~$1,000-2,000/month

**Key safety concern for aging indication:** Chronic immunosuppression in an already immunosenescent elderly population could increase infection risk substantially. This is the primary barrier.

### Key Publications

1. Ferrucci L, Corsi A, Lauretani F, et al. The origins of age-related proinflammatory state. *Blood*. 2005;105(6):2294-2299. DOI: 10.1182/blood-2004-07-2599
2. Maggio M, Guralnik JM, Longo DL, Ferrucci L. Interleukin-6 in aging and chronic disease: a magnificent pathway. *J Gerontol A Biol Sci Med Sci*. 2006;61(6):575-584. DOI: 10.1093/gerona/61.6.575
3. Rose-John S. IL-6 trans-signaling via the soluble IL-6 receptor: importance for the pro-inflammatory activities of IL-6. *Int J Biol Sci*. 2012;8(9):1237-1247. DOI: 10.7150/ijbs.4989
4. Xu M, Tchkonia T, Ding H, et al. JAK inhibition alleviates the cellular senescence-associated secretory phenotype and frailty in old age. *Proc Natl Acad Sci USA*. 2015;112(46):E6301-E6310. DOI: 10.1073/pnas.1515386112

### Controversies

- **Classic vs. trans-signaling:** Blocking all IL-6 signaling (tocilizumab/sarilumab) may throw out the baby with the bathwater -- classic signaling has regenerative and anti-inflammatory roles
- **Correlation vs. causation in humans:** While IL-6 predicts poor outcomes, it may be a marker rather than a driver of aging in some contexts
- **Infection risk in elderly:** The population most likely to benefit from IL-6 blockade (frail elderly) is also most vulnerable to the immunosuppressive side effects
- **Monotherapy limitations:** IL-6 is one of many inflammatory mediators elevated in aging; blocking it alone may be insufficient if upstream drivers (senescent cells, cGAS-STING) persist
- **Cost-effectiveness:** Biological drugs for a widespread condition (aging) face enormous cost barriers

---

## 7.3 Cross-Cutting Analysis: The Inflammaging Network

The two inflammaging targets reviewed (cGAS-STING and IL-6) are part of an interconnected inflammatory network in aging:

```
Aging Hallmarks --> Cytosolic DNA --> cGAS-STING --> NF-kB + IRF3
     |                                                    |
     |                                                    v
     |                                          Type I IFN + IL-6 + TNF-alpha
     |                                                    |
     v                                                    v
Senescent Cells --> SASP (IL-6, IL-8, MCP-1, etc.) --> Tissue dysfunction
     |                                                    |
     v                                                    v
Mitochondrial damage --> mtDNA leak --> cGAS-STING -------> Feedforward loop
```

**Key therapeutic strategy implications:**
1. **Upstream targeting (cGAS-STING)** may be more effective than downstream cytokine blockade
2. **Senolytic therapy** removes the source of SASP (including IL-6)
3. **Combination approaches** (senolytic + STING inhibitor + anti-inflammatory) have theoretical appeal
4. **The most promising near-term approach** may be repurposing NRTIs (lamivudine) to block L1-driven cGAS activation -- cheap, FDA-approved, well-tolerated

---

*Document compiled: February 2025*
*Data currency: Through May 2025 training data*
