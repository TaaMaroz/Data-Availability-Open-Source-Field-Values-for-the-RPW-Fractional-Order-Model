# Data Availability — Open-Source Field Values for the RPW Fractional-Order Model

<p align="center">
  <img src="Figure_1_map.tif"
       alt="Reported palm and infestation values on the UAE map"
       width="100%">
</p>

<p align="center">
  <em>Figure 1.</em> Reported palm and infestation values across the
  UAE (a), regional share of palms (b), and key reported values (c).
</p>

This document lists all numerical values used in the model that are traceable to publicly available online reports, field surveys, and peer-reviewed literature. It is provided to support the Data Availability Statement of the manuscript *"A Fractional-Order Model for Red Palm Weevil Infestation Dynamics with Global Stability Analysis and Field Validation"* and to enable independent verification and reuse.

All sources are open-access or publicly accessible reports. Where a value is derived rather than directly reported, this is stated explicitly.

---

## 1. 1994/95 Al Ain Field Survey Data

| Quantity | Value | Source | Notes |
|---|---|---|---|
| Total date palm trees surveyed | 1,108,723 | El Ezaby et al., *Integrated Pest Management for the Control of Red Palm Weevil in the UAE, Eastern Region, Al Ain* — pubhort.org | Survey covered 6,177 farms across 30 centres in the Al Ain region |
| Number of farms surveyed | 6,177 | Same source | |
| Infestation percentage (1994/95) | 1.3% | Same source; also reported in iraqi-datepalms.net | |
| Infestation percentage (1995/96) | 1.1% | Same source | |
| Infestation percentage (1996/97) | 0.7% | Same source | |
| Farms with infestation (1994/95) | 28.7% | Same source | |
| Farms with infestation (1995/96) | 33.4% | Same source | |
| Farms with infestation (1996/97) | 20.3% | Same source | |
| Number of infested palms injected (1994/95) | 15,224 | Same source; also reported in iraqi-datepalms.net | |
| Number of infested palms injected (1995/96) | 11,944 | Same source | |
| Number of infested palms injected (1996/97) | 7,769 | Same source | |
| Recovery rate after insecticide injection (Rolfan) | 96.4% average | El Ezaby et al., Table 6 — pubhort.org | Based on 4 centres: Saad East, Saad South, She Bin Ammar, Al Yahar |
| Infestation reduction with pheromones + injection | 63.5% | El Ezaby et al., abstract — pubhort.org | Compared to 3.58% reduction without pheromones |
| Infestation reduction with injection only | 3.58% | Same source | |
| Initial susceptible palms (derived) | 1,108,723 − 15,224 = 1,093,499 | Derived from above | Used as IC94 initial condition |

**Primary source URL:** https://www.pubhort.org/datepalm/datepalm1/datepalm1_23.pdf

---

## 2. 2025 FAO/C4RPWC Programme Outcomes

| Quantity | Value | Source | Notes |
|---|---|---|---|
| Infested palm trees treated | 632 | FAO Regional Webinar, 22/09/2025 — fao.org | Farmer Field Schools in six countries |
| Recovery rate | ≈90% | Same source | |
| Yield/quality improvement reported | 20–25% | Same source | |
| Income gains reported | up to 75% | Same source | |
| Farmer knowledge increase | >50% | Same source | |
| Adoption rate of recommended practices | rose from 38% to 67% | Same source | 65% increase |
| Countries in regional alliance | 18 | Same source | |
| Farmers reached regionally | ≈50 million | Same source | |
| National hub for RPW research (UAE) | Al Hamraniyah Research Center | ICARDA C4RPWC programme page — icarda.org | Designated national hub |
| Field trial sites (UAE) | 36 sites across 7 emirates | Global Agriculture, 18 Dec 2025 — global-agriculture.com | Preparing to test traps, sensors, treatments |
| Aretor endotherapy pilots | Syngenta biorational pesticide (emamectin benzoate) | Same source; also ICARDA C4RPWC page | Injected into palm trunks |

**Primary source URLs:**
- https://www.fao.org/neareast/news/details/fao-regional-webinar-highlights-milestones-in-red-palm-weevil-eradication/en
- https://icarda.org/research/projects/consortium-red-palm-weevil-control-c4rpwc-program

---

## 3. Biological Parameters for *Rhynchophorus ferrugineus*

| Parameter | Value | Unit | Source | Notes |
|---|---|---|---|---|
| Eggs per female (lifetime) | 200–400 (average 300) | eggs | Hussein (1998), cited in journals.ekb.eg | Some studies report up to 531 |
| Egg hatch time | 3–6 | days | Faleiro, *Bio-ecology of Red Palm Weevil* — mel.cgiar.org | |
| Larval period | 25–105 | days | Faleiro (2006); also *The world situation and the main lessons of 30 years of fight against RPW* — scite.ai | 3–17 instars; concealed inside trunk |
| Larval period (alternative range) | 25–170 | days | CISR, UC Riverside — cisr.ucr.edu | Depends on temperature and humidity |
| Pupal stage | 15–30 | days | Faleiro — mel.cgiar.org | 11–45 days in some reports |
| Adult lifespan | 2–3 | months | Faleiro — mel.cgiar.org | Up to 6 months in some conditions |
| Adult dispersal distance | up to 50 | km | Defra (2024), cited in manuscript | 70% fly >1 km in 24 h |
| Egg-to-adult development | 45–139 | days | Faleiro — mel.cgiar.org | |
| Female lifespan | 74 ± 5 | days | Semanticscholar — pdfs.semanticscholar.org | |
| Male lifespan | 94 ± 6 | days | Same source | |
| Larval instars | 10–14 | — | Cabrera (2017), cited in manuscript | |

