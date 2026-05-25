# Recursion Pharmaceuticals (recursion-pharmaceuticals)

Recursion Pharmaceuticals (NASDAQ: RXRX) is a Salt Lake City-based AI-enabled drug discovery company operating the Recursion Operating System (Recursion OS) — a vertically integrated platform pairing automated wet-lab cellular phenomics, transcriptomics (Trekseq), proteomics, ADME, and chemistry with machine learning on the BioHive-2 NVIDIA supercomputer and 50+ petabytes of proprietary data. Following the November 2024 acquisition of Exscientia, Recursion runs 10+ clinical/preclinical programs, 10+ advanced discovery programs, and 10+ partnered programs with Roche/Genentech, Bayer, Sanofi, and Merck KGaA. Recursion has no public commercial API but publishes substantive open-source models (OpenPhenom-S/16, MolE, gflownet, SynFlowNet-Boltz, MAEs Microscopy) and open phenomics datasets (RxRx1/2/3/3-core/19a/19b).

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/recursion-pharmaceuticals/refs/heads/main/apis.yml)

## Tags

- AI, Artificial Intelligence, Drug Discovery, Biotech, Pharmaceuticals, Phenomics, Cellular Imaging, Transcriptomics, Proteomics, Chemistry, Machine Learning, Foundation Models, Open Datasets, Open Source Models, Generative Chemistry, Oncology, Rare Disease, Clinical Trials, BioHive, Recursion OS, MOSAIC, MapApp, OpenPhenom, MolE, GFlowNet, RxRx, Exscientia

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

Recursion does not publish a paid commercial developer API. External access to Recursion's platform is delivered through:

- **MapApp** — Web product exposing the RxRx3 map of biology: 370M relationships, 17,000+ gene knockouts, 1,600+ FDA-approved compounds.
- **OpenPhenom-S/16** — Public foundation model for cellular feature extraction, distributed via Hugging Face, NVIDIA BioNeMo (as Phenom-Beta), and Google Cloud's Model Garden.
- **Open phenomics datasets (RxRx family)** — Bulk-downloadable image and metadata datasets released under research-friendly licenses on rxrx.ai, Hugging Face, and GitHub.
- **Pharma collaborations and licensing deals** — The primary commercial channel; not externally callable.

## Platform Components

- **Recursion OS** — Nomination, Design, and ClinTech workflows over Maps of Biology and Chemistry.
- **BioHive-2** — In-house NVIDIA supercomputer (~$50M NVIDIA investment, 2023).
- **Trekseq** — High-throughput transcriptomics platform.
- **MOSAIC** — Multi-omics generation and analysis stack used internally.
- **Centaur Chemist** — Generative chemistry suite acquired with Exscientia.
- **Phenom-1 / Phenom-2 / Phenom-Beta / OpenPhenom-S/16** — Phenomics foundation models (Phenom-1 at CVPR 2024, Phenom-2 at NeurIPS FM4S 2024).
- **MolE** — Molecular foundation model.
- **gflownet** — Graph and molecular generative modeling library.
- **SynFlowNet-Boltz** — Retrosynthesis-aware molecular design.

## Clinical Pipeline (Selected)

| Program | Indication | Stage |
|---|---|---|
| REC-4881 | Familial adenomatous polyposis (FAP) — TUPELO | Clinical |
| REC-3565 | MALT1 inhibitor, B-cell malignancies — EXCELERIZE | Clinical |
| REC-1245 | RBM39, biomarker-enriched solid tumors / lymphoma — DAHLIA | Clinical |
| REC-617 | CDK7 inhibitor, advanced solid tumors — ELUCIDATE | Clinical |
| REC-994 | Cerebral cavernous malformation — SYCAMORE | Clinical |
| REC-2282 | NF2-mutated meningiomas — POPLAR | Clinical |
| REC-4209 | Idiopathic pulmonary fibrosis | Preclinical |
| REC-7735 | HSD obesity | Preclinical |

## Partnerships

