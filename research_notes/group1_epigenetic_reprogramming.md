# Group 1: Epigenetic Reprogramming

> **Data Source Note:** Compiled from training knowledge through May 2025. WebSearch/WebFetch were unavailable. Items marked [VERIFY] would benefit from live search confirmation.

---

## 1.1 Yamanaka Factors (OSKM/OSK) -- Partial Reprogramming

### Mechanism of Action

Partial cellular reprogramming uses transient expression of Yamanaka factors -- Oct4 (O), Sox2 (S), Klf4 (K), and optionally c-Myc (M) -- to reverse epigenetic age without fully dedifferentiating cells back to a pluripotent state.

**Detailed mechanism:**

1. **Full reprogramming (iPSC generation):** Continuous OSKM expression over 2-4 weeks converts somatic cells to induced pluripotent stem cells (iPSCs), erasing cellular identity entirely. This resets the epigenetic clock to near-zero but destroys tissue function.

2. **Partial reprogramming:** Brief, cyclic expression of OSKM (or OSK without c-Myc) for shorter durations (2-7 days on, 2-3 weeks off) reverses age-associated epigenetic marks without losing cell identity. Key epigenetic changes include:
   - Reversal of age-related DNA methylation patterns (CpG sites measured by epigenetic clocks)
   - Restoration of histone modification patterns (H3K9me3, H3K27me3) to younger states
   - Re-establishment of heterochromatin architecture
   - Restoration of nuclear lamina integrity (lamin B1 expression)
   - Improvement of transcriptomic profiles toward younger signatures

3. **OSK (without c-Myc):** Many groups prefer the three-factor OSK cocktail because c-Myc is a potent oncogene that significantly increases tumorigenesis risk. David Sinclair's lab demonstrated that OSK alone is sufficient for age reversal in multiple tissues.

4. **Molecular targets of partial reprogramming:**
   - **TET enzymes:** Reprogramming factors activate TET1/2 demethylases, which remove aberrant age-related DNA methylation
   - **Polycomb repressive complexes:** PRC1/PRC2 are remodeled, restoring youthful heterochromatin
   - **Pioneer factor activity:** Oct4 and Sox2 act as pioneer factors, accessing closed chromatin and initiating epigenetic remodeling
   - **Metabolic reprogramming:** Transient shift from oxidative phosphorylation to glycolysis during reprogramming may contribute to mitochondrial rejuvenation

### Key Preclinical Results

| Study | Species | Key Finding | Reference |
|-------|---------|-------------|-----------|
| Ocampo et al. 2016 | Mouse (progeria + WT) | First in vivo partial reprogramming; cyclic OSKM (doxycycline-inducible, 2 days on / 5 days off) in progeroid mice extended lifespan by ~33%; in wild-type aged mice, improved tissue regeneration | Ocampo A, et al. Cell. 2016;167(7):1719-1733.e12. DOI: 10.1016/j.cell.2016.11.052 |
| Lu et al. 2020 | Mouse | OSK expression in retinal ganglion cells restored youthful DNA methylation patterns and regenerated axons after optic nerve crush; reversed glaucoma-related vision loss in aged mice | Lu Y, et al. Nature. 2020;588(7836):124-129. DOI: 10.1038/s41586-020-2975-4 |
| Browder et al. 2022 | Mouse | Long-term partial reprogramming (OSKM, 7 months of cyclic expression) in aged wild-type mice rejuvenated skin, kidney, and reduced epigenetic age without increased cancer; no teratoma formation | Browder KC, et al. Nat Aging. 2022;2(3):243-253. DOI: 10.1038/s43587-022-00183-2 |
| Chondronasiou et al. 2022 | Mouse | Multi-tissue analysis of in vivo reprogramming showed tissue-specific responses; some tissues more amenable to rejuvenation than others | Chondronasiou D, et al. Nat Aging. 2022;2(12):1165-1175 |
| Yang et al. 2023 | Mouse | Loss of epigenetic information (through induced DSBs without mutations) accelerates aging; restoration via OSK reverses these changes; published as the "Information Theory of Aging" | Yang JH, et al. Cell. 2023;186(2):305-326.e27. DOI: 10.1016/j.cell.2022.12.027 |
| Macip et al. 2024 | Mouse | Gene therapy delivery of OSK factors via AAV in aged mice improved multiple age-related phenotypes; extended remaining lifespan [VERIFY exact results] | Macip CC, et al. [VERIFY publication details -- preprint/publication 2024] |

