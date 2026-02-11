# Group 5: Gene Therapies for Aging

> **Data Source Note:** Compiled from training knowledge through May 2025. Items marked [VERIFY] would benefit from live search confirmation.

---

## 5.1 Telomerase / TERT Gene Therapy

### Mechanism of Action

Telomerase is a reverse transcriptase enzyme that extends telomeres -- the protective TTAGGG repeat sequences capping chromosome ends. The catalytic subunit TERT (telomerase reverse transcriptase) and its RNA template component TERC together constitute the active enzyme.

**Telomere biology and aging:**
1. **Telomere shortening:** Most somatic cells lack telomerase activity. With each cell division, telomeres shorten by 50-200 bp due to the end-replication problem.
2. **Critical shortening trigger:** When telomeres reach a critical length (~5 kb in humans), they trigger DNA damage response (DDR) signaling through ATM/ATR kinases.
3. **Cellular senescence or apoptosis:** DDR activation at critically short telomeres induces p53/p21 and p16/Rb-mediated cell cycle arrest (senescence) or apoptosis.
4. **Tissue dysfunction:** Accumulated senescent cells and depleted stem cell pools contribute to age-related tissue decline.
5. **Telomere-related diseases:** Dyskeratosis congenita, idiopathic pulmonary fibrosis, aplastic anemia -- all caused by mutations affecting telomere maintenance.

**TERT gene therapy rationale:**
- Deliver TERT gene via AAV (adeno-associated virus) to somatic cells
- Transient or sustained TERT expression extends telomeres
- Prevents or reverses telomere-driven senescence and tissue dysfunction
- Does NOT require cell division (TERT has non-canonical functions including mitochondrial protection, Wnt signaling modulation, and gene expression regulation)

### Key Preclinical Results

| Study | Species | Key Finding | Reference |
|-------|---------|-------------|-----------|
| Blasco group 2012 | Mouse | AAV9-TERT gene therapy in 1-year-old (adult) and 2-year-old (aged) mice: extended median lifespan by 24% (adult) and 13% (old); no increase in cancer; improved glucose tolerance, osteoporosis, neuromuscular coordination, multiple aging markers | Bernardes de Jesus B, et al. EMBO Mol Med. 2012;4(8):691-704. DOI: 10.1002/emmm.201200245 |
| Blasco group 2015 | Mouse | AAV9-TERT in aged mice improved cardiac function after MI; reduced cardiac fibrosis and hypertrophy; extended lifespan in the heart disease context | Bar C, et al. EMBO Mol Med. 2014;6(9):1296-1307 [VERIFY year] |
| Blasco group 2019 | Mouse | AAV9-TERT in mouse model of pulmonary fibrosis: reversed fibrosis, improved lung function; relevant to telomere-related lung disease | Povedano JM, et al. eLife. 2018;7:e31299. DOI: 10.7554/eLife.31299 |
| Blasco group 2020 | Mouse | TERT gene therapy in aplastic anemia mouse model restored hematopoiesis | [VERIFY exact citation] |

**Lifespan data:**
- 24% median lifespan extension in 1-year-old mice (AAV9-TERT, single injection)
- 13% median lifespan extension in 2-year-old mice (AAV9-TERT, single injection)
- NO increased cancer incidence -- this is critical because telomerase activation was long feared to promote cancer
- The Blasco lab results are from Maria Blasco's group at CNIO (Spanish National Cancer Research Centre)

### Cancer Risk Analysis

The relationship between telomerase and cancer is complex:

**Arguments for increased cancer risk:**
- ~90% of cancers reactivate telomerase to achieve replicative immortality
- TERT promoter mutations are among the most common non-coding mutations in cancer
- Telomere lengthening could allow pre-malignant cells to avoid senescence checkpoint