| Partner | Year | Focus | Economics |
|---|---|---|---|
| Roche / Genentech | 2021 | Neuroscience, GI oncology | $150M upfront; up to ~$300M+ per program; up to 40 programs |
| Bayer | 2020 (extended 2023) | Precision oncology | $80M upfront + equity; up to $1.5B milestones; up to 7 programs |
| Sanofi | 2022 | Oncology, immunology | $100M upfront; up to $5.2B milestones; up to 15 targets |
| Merck KGaA, Darmstadt | 2023 | Oncology, immunology | $20M upfront; up to $674M milestones; 3 initial programs |
| NVIDIA | 2023 | Compute, foundation models | $50M investment; BioHive-2 build |
| Tempus | 2023 | Oncology patient data | >20 PB clinical data access |
| Helix | 2024 | Clinico-genomic data | 200k+ de-identified records |

## Open Source Models and Datasets

### Hugging Face

- [OpenPhenom-S/16](https://huggingface.co/recursionpharma/OpenPhenom) — Phenomics feature extraction foundation model.
- [RxRx3 dataset](https://huggingface.co/datasets/recursionpharma/rxrx3)
- [RxRx3-core dataset](https://huggingface.co/datasets/recursionpharma/rxrx3-core)

### GitHub ([recursionpharma](https://github.com/recursionpharma))

- [gflownet](https://github.com/recursionpharma/gflownet) — Graph/molecular GFlowNet library (MIT).
- [mole_public](https://github.com/recursionpharma/mole_public) — MolE molecular foundation model.
- [synflownet-boltz](https://github.com/recursionpharma/synflownet-boltz) — Retrosynthesis-aware design (MIT).
- [maes_microscopy](https://github.com/recursionpharma/maes_microscopy) — NeurIPS 2023 spotlight masked autoencoders for microscopy.
- [rxrx1-utils](https://github.com/recursionpharma/rxrx1-utils) — NeurIPS 2019 CellSignal competition starter (Apache-2.0).
- [rxrx-datasets](https://github.com/recursionpharma/rxrx-datasets) — Documentation for RxRx datasets.

### Open Datasets ([rxrx.ai](https://www.rxrx.ai))

- **RxRx1** — Cell painting across siRNA perturbations.
- **RxRx2** — Cytokine storm models.
- **RxRx3** — Genome-scale CRISPR knockouts + small molecules (powers MapApp).
- **RxRx3-core** — Research-optimized subset of RxRx3.
- **RxRx19a / RxRx19b** — SARS-CoV-2 / COVID-19 cytokine storm screens.

## Common Properties

- [Website](https://www.recursion.com)
- [Platform — Recursion OS](https://www.recursion.com/recursion-os)
- [Pipeline](https://www.recursion.com/pipeline)
- [Partnerships](https://www.recursion.com/partners)
- [Publications](https://www.recursion.com/publications)
- [Open Datasets — rxrx.ai](https://www.rxrx.ai)
- [MapApp](https://www.rxrx.ai/mapapp)
- [Hugging Face](https://huggingface.co/recursionpharma)
- [GitHub Organization](https://github.com/recursionpharma)
- [Phenom-Beta on NVIDIA BioNeMo](https://build.nvidia.com/recursion)
- [Investor Relations](https://ir.recursion.com)
- [Acquisition — Exscientia completion](https://ir.recursion.com/news-releases/news-release-details/recursion-completes-acquisition-exscientia)
- [LinkedIn](https://www.linkedin.com/company/recursionpharma)
- [Twitter](https://twitter.com/RecursionPharma)
- [YouTube](https://www.youtube.com/@RecursionPharmaceuticals)

## Tier Assessment

**Tier 2 — Provider with no commercial API, but a substantive open-source / open-model footprint.** Like [Figure](https://github.com/api-evangelist/figure-robotics), Recursion does not yet sell developer access to its core platform. Unlike Figure, Recursion publishes meaningful open weights (OpenPhenom-S/16), open datasets (the RxRx family), and open libraries (gflownet, MolE, SynFlowNet-Boltz) that the computational biology community can use directly. This puts it closer to provider-tier players like [Anthropic](https://github.com/api-evangelist/anthropic) on the open-tooling axis, even though it lacks a paid API surface.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