**Lifespan data:**
- Ocampo et al. 2016: ~33% lifespan extension in progeroid (LAKI) mice with cyclic OSKM
- Browder et al. 2022: Rejuvenation without lifespan measurement (healthspan study)
- Wild-type mouse lifespan extension with partial reprogramming has been reported but not yet robustly replicated across independent labs [VERIFY for 2024-2025 publications]

### Clinical Trial Status (as of early 2025)

**No human clinical trials of Yamanaka factor-based reprogramming have been registered on ClinicalTrials.gov as of early 2025.**

The technology remains preclinical due to:
- Safety concerns (teratoma risk, oncogenesis from c-Myc and Oct4)
- Delivery challenges (how to transiently express transcription factors in human tissues safely)
- Dosing/timing unknowns (optimal cycle length, duration, tissue specificity)

**Regulatory pathway:** No established regulatory framework for epigenetic reprogramming therapies. The FDA would likely classify these as gene therapies (if viral delivery) or biologics.

### Safety Profile

**Major risks:**
- **Teratoma formation:** Overexpression or prolonged expression of OSKM can induce pluripotency and teratoma formation. The Ocampo et al. 2016 study showed that continuous (non-cyclic) expression caused teratomas and death in mice.
- **Oncogenesis:** c-Myc is a well-characterized oncogene; Oct4 can also promote tumor formation. OSK (without c-Myc) has a better safety profile but is not risk-free.
- **Tissue dysfunction:** Excessive reprogramming could disrupt tissue function by dedifferentiating critical cell types (e.g., cardiomyocytes, neurons)
- **Off-target effects:** Systemic delivery could affect tissues where reprogramming is undesirable
- **Epigenetic instability:** Repeated cycling of reprogramming factors could introduce epigenetic errors

**Mitigation strategies being explored:**
- OSK instead of OSKM (removing c-Myc)
- Tightly controlled inducible expression systems (Tet-ON/OFF)
- Tissue-specific promoters limiting expression to target tissues
- Short, pulsed expression protocols
- Chemical reprogramming alternatives (see Section 1.5)
- mRNA delivery (transient, no genomic integration risk)

### Key Publications

1. Ocampo A, Reddy P, Martinez-Redondo P, et al. In vivo amelioration of age-associated hallmarks by partial reprogramming. *Cell*. 2016;167(7):1719-1733.e12. DOI: 10.1016/j.cell.2016.11.052
2. Lu Y, Brommer B, Tian X, et al. Reprogramming to recover youthful epigenetic information and restore vision. *Nature*. 2020;588(7836):124-129. DOI: 10.1038/s41586-020-2975-4
3. Browder KC, Reddy P, Wang M, et al. In vivo partial reprogramming alters age-associated molecular changes during physiological aging in mice. *Nat Aging*. 2022;2(3):243-253. DOI: 10.1038/s43587-022-00183-2
4. Yang JH, Hayano M, Griffin PT, et al. Loss of epigenetic information as a cause of mammalian aging. *Cell*. 2023;186(2):305-326.e27. DOI: 10.1016/j.cell.2022.12.027
5. Gill D, Parry A, Santos F, et al. Multi-omic rejuvenation of human cells by maturation phase transient reprogramming. *eLife*. 2022;11:e71624. DOI: 10.7554/eLife.71624

### Controversies and Negative Results

- **Reproducibility concerns:** The Yang et al. 2023 "Information Theory of Aging" paper generated significant debate. Some researchers questioned whether the ICE (Inducible Changes to the Epigenome) mouse model truly separates epigenetic from genetic contributions to aging.
- **c-Myc toxicity:** Several labs have reported significant adverse effects when c-Myc is included, even with cyclic protocols
- **Tissue-specific variability:** Not all tissues respond equally to reprogramming; some (like the brain) may be resistant or require different approaches
- **Delivery challenge is unsolved:** No safe, effective method exists for systemically delivering transcription factors to humans with appropriate temporal control
- **David Sinclair's claims have been controversial:** His promotion of reprogramming as "curing aging" and commercial interests (Life Biosciences) have drawn criticism from some in the field