**Primary source URLs:**
- https://mel.cgiar.org/reporting/downloadmelspace/hash/7e36ef006b556a79a5b00b57a0e9ce9e
- https://cisr.ucr.edu

---

## 4. Pheromone Trap Efficiency

| Parameter | Value | Source | Notes |
|---|---|---|---|
| Capture rate increase with pheromone + food bait | 6.95 ± 1.81× | *Assessment of Attractant Combinations for the Management of RPW in the UAE* — agris.fao.org (2025) | Compared to food bait alone |
| Newly synthesized pheromone vs. commercial | 2.69 ± 0.07× higher | Same source | |
| Trap capture (white traps) | 22.5 adults/trap/month | eprints.hec.gov.pk | |
| Trap capture (alternative) | 16.8 adults/trap/month | Same source | |
| Capture increase with 4-methyl-5-nonanone addition | 65% | FAO — fao.org | Ketone synergist |
| Trap capture increase (5 traps vs. 1 trap) | 3.5× | eprints.hec.gov.pk | |

**Primary source URLs:**
- https://agris.fao.org/search/zh/records/675986e0c7a957febdfab9e5
- https://www.fao.org

---

## 5. Aretor Endotherapy (Emamectin Benzoate)

| Parameter | Value | Source | Notes |
|---|---|---|---|
| Active ingredient | Emamectin benzoate | Hammami et al. (2024) — biosaline.org | Aretor® by Syngenta |
| Concentration options | 4.5% or 9.5% | Same source | TMI optimised formulation |
| Application rate (4.5%) | 48 mL per tree | Same source | Four injection points |
| Application rate (9.5%) | 21 mL per tree | Same source | |
| Application frequency | Once per year | Same source | |
| Pre-harvest interval | 90 days | Same source | |
| Residue persistence in trunk | up to 15 months | *Translocation of emamectin benzoate residues* — wildlife-biodiversity.com | Supports preventive and curative use |
| RPW mortality (laboratory) | >90% | USDA ARS — ars.usda.gov | Cited in technical update |
| Impulse burst rate reduction | to zero after 4 months | Same source | |

**Primary source URLs:**
- https://www.biosaline.org/sites/default/files/publicationsfile/study-rpw-icba-hammami-et-al-2024.pdf
- https://www.syngenta-treecare.com

---

### 6. Acoustic Sensor Detection

| Parameter | Value | Source | Notes |
|---|---|---|---|
| Device names | Palmear, PalmProtect | Bob, El-Shafie & Ammar (2025), *Outlooks on Pest Management*  | Portable acoustic sensors |
| Detection capability | Real-time with reasonable accuracy | Same source  | Minimal labour |
| Deployment (UAE) | IoT acoustic sensors at 36 national hub sites | Global Agriculture (2025) — global-agriculture.com | Part of C4RPWC programme |
| Remote sensing partner | Mohammed Bin Rashid Space Centre | Same source | |
| Detection principle | Acoustic signals of larval feeding | IEEE (2024) — ieeexplore.ieee.org | Deep learning + IoT |

**Primary source URLs:**
- **IngentaConnect (publisher page):** https://www.ingentaconnect.com/content/resinf/opm/2025/00000036/00000003/art00006 
- **DOI:** https://doi.org/10.1564/v36_oct_02 
- **Semantic Scholar (working link):** https://www.semanticscholar.org/paper/Evaluation-and-Validation-of-Acoustic-Sensors-for-Bob-El-Shafie/6b290e1a5ff94851cd659fda7a21d635d43b0d87 
---

## 7. Date Palm Population and Mortality

| Parameter | Value | Source | Notes |
|---|---|---|---|
| Total date palms in UAE | ≈40 million | Al-Muaini et al. (2019), cited in biosaline.org | |
| Date palms in Al Ain region | 8.5 million | Same source | |
| Natural palm lifespan | ≈125 years | UAE conference (2019), cited in manuscript | Used to derive μ_p = 8×10⁻³ day⁻¹ |
| Annual natural loss rate (slow decline disease) | 6% | BSPP Journals — bsppjournals.onlinelibrary.wiley.com | Not directly used but provides context |
| Annual infection rate (Middle East average) | 1.9% | old.belal.by | |
| RPW first recorded in UAE | 1985 | FAO — openknowledge.fao.org | Ras Al Khaimah |

**Primary source URLs:**
- https://www.biosaline.org/sites/default/files/publicationsfile/study-rpw-icba-hammami-et-al-2024.pdf
- https://openknowledge.fao.org

---


## 8. License and Attribution

This compilation is provided for research and educational purposes. All original data remains the property of the cited sources. Where sources are open-access, links are provided. Users should verify all values against the original publications before reuse.

---

*Last updated: 2026*
