# SLR Pipeline — Reverse NIH in High-Capital Emerging Economies
# Target: 40+ quality papers across 4 clusters
# Date: 2026-05-27

## Search Architecture

### Cluster A: NIH / Buy-in Syndrome (10-15 papers)
**Search strings:** "not invented here" syndrome, "buy-in syndrome", "proudly found elsewhere", "attitudes to external knowledge"
**Inclusion:** Peer-reviewed, English, empirical/conceptual, organizational level
**Sources:** Scopus, OpenAlex, Crossref, Semantic Scholar

### Cluster B: GCC HR / Talent / Expat Preference (10-12 papers)
**Search strings:** GCC "talent management", "expatriate preference", "workforce localization", "Saudization", "Emiratization"
**Inclusion:** GCC context, HR/OB, institutional analysis

### Cluster C: GCC Procurement / Consulting / Policy (10-12 papers)
**Search strings:** GCC "procurement", "local content", "consulting", "LCGPA", "IKTVA", "Vision 2030" localization, Nama, Shareek
**Inclusion:** GCC focus, procurement policy, consulting industry
**+** Nazaha / anti-corruption / procurement integrity

### Cluster D: Emerging Economy Parallels / Counter-Examples (8-10 papers)
**Search strings:** "Latin America" foreign preference, "consumer xenocentrism", Brazil procurement, liability of localness, reverse innovation
**Inclusion:** Non-GCC emerging economy, comparative, deviant case

## Database Search Log

### OpenAlex — Cluster C: LCGPA / Local Content / Nazaha
### OpenAlex — Cluster D: Latin America
### OpenAlex — Cluster A: NIH/buy-in extension to emerging economies

### Crossref / Google Scholar — remaining clusters

## Screening Pipeline
1. Title/abstract screen → Include / Exclude / Maybe
2. Full text retrieval → quality score (1-4)
3. Data extraction → Matrix CSV
4. Synthesis

## Current Paper Inventory (12 on disk)

| # | Paper | Cluster | Quality | Status |
|---|-------|---------|---------|--------|
| 1 | Lichtenthaler & Ernst (2006) | A | 4 | On disk |
| 2 | Antons & Piller (2015) — "Opening black box of NIH" | A | 4 | NEW on disk |
| 3 | Ham, Choi & Lee (2017) — "Open and closed knowledge sourcing" | A | 3 | NEW on disk |
| 4 | Roldán Bravo et al. (2022) — "OI practices drive innovation perf" | A | 3 | NEW on disk |
| 5 | Sidani & Al Ariss (2014) — "Institutional and corporate drivers of GTM" | B | 4 | On disk |
| 6 | Hertog (2012) — "GCC labor nationalization policies" | B | 4 | On disk |
| 7 | Elbanna et al. (2023) — "GCC HR systematic review" | B | 3 | On disk |
| 8 | Ewers et al. (2022) — "Skilled migration to emerging economies" | B | 3 | On disk |
| 9 | Mellahi & Al-Hinai (2000) — "Local Workers in GCC" | B | 3 | On disk |
| 10 | Jones (2019) — "Adviser to the King" | C | 4 | On disk |
| 11 | Alhouti (2023) — "Education reform, foreign consultant dependency" | C | 3 | On disk |
| 12 | Gatekeeping Paper (unidentified) | A/C | 3 | On disk |

### Papers to add (found via S2 API, need download)

| # | Paper | Cluster | DOI / Search | Priority |
|---|-------|---------|-------------|----------|
| 13 | **Containing NIHS in external knowledge absorption** (2019, 83 cit) | A | `10.1016/J.RESPOL.2019.103822` | HIGH |
| 14 | Kola & Sołdyński (2025) — "Local Content Requirements in Public Procurement: EU vs Saudi" | C | `10.65271/hjjd6777` | HIGH |
| 15 | Khodroj (2025) — "Public Procurement Status and Improvement Needs in Saudi Arabia" | C | `ssrn.com/abstract=5431714` | HIGH |
| 16 | Hamzi (2026) — "Digital Integrity in the Gulf: Anti-Corruption" | C | `10.5772/intechopen.1013544` | MED |
| 17 | Benavente, Crespi & Alvarez (2019) — "Foreign Competition and Innovation in Latin America" | D | IDB report `10.18235/0002043` | MED |
| 18 | Quaye (2019) — Xenocentrism in emerging markets | D | Search title | MED |
| 19 | Warner (2017) — "Local Content in Procurement" (book) | C | `10.4324/9781351278089` | HIGH |
| 20 | Kattel & Lember (2010) — "Public procurement as an industrial policy tool" | D | J Public Procurement | MED |
| 21 | Edler & Georghiou (2007) — "Public procurement and innovation" | D | `10.1016/j.respol.2007.03.003` | MED |
| 22 | Menon & Pfeffer (2003) — "Valuing internal vs external knowledge" | A | `10.1287/mnsc.49.4.497` | HIGH |
| 23 | Burcharth, Knudsen & Søndergaard (2014) — "Neither invented nor shared here" | A | `10.1016/j.technovation.2013.11.007` | MED |
| 24 | Herzog (2011) — "Open and Closed Innovation" (book) | A | `10.1007/978-3-8349-6150-1` | LOW |
| 25 | **Exploring talent management in practice: an Arab country-specific investigation** (2020, 15 cit) | B | `10.1108/ER-10-2019-0411` | MED |
| 26 | **IHRM in the Arab Gulf States — an institutional perspective** (2017, 47 cit) | B | `10.1080/09585192.2016.1234502` | HIGH |
| 27 | **Talent Management and Development in the UAE** (2018, 16 cit) | B | `10.1177/1523422318803088` | MED |
| 28 | **Evaluating Local Content Policies in Saudi Construction Projects** (2025) | C | S2 search | MED |
| 29 | **Fostering Business Growth Through Local Content in KSA** (2025, 1 cit) | C | S2 search | MED |
| 30 | **Influence of Xenocentrism on Purchase Intentions** (2020, 46 cit) | D | S2 search | MED |
| 31 | **How xenocentrism shapes online consumer behavior** (2025) | D | S2 search | LOW |

## Research Protocol Notes

**LCGPA (Local Content & Government Procurement Authority):** Established 2019, operates Mandatory List of National Products, price preference up to 10% for local content, weighted evaluation algorithms. Pairs with IKTVA (Aramco's in-country value program) and Shareek. Key question: do these mechanisms actually counter Reverse NIH, or do they produce symbolic compliance?

**Nazaha (National Anti-Corruption Authority):** Saudi oversight body for procurement integrity. Links to e-procurement transparency (Etimad platform). Creates a compliance layer that may interact with procurement-as-insurance mechanism.

**Latin America parallel:** Consumer xenocentrism literature well-developed (Quaye 2019, Fischer et al. 2022). Procurement-side less studied but Benavente et al. (2019) shows foreign competition's positive effect on innovation in LAC — a different dynamic from GCC where foreign preference suppresses local innovation.