---

## 1.2 Altos Labs

### Company Profile

- **Founded:** 2022 (announced January 2022)
- **Headquarters:** San Diego, CA; San Francisco Bay Area; Cambridge, UK; Tokyo, Japan
- **Funding:** $3 billion initial funding -- the largest single investment in longevity/aging research history
- **Key investors:** Yuri Milner (primary), Jeff Bezos, other undisclosed investors
- **Structure:** For-profit research institution (not typical biotech structure)

### Scientific Leadership

- **CEO:** Hal Barron (former CSO of GlaxoSmithKline)
- **Key scientists recruited:**
  - Shinya Yamanaka (Nobel laureate, Yamanaka factors discoverer) -- Scientific Advisory Board
  - Juan Carlos Izpisua Belmonte (Salk Institute, Ocampo et al. 2016 senior author)
  - Steve Horvath (epigenetic clock inventor)
  - Wolf Reik (epigenetics, Babraham Institute)
  - Manuel Serrano (senescence/reprogramming, IRB Barcelona)
  - Jennifer Doudna (CRISPR co-inventor) -- Advisory Board
  - Jan Karlseder (telomere biology)
  - Peter Walter (proteostasis, ISRIB co-discoverer)

### Core Technology / Approach

Altos Labs is pursuing **cellular rejuvenation programming** -- a term they use to encompass:

1. **Partial reprogramming:** Optimizing Yamanaka factor-based epigenetic rejuvenation
2. **Epigenetic clock development:** Using Horvath's expertise to measure and validate rejuvenation
3. **Mechanistic understanding:** Dissecting the molecular pathways that mediate epigenetic rejuvenation vs. dedifferentiation
4. **Drug discovery:** Identifying small molecules, gene therapies, or biologics that can achieve controlled rejuvenation
5. **Safety engineering:** Developing approaches to separate rejuvenation from tumorigenesis risk

### 2023-2025 Developments

- Altos has been notably secretive about specific results, publishing limited data
- The company operates more like a research institute than a typical biotech, with a long-term (10+ year) development horizon
- Multiple publications from Altos scientists in top journals, though mostly basic research rather than therapeutic pipeline updates
- Estimated burn rate suggests the $3B funding provides ~10 years of runway at current spending
- No clinical candidates have been publicly disclosed as of early 2025 [VERIFY]
- Some reports suggest internal focus has shifted toward understanding the fundamental biology before rushing to therapeutics

### Key Publications from Altos Scientists (post-founding)

1. Roux E, et al. (Altos Labs team). Various publications on epigenetic reprogramming mechanisms [VERIFY specific publications]
2. Horvath S. Continued epigenetic clock development work [VERIFY specific Altos-affiliated publications]

### Criticisms

- **"Brain drain" criticism:** Altos recruited many top aging researchers from academia, raising concerns about loss of basic research talent from universities
- **Secrecy:** Limited public disclosure of results despite enormous funding
- **Timeline uncertainty:** No clear path to clinical products; investors may face very long timelines
- **Hype vs. substance debate:** Some researchers feel the $3B valuation is premature given the early stage of reprogramming technology

---

## 1.3 Turn Biotechnologies

### Company Profile

- **Founded:** 2018 (Stanford spin-out)
- **Headquarters:** Mountain View, CA
- **Funding:** ~$60M+ total raised [VERIFY for latest rounds]
- **Key founders:** Vittorio Bhardwaj (CEO), Jay Sarkar, based on research from Stanford
- **Core technology:** ERA (Epigenetic Reprogramming of Aging) platform

### Core Technology

Turn Bio's ERA platform uses **mRNA-based transient expression** of Yamanaka factors (OSKM or subsets) to achieve epigenetic rejuvenation:

