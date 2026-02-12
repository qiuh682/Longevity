# Longevity Research Tracker

Comprehensive longevity science knowledge base covering the 2023-2025 research landscape: 12 hallmarks of aging, therapeutic interventions, biomarkers, clinical trials, industry landscape, and an interactive D3.js mindmap.

## Interactive Mindmap

Open `longevity_mindmap.html` in any modern browser for an interactive radial tree visualization of the entire knowledge base.

- 6 color-coded branches with 100+ data nodes
- Click to expand/collapse, hover for detailed tooltips
- Zoom (scroll) and pan (drag) navigation
- Key data points: lifespan extension %, trial results, funding amounts

## Project Structure

```
Longevity/
├── longevity_mindmap.html              # Interactive D3.js radial mindmap
├── longevity_research_review.md        # Full research review (1,696 lines)
├── longevity-research-tracker-prompts.md  # 3-phase prompt methodology
│
├── research_notes/                     # Phase 1: Raw research findings
│   ├── hallmarks_findings.md           # 12 Hallmarks of Aging (comprehensive)
│   ├── hallmarks_first_six_detailed.md # Detailed analysis of hallmarks 1-6
│   ├── biomarkers_clocks.md            # Epigenetic, proteomic & functional clocks
│   ├── clinical_trials.md              # 33+ clinical trials catalog
│   ├── companies_landscape.md          # 25+ company profiles
│   ├── compounds_data.md               # Intervention mechanisms & evidence
│   ├── key_publications.md             # Key citations & references
│   ├── group1_epigenetic_reprogramming.md
│   ├── group2_glp1_agonists.md
│   ├── group3_mitochondrial_therapies.md
│   ├── group4_emerging_interventions.md
│   ├── group5_gene_therapies.md
│   ├── group6_plasma_young_blood.md
│   └── group7_inflammaging_targets.md
│
├── longevity_database/                 # Phase 2: Structured CSV databases
│   ├── README_database.md              # Schema documentation
│   ├── interventions_database.csv      # 33 compounds with mechanisms & evidence
│   ├── clinical_trials_database.csv    # 44 trials with NCT numbers & results
│   ├── companies_database.csv          # 33 companies with funding & pipelines
│   ├── biomarkers_database.csv         # 25 aging biomarkers & clocks
│   └── publications_database.csv       # 66 key publications with citations
│
└── review_parts/                       # Phase 3: Sectioned review drafts
    ├── sections_1_3.md
    ├── sections_4_5.md
    └── sections_6_10.md
```

## Coverage

### 12 Hallmarks of Aging

Genomic instability, telomere attrition, epigenetic alterations, loss of proteostasis, disabled macroautophagy, deregulated nutrient-sensing, mitochondrial dysfunction, cellular senescence, stem cell exhaustion, altered intercellular communication, chronic inflammation, and dysbiosis.

### Therapeutic Interventions (8 categories)

| Category | Key Compounds | Best Preclinical Result |
|----------|--------------|----------------------|
| Senolytics | D+Q, fisetin, UBX1325, navitoclax | ~36% remaining lifespan (D+Q) |
| mTOR Inhibitors | Rapamycin, everolimus, acarbose | 36.6% median lifespan (rapa+acarbose) |
| NAD+ Precursors | NMN, NR, CD38 inhibitors | NAD+ restoration, mixed clinical |
| GLP-1 Agonists | Semaglutide, tirzepatide | Epigenetic age reversal: GrimAge -3.1y |
| Epigenetic Reprogramming | OSK factors, SB000, chemical | 109% remaining lifespan (OSK) |
| Mitochondrial | Urolithin A, elamipretide | 12% muscle strength; FDA approval |
| Gene Therapy | Klotho, follistatin, SIRT6, TERT | 19.7-30% lifespan extension |
| Emerging | Taurine, GlyNAC, AKG, spermidine | 10-25% lifespan (taurine) |

### Biomarkers & Aging Clocks

- **1st generation:** Horvath (2013), Hannum (2013)
- **2nd generation:** PhenoAge (2018), GrimAge (2019)
- **3rd generation:** DunedinPACE (2022) - measures rate of aging
- **Proteomic:** Organ-specific clocks (Oh et al. 2023), GDF-15
- **Commercial:** TruDiagnostic, Elysium, Tally Health, GlycanAge

### Clinical Trials

33+ trials across 11 intervention classes. Key results include PEARL (rapamycin), ASPIRE (UBX1325, +5.6 letters in NEJM Evidence), MitoImmune (Urolithin A, Nature Aging 2025), and TAME (metformin, pending).

### Industry Landscape

$8B+ invested across 25+ companies. Major players: Altos Labs ($3B), Retro Biosciences ($1B), Calico (Alphabet), Unity Biotechnology, Insilico Medicine. Pharma partnerships: AbbVie-Calico ($1.5B+), Novartis-BioAge, Lilly-BioAge.

## Data Sources

- Peer-reviewed publications (Cell, Nature, Science, NEJM Evidence, Nature Aging, PNAS)
- ClinicalTrials.gov registrations
- Company disclosures and SEC filings
- Conference presentations (ASCO, ASH)
- Preprint servers (bioRxiv, medRxiv)

Evidence currency: through early 2025.

## Methodology

This project was built in 3 phases using Claude Code:

1. **Research & Data Collection** - Systematic search across 12 hallmarks, 8 intervention categories, biomarkers, trials, and companies
2. **Database Construction** - Structured CSV databases with standardized schemas
3. **Synthesis & Visualization** - Comprehensive review document and interactive D3.js mindmap

See `longevity-research-tracker-prompts.md` for the full prompt methodology.

## License

This is a research compilation for educational and informational purposes. All cited works belong to their respective authors and publishers.