**Arguments against (and evidence from gene therapy studies):**
- Blasco's AAV-TERT studies showed no increased cancer incidence
- Telomere shortening itself causes genomic instability (chromosome fusions, breakage-fusion-bridge cycles) that PROMOTES cancer
- The net effect of TERT gene therapy may be cancer-neutral or even cancer-protective
- TERT gene therapy extends telomeres modestly (not to the extreme levels seen in cancer)
- Short telomeres may be a greater cancer risk than moderate telomere lengthening

### Clinical Trial Status (as of early 2025)

**No registered clinical trials for TERT gene therapy for aging as of early 2025.**

**Related developments:**
- **Libella Gene Therapeutics:** A company that claimed to offer TERT gene therapy for aging; generated controversy:
  - Planned a trial in Colombia (to avoid US regulatory oversight)
  - Listed on ClinicalTrials.gov but was criticized for lack of preclinical safety data specific to their construct
  - Regulatory and ethical concerns raised by the aging research community
  - Current status uncertain [VERIFY]

- **BioViva Sciences (Liz Parrish):** CEO Liz Parrish claimed to have self-administered TERT and follistatin gene therapy in 2015 in Colombia. Claims included telomere lengthening (~20 years of telomere "age" reversal) based on HT Q-FISH telomere measurement. This was widely criticized:
  - No peer-reviewed publication
  - Single n=1 subject (the CEO)
  - Telomere length measurement methods questioned
  - No independent verification
  - Ethical concerns about self-experimentation and promotion
  - [VERIFY for any subsequent publications or clinical developments]

- **Telomere therapeutics in disease contexts:** TERT gene therapy approaches are being developed for telomere biology disorders (pulmonary fibrosis, dyskeratosis congenita, aplastic anemia) rather than aging per se:
  - These disease-focused programs provide a regulatory pathway
  - If successful, could eventually be explored for aging

### Safety Considerations

- **Cancer risk:** The primary concern (discussed above); preclinical data is reassuring but limited
- **AAV vector safety:** Standard AAV gene therapy risks (immune response, hepatotoxicity at high doses, potential for insertional mutagenesis with some serotypes)
- **Overexpression risk:** Excessive telomerase activity could theoretically support cancer cell survival
- **Dose control:** Gene therapy provides limited control over expression levels; this is a challenge for a therapy where too much activity could be harmful
- **Durability:** AAV-delivered TERT expression may be transient (episomal) or may persist for years; long-term expression dynamics are not fully characterized

### Key Publications

1. Bernardes de Jesus B, Vera E, Schneeberger K, et al. Telomerase gene therapy in adult and old mice delays aging and increases longevity without increasing cancer. *EMBO Mol Med*. 2012;4(8):691-704. DOI: 10.1002/emmm.201200245
2. Bar C, Blasco MA. Telomeres and telomerase as therapeutic targets to prevent and treat age-related diseases. *F1000Res*. 2016;5:89. DOI: 10.12688/f1000research.7020.1

---

## 5.2 Klotho Gene Therapy / Protein Therapy

### Mechanism of Action

Klotho is a transmembrane protein predominantly expressed in the kidney and brain (choroid plexus). It exists in two forms:

1. **Membrane Klotho:** Transmembrane form that acts as a co-receptor for FGF23 (fibroblast growth factor 23), regulating phosphate homeostasis, vitamin D metabolism, and calcium balance
2. **Soluble Klotho (sKlotho):** The extracellular domain is cleaved by ADAM10/17 metalloproteases and circulates in blood. sKlotho has independent signaling functions:
   - Inhibits insulin/IGF-1 signaling (FoxO activation)
   - Inhibits Wnt signaling (reduces fibrosis, preserves stem cells)
   - Inhibits TGF-beta signaling (anti-fibrotic)
   - Suppresses NF-kB (anti-inflammatory)
   - Reduces oxidative stress (upregulates Nrf2, MnSOD, catalase)
   - Improves endothelial function
   - Modulates calcium channel activity in the brain (NMDA receptors)

