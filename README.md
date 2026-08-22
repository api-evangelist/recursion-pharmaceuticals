# Recursion Pharmaceuticals (recursion-pharmaceuticals)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