1. **mRNA delivery:** Unlike viral vectors (AAV), mRNA is transient by nature -- it degrades within days, providing built-in safety against prolonged expression
2. **Lipid nanoparticle (LNP) formulation:** mRNA is encapsulated in LNPs for cellular delivery
3. **Optimized factor cocktails:** Turn Bio has developed proprietary combinations and ratios of reprogramming factors optimized for rejuvenation without dedifferentiation
4. **Tissue-specific targeting:** LNP formulations can be modified for different tissue targets

### Pipeline and Indications

- **Skin rejuvenation (lead program):** Topical mRNA-LNP formulation for skin aging
  - Preclinical data showed reversal of age-related epigenetic marks in human skin cells
  - Improved collagen production, reduced senescence markers
  - Phase 1 trial for skin aging may have been planned [VERIFY for IND/trial status]
- **Osteoarthritis:** mRNA reprogramming of aged chondrocytes
- **Muscle degeneration:** Rejuvenation of aged muscle stem cells (satellite cells)
- **Ophthalmology:** Eye-specific reprogramming (following Sinclair lab retinal work)

### 2023-2025 Developments

- Turn Bio published data on mRNA-based partial reprogramming of human cells showing epigenetic age reversal measured by Horvath clock [VERIFY specific publications]
- The mRNA approach gained credibility after COVID-19 mRNA vaccine success demonstrated LNP-mRNA delivery at scale
- Company reportedly advanced toward IND-enabling studies [VERIFY]
- Key advantage: mRNA degradation provides inherent safety ceiling that viral approaches lack

---

## 1.4 Life Biosciences / Retro Biosciences

### Life Biosciences

- **Founded:** 2017 by David Sinclair
- **Headquarters:** Boston, MA
- **Funding:** ~$100M+ raised
- **Approach:** Portfolio model -- Life Biosciences created multiple subsidiary companies ("daughter companies") each targeting a different hallmark of aging:
  - **Iduna:** Epigenetic reprogramming
  - **Selphagy:** Autophagy modulation
  - **Senolytic Therapeutics:** Senescent cell clearance
  - **Continuum Biosciences:** Stem cell exhaustion
  - **Animal Biosciences:** Veterinary longevity (companion animals)
  - Others

- **2023-2025 status:** Life Biosciences has undergone strategic restructuring. Some daughter companies have been consolidated or shut down. The company has focused more narrowly on its most promising programs. Sinclair's involvement and conflicts of interest have been a persistent topic of discussion. [VERIFY current operational status]

### Retro Biosciences

- **Founded:** 2021
- **Headquarters:** Redwood City, CA
- **Funding:** $180M from Sam Altman (CEO of OpenAI) -- single largest individual investment in a longevity company
- **CEO:** Joe Betts-LaCroix
- **Mission:** Add 10 healthy years to human lifespan

**Three core programs:**

1. **Partial reprogramming / epigenetic rejuvenation:**
   - Developing in vivo reprogramming approaches
   - Working on AAV and non-viral delivery of reprogramming factors
   - Exploring both genetic and chemical reprogramming

2. **Autophagy modulation:**
   - Developing small molecules to enhance autophagy
   - Targeting age-related decline in autophagic flux

3. **Plasma-inspired therapies:**
   - Based on parabiosis / young blood research
   - Identifying and producing specific rejuvenating blood factors
   - Developing recombinant protein therapies

**2023-2025 developments:**
- Retro Bio has been more open about its research approach than Altos Labs
- Published preprints on reprogramming optimization [VERIFY specific publications]
- Actively recruiting from top aging labs
- The Sam Altman backing gives the company significant visibility and credibility in the tech/longevity intersection
- No clinical candidates publicly disclosed as of early 2025 [VERIFY]

---

## 1.5 Chemical Reprogramming

### Overview

Chemical reprogramming refers to the use of small-molecule cocktails (instead of transcription factors) to achieve cellular reprogramming or rejuvenation. This approach avoids the safety risks of gene delivery (viral integration, oncogene expression) entirely.

### Mechanism of Action

Chemical cocktails typically target:
1. **Epigenetic modifiers:** HDAC inhibitors (valproic acid, sodium butyrate), DNA methyltransferase inhibitors (RG108), histone demethylase inhibitors
2. **Signaling pathway modulators:** GSK3 inhibitors (CHIR99021), MEK inhibitors (PD0325901), TGF-beta inhibitors (RepSox, A-83-01)
3. **Metabolic modulators:** Forskolin (adenylate cyclase activator), DZNep (SAH hydrolase inhibitor)
4. **Stress response activators:** Various compounds that activate cellular stress responses mimicking aspects of reprogramming