**Age-related Klotho decline:**
- Klotho expression and circulating sKlotho levels decline dramatically with age
- Klotho-deficient mice (kl/kl) display accelerated aging: shortened lifespan (~8-9 weeks), arteriosclerosis, osteoporosis, skin atrophy, pulmonary emphysema, cognitive impairment
- Klotho overexpression extends mouse lifespan by ~20-30%

### Key Preclinical Results

| Study | Species | Key Finding | Reference |
|-------|---------|-------------|-----------|
| Kuro-o et al. 1997 | Mouse | Discovery: Klotho-deficient mice show accelerated aging phenotype | Kuro-o M, et al. Nature. 1997;390(6655):45-51. DOI: 10.1038/36285 |
| Kurosu et al. 2005 | Mouse | Klotho overexpression extends mouse lifespan by 20-30%; suppresses insulin/IGF-1 signaling | Kurosu H, et al. Science. 2005;309(5742):1829-33. DOI: 10.1126/science.1112766 |
| Leon et al. 2017 | Mouse | Systemic delivery of sKlotho improved kidney function in aged mice; reduced fibrosis | [VERIFY exact citation] |
| Castner et al. 2023 | Rhesus monkey | Single injection of sKlotho protein improved cognitive function (working memory) in aged non-human primates; effects lasted 2+ weeks | Castner SA, et al. Nat Aging. 2023;3(8):931-937. DOI: 10.1038/s43587-023-00441-x |
| Zeng et al. 2019 | Mouse | AAV-Klotho gene therapy improved cognitive function and reduced neuroinflammation in Alzheimer's mouse model | [VERIFY exact citation] |

**Lifespan data:**
- Klotho overexpression (transgenic): 20-30% median lifespan extension in mice (Kurosu et al. 2005)
- Gene therapy lifespan study: Not yet published [VERIFY]

### Clinical Trial Status (as of early 2025)

**No registered clinical trials for Klotho gene therapy or protein therapy for aging as of early 2025.**

**However, significant translational progress:**
- **Unity Biotechnology** (coincidentally named, different from Klotho biology) and other groups have explored Klotho biology
- **Dena Bhatt's group at UCSF/Stanford** has been developing sKlotho protein therapy for cognitive aging [VERIFY PI name]
- **Castner et al. 2023 Nature Aging paper** (NHP data) is the closest to clinical translation -- demonstrating that a single systemic injection of sKlotho improved working memory in aged monkeys is a strong translational finding

**Challenges for clinical development:**
- Protein therapy: sKlotho is a large protein (~130 kDa); production, stability, and delivery are challenging
- Gene therapy: AAV-Klotho has standard gene therapy delivery challenges
- Target organ: Brain delivery requires crossing the blood-brain barrier (Klotho may be unique in that systemic sKlotho appears to affect brain function, possibly via choroid plexus or indirect signaling)

### 2023-2025 Developments

- **Castner et al. 2023 (Nature Aging):** The NHP cognitive improvement study was the most significant Klotho development. Demonstrating cognitive enhancement in old monkeys with a single protein injection generated excitement for clinical translation.
- Multiple groups working on Klotho delivery optimization (PEGylation, Fc-fusion, AAV, mRNA-LNP) [VERIFY specifics]
- Biomarker studies correlating circulating Klotho levels with aging outcomes in human cohorts [VERIFY]
- Some longevity companies exploring Klotho in their pipelines [VERIFY specific companies]

### Safety Considerations

- **Calcium/phosphate homeostasis:** Klotho is a key regulator of mineral metabolism; systemic administration could disrupt calcium and phosphate balance
- **Hypophosphatemia:** Excessive Klotho could cause dangerously low phosphate levels
- **Bone effects:** Altered mineral metabolism could affect bone density (positively or negatively depending on context)
- **Protein immunogenicity:** Recombinant sKlotho may elicit immune responses with repeated dosing
- **Long-term effects unknown:** No chronic dosing studies in primates