### Key Preclinical Results

| Study | Key Finding | Reference |
|-------|-------------|-----------|
| Hou et al. 2013 | First complete chemical reprogramming of mouse somatic cells to iPSCs using a cocktail of 7 small molecules (VPA, CHIR, E616452, tranylcypromine, forskolin, DZNep, TTNPB) | Hou P, et al. Science. 2013;341(6146):651-4. DOI: 10.1126/science.1239278 |
| Guan et al. 2022 | Chemical reprogramming of human somatic cells to pluripotency using an 11-compound cocktail; first demonstration in human cells | Guan J, et al. Nature. 2022;605(7909):325-331. DOI: 10.1038/s41586-022-04593-5 |
| Yang et al. 2023 (Harvard) | Identified chemical cocktails (6 combinations of 2-4 molecules) that reverse cellular aging in human cells measured by transcriptomic and epigenetic age; cocktails included combinations of valproic acid, tranylcypromine, CHIR99021, RepSox, and others | Yang JH, et al. Aging. 2023;15(14):6834-6856. DOI: 10.18632/aging.204896 |
| Mitchell et al. 2024 | Chemical cocktails reversed age-related gene expression in aged mouse tissues in vivo [VERIFY -- this was reported in 2023-2024 from Sinclair's lab] | [VERIFY publication details] |

### 2023-2025 Developments

- **David Sinclair's chemical cocktails (July 2023):** Sinclair's group published a widely publicized study identifying chemical cocktails that reverse transcriptomic age in human cells (Yang et al. Aging 2023). The paper received significant media attention but also criticism:
  - The study measured primarily transcriptomic rather than epigenetic (DNA methylation) age reversal
  - Effect sizes were modest
  - In vivo validation was limited
  - The "chemical alternative to genetic reprogramming" claim was considered oversold by some researchers

- **Chinese groups advancing chemical reprogramming:** Deng Hongkui's lab at Peking University (Guan et al. 2022 Nature) continues to lead in chemical reprogramming to pluripotency, which could eventually be adapted for partial rejuvenation

- **Challenges specific to chemical reprogramming for aging:**
  - Cocktails are complex (6-11 compounds) with potential for drug-drug interactions
  - Dose optimization for each compound in combination is extremely challenging
  - Tissue penetration and bioavailability of all components simultaneously is difficult
  - Selectivity for epigenetic rejuvenation vs. uncontrolled reprogramming is not guaranteed with small molecules that have pleiotropic effects

### Safety Considerations

- **Theoretical advantages:** No genetic modification, no viral vectors, transient drug exposure, dose-titratable
- **Theoretical risks:** Off-target epigenetic changes, uncontrolled reprogramming, complex polypharmacy interactions, individual variation in drug metabolism
- **No clinical safety data** for anti-aging chemical reprogramming cocktails

### Key Publications

1. Hou P, Li Y, Zhang X, et al. Pluripotent stem cells induced from mouse somatic cells by small-molecule compounds. *Science*. 2013;341(6146):651-654. DOI: 10.1126/science.1239278
2. Guan J, Wang G, Wang J, et al. Chemical reprogramming of human somatic cells to pluripotent stem cells. *Nature*. 2022;605(7909):325-331. DOI: 10.1038/s41586-022-04593-5
3. Yang JH, Petty CA, Dixon-McDougall T, et al. Chemically induced reprogramming to reverse cellular aging. *Aging*. 2023;15(14):6834-6856. DOI: 10.18632/aging.204896

### Controversies

- Sinclair's chemical cocktail paper received substantial criticism for overstated claims
- The distinction between "rejuvenation" and "transcriptomic change" is important -- not all gene expression changes represent genuine age reversal
- Reproducibility across labs has not been fully established
- Commercial interests (Sinclair's Life Biosciences has chemical reprogramming assets) create conflict of interest concerns

---

*Document compiled: February 2025*
*Data currency: Through May 2025 training data*