### Key Publications

1. Kuro-o M, Matsumura Y, Aizawa H, et al. Mutation of the mouse klotho gene leads to a syndrome resembling ageing. *Nature*. 1997;390(6655):45-51. DOI: 10.1038/36285
2. Kurosu H, Yamamoto M, Clark JD, et al. Suppression of aging in mice by the hormone Klotho. *Science*. 2005;309(5742):1829-1833. DOI: 10.1126/science.1112766
3. Castner SA, Gupta S, Wang D, et al. Longevity factor klotho enhances cognition in aged nonhuman primates. *Nat Aging*. 2023;3(8):931-937. DOI: 10.1038/s43587-023-00441-x

---

## 5.3 Follistatin Gene Therapy / Rejuvenate Bio

### Mechanism of Action

Follistatin (FST) is a glycoprotein that binds and inhibits members of the TGF-beta superfamily, primarily:

1. **Myostatin (GDF-8) inhibition:** Myostatin is a negative regulator of skeletal muscle growth. Follistatin's neutralization of myostatin promotes:
   - Muscle hypertrophy
   - Increased muscle mass and strength
   - Improved muscle regeneration
   - Resistance to age-related sarcopenia

2. **Activin A/B inhibition:** Activins promote fibrosis, inflammation, and muscle wasting. Follistatin neutralization:
   - Reduces tissue fibrosis (heart, liver, kidney, lung)
   - Reduces inflammation
   - Improves metabolic health
   - May reduce cellular senescence (activin A is a SASP factor)

3. **GDF-11 modulation:** Follistatin can bind GDF-11 (a controversial "rejuvenation factor" from parabiosis studies); the net effect of GDF-11 modulation is debated.

**Anti-aging rationale:**
- Sarcopenia (age-related muscle loss) is a major driver of frailty and disability
- Age-related fibrosis (heart, kidney, liver, lung) drives organ dysfunction
- Activin levels increase with age and contribute to inflammaging
- Follistatin gene therapy could simultaneously combat sarcopenia AND organ fibrosis

### Rejuvenate Bio

- **Founded:** 2017
- **Headquarters:** San Diego, CA [VERIFY]
- **Key founders:** George Church (Harvard geneticist), Daniel Oliver (CEO), Noah Davidsohn
- **Core technology:** AAV-based gene therapy delivering multiple longevity genes simultaneously
- **Approach:** "Combination gene therapy" -- co-delivering multiple therapeutic transgenes (e.g., follistatin + TERT + Klotho + sFLT1) in a single treatment

**Key results from Rejuvenate Bio:**

| Study | Species | Key Finding | Reference |
|-------|---------|-------------|-----------|
| Davidsohn et al. 2019 | Mouse | AAV combination gene therapy (follistatin + sFLT1 + TERT or Klotho) in aged mice improved cardiac function, reduced fibrosis, improved metabolic parameters; certain combinations extended lifespan; follistatin was a key component | Davidsohn N, et al. (preprint/presentation) [VERIFY for peer-reviewed publication] |
| Rejuvenate Bio dog study | Dog | Gene therapy in aged dogs (companion animals) to test safety and efficacy of follistatin-based approach | [VERIFY for publication status] |

### Clinical/Translational Status (as of early 2025)

- **Dog trials:** Rejuvenate Bio reported conducting gene therapy in aged companion dogs, with results showing improved cardiac function and biomarkers [VERIFY for published data and specific outcomes]
- **No human clinical trials** registered as of early 2025
- **Regulatory pathway:** Gene therapy regulatory requirements are extensive; IND filing would require substantial preclinical safety and manufacturing data
- The company's strategy appears to be: dogs first (less regulatory burden, proof of concept) then humans

### 2023-2025 Developments

- Rejuvenate Bio is one of the few companies pursuing multi-gene longevity therapy
- George Church's involvement provides significant academic credibility and media attention
- The concept of treating aging as a "gene therapy indication" is being explored
- Competition from other follistatin approaches:
  - **Myostatin antibodies/inhibitors** are in clinical development for sarcopenia (e.g., bimagrumab, though Phase 3 results have been mixed)
  - **Anti-activin approaches** (e.g., sotatercept for PAH) validate the pathway

### Safety Considerations

- **Muscle hypertrophy risks:** Excessive muscle growth could stress the cardiovascular system; cardiac hypertrophy if heart muscle is affected
- **AAV gene therapy risks:** Standard risks (immune response, hepatotoxicity, potential insertional mutagenesis)
- **Reproductive effects:** Follistatin plays roles in reproductive biology; systemic gene therapy could affect fertility
- **Irreversibility:** Gene therapy is difficult to "turn off" if adverse effects emerge
- **Myostatin inhibition concerns:** Complete myostatin inhibition causes tendon weakness (tendons don't hypertrophy proportionally to muscle); potential for injury

### Key Publications

1. Haidet AM, Rizo L, Handy C, et al. Long-term enhancement of skeletal muscle mass and strength by single gene administration of myostatin inhibitors. *Proc Natl Acad Sci USA*. 2008;105(11):4318-4322. DOI: 10.1073/pnas.0709144105
2. Davidsohn N, Pezone M, Vernet A, et al. A single combination gene therapy treats multiple age-related diseases. *Proc Natl Acad Sci USA*. 2019;116(47):23505-23511. DOI: 10.1073/pnas.1906073116 [VERIFY exact citation details]

---

## 5.4 SIRT6 Overexpression

### Mechanism of Action

SIRT6 is a NAD+-dependent histone deacetylase (sirtuin family member) with multiple roles in genome maintenance, metabolism, and longevity:

1. **DNA repair:** SIRT6 is recruited to DNA double-strand breaks (DSBs) where it:
   - Deacetylates H3K9ac and H3K56ac, promoting chromatin compaction for repair
   - Recruits SNF2H (chromatin remodeler) and DNA-PKcs for NHEJ repair
   - Activates PARP1 for break signaling
   - Promotes HR repair pathway

2. **Telomere maintenance:** SIRT6 deacetylates H3K9 and H3K56 at telomeres, maintaining telomeric chromatin structure and preventing telomere dysfunction

3. **Metabolic regulation:**
   - Suppresses glucose uptake by deacetylating H3K9 at HIF-1alpha target gene promoters (reduces Warburg effect)
   - Promotes fatty acid oxidation
   - Regulates gluconeogenesis
   - Functions as a tumor suppressor by limiting glycolytic metabolism

4. **Anti-inflammatory:** Deacetylates H3K9 at NF-kB target gene promoters, reducing inflammatory gene expression (TNF-alpha, IL-6, IL-8)

5. **LINE-1 retrotransposon silencing:** SIRT6 represses LINE-1 retrotransposable elements through H3K18 deacetylation; age-related SIRT6 decline may lead to LINE-1 derepression and genomic instability

### Key Preclinical Results

| Study | Species | Key Finding | Reference |
|-------|---------|-------------|-----------|
| Kanfi et al. 2012 | Mouse | SIRT6 overexpression extended median lifespan by 15.8% in MALE mice; NO lifespan extension in females; effect mediated by reduced IGF-1 signaling | Kanfi Y, et al. Nature. 2012;483(7388):218-21. DOI: 10.1038/nature10815 |
| Tian et al. 2019 | Mouse + Human cells | SIRT6 identified as key longevity factor in long-lived species (bowhead whale, naked mole rat); more efficient DNA repair associated with higher SIRT6 activity | Tian X, et al. Cell. 2019;177(3):622-638.e22. DOI: 10.1016/j.cell.2019.03.043 |
| Roichman et al. 2021 | Mouse | SIRT6 overexpression in both male AND female mice extended lifespan when using a centromeric SIRT6 transgene (correcting the sex-specific limitation of earlier work); improved frailty markers | Roichman A, et al. Nat Commun. 2021;12(1):3329. DOI: 10.1038/s41467-021-23545-7 |
| Mostoslavsky et al. 2006 | Mouse | SIRT6 knockout mice die within 4 weeks; exhibit genomic instability, metabolic defects, progeria-like phenotype | Mostoslavsky R, et al. Cell. 2006;124(2):315-29. DOI: 10.1016/j.cell.2005.11.044 |
| Simon et al. 2022 | Mouse | SIRT6 activators (small molecules like MDL-800) improved DNA repair and metabolic health in aged mice | [VERIFY exact citation] |

**Lifespan data:**
- SIRT6 overexpression: 15.8% median lifespan extension in male mice (Kanfi 2012)
- Later studies showed extension in both sexes with appropriate transgene design (Roichman 2021)
- SIRT6 knockout: Dramatic lifespan shortening (~4 weeks), confirming its essential role

### Clinical/Translational Status

- **No clinical trials** for SIRT6 gene therapy or activation for aging as of early 2025
- **SIRT6 activators (small molecules):**
  - MDL-800: A SIRT6-specific activator identified through high-throughput screening; shown to enhance DNA repair and reduce cancer cell viability in preclinical studies
  - Fluvastatin, fucoidan, and cyanidin have been reported as weak SIRT6 activators
  - No SIRT6-specific activator has entered clinical trials
- **Companies:** No publicly known company specifically focused on SIRT6 for longevity [VERIFY]

### 2023-2025 Developments

- The Tian et al. 2019 comparative biology study (showing SIRT6 correlates with species longevity) generated interest in SIRT6 as a longevity target
- Discovery of more potent and specific SIRT6 activators in academic labs [VERIFY]
- Understanding of SIRT6's role in LINE-1 retrotransposon silencing has deepened, connecting SIRT6 biology to the "genomic instability" hallmark of aging
- SIRT6 as a drug target has been explored by some computational/AI drug discovery companies [VERIFY]

### Safety Considerations

- **Gene therapy approach:** Standard AAV risks; SIRT6 is a nuclear protein requiring efficient nuclear delivery
- **Metabolic effects:** SIRT6 overexpression suppresses glycolysis; could cause hypoglycemia in fasting states
- **Sex-specific effects:** The sex-specificity of lifespan effects (initially males only) raises questions about safety/efficacy balance in females
- **Cancer implications:** SIRT6 generally acts as a tumor suppressor; overexpression may be cancer-protective rather than cancer-promoting (favorable safety signal)
- **Small-molecule SIRT6 activators:** Specificity within the sirtuin family is challenging; off-target activation of other sirtuins or unrelated enzymes possible

### Key Publications

1. Kanfi Y, Naiman S, Amir G, et al. The sirtuin SIRT6 regulates lifespan in male mice. *Nature*. 2012;483(7388):218-221. DOI: 10.1038/nature10815
2. Tian X, Firsanov D, Zhang Z, et al. SIRT6 is responsible for more efficient DNA double-strand break repair in long-lived species. *Cell*. 2019;177(3):622-638.e22. DOI: 10.1016/j.cell.2019.03.043
3. Roichman A, Elhanati S, Aon MA, et al. Restoration of energy homeostasis by SIRT6 extends healthy lifespan. *Nat Commun*. 2021;12(1):3329. DOI: 10.1038/s41467-021-23545-7
4. Mostoslavsky R, Chua KF, Lombard DB, et al. Genomic instability and aging-like phenotype in the absence of mammalian SIRT6. *Cell*. 2006;124(2):315-329. DOI: 10.1016/j.cell.2005.11.044

---

*Document compiled: February 2025*
*Data currency: Through May 2025 training data*
