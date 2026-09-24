# Portfolio Reproduction Cost Analysis

**Owner:** [@theworker02](https://github.com/theworker02) (Matthew)  
**Prepared:** 2026-09-24  
**Purpose:** Independent replacement-cost and commercial asking-price analysis for every owned repository (excluding third-party forks).  
**Commercial posture:** Each asset is positioned for **sale or exclusive commercial license at a floor of USD $80,000**. Platform and deep-IP systems are listed above that floor.

> This document estimates **what it would cost a competent buyer or competitor to reproduce** the transferable IP (source, architecture, tests, docs, CI, packaging, and domain know-how encoded in-repo), then maps that to a **commercial asking price**. It is diligence support, not a binding offer or appraisal under USPAP.

---

## Methodology

| Parameter | Value |
| :--- | :--- |
| Loaded senior engineer rate | USD $165–$220 / hour (varies by tier) |
| Included work | product design, architecture, implementation, tests, CI/CD, docs, packaging, security posture, acquisition room |
| Excluded | live customers, ARR, filed patents (unless evidenced in-repo), hosted infra OPEX |
| Floor asking price | **USD $80,000 per repository asset** |
| Multiplier logic | Reproduction cost × strategic scarcity / domain premium (robotics, connectomics, quantum, distributed systems, proprietary OEM packs) |

**Reproduction cost** = estimated specialized engineering hours × loaded rate.  
**Asking price** = commercial sale target reflecting reproduction cost, scarcity, and transferability of proprietary rights — **never below $80,000**.

### Portfolio roll-up (owned non-fork repos)

| Metric | Amount |
| :--- | ---: |
| Repositories analyzed | 89 |
| Aggregate reproduction cost | USD $10,343,950 |
| Aggregate commercial asking (sum of floors) | USD $13,050,000 |
| Per-asset asking floor | USD $80,000 |

---

## Summary table

| Repository | Visibility | Language | Size (KB) | Tier | Est. hours | Repro cost | Asking price |
| :--- | :---: | :---: | ---: | :--- | ---: | ---: | ---: |
| [Axiom-IDE](https://github.com/theworker02/Axiom-IDE) | private | TypeScript | 41220 | Platform | 1800 | $396,000 | **$450,000** |
| [Nexus-robotics-OS](https://github.com/theworker02/Nexus-robotics-OS) | public | HTML | 355248 | Platform | 1800 | $396,000 | **$450,000** |
| [EdgeMirror](https://github.com/theworker02/EdgeMirror) | public | TypeScript | 628 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [quantum-materials-1](https://github.com/theworker02/quantum-materials-1) | private | Python | 345 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [SVIE-concept](https://github.com/theworker02/SVIE-concept) | public | Python | 4879 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [nex-lang](https://github.com/theworker02/nex-lang) | public | TypeScript | 9582 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [CUDAtoAMD](https://github.com/theworker02/CUDAtoAMD) | public | Python | 229 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [cross-region-private-networking](https://github.com/theworker02/cross-region-private-networking) | public | Rust | 261 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [deadwire](https://github.com/theworker02/deadwire) | public | TypeScript | 99 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [reprise](https://github.com/theworker02/reprise) | public | TypeScript | 199 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [facet-lang](https://github.com/theworker02/facet-lang) | private | Ruby | 7541 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [magnexis-quantum](https://github.com/theworker02/magnexis-quantum) | public | HTML | 2660 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [magaphragma-connectome](https://github.com/theworker02/magaphragma-connectome) | public | Python | 2701 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [new-connectome-project](https://github.com/theworker02/new-connectome-project) | public | Python | 11324 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [OpenDashCAN](https://github.com/theworker02/OpenDashCAN) | public | Python | 1985 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [patentpulse](https://github.com/theworker02/patentpulse) | public | Python | 285 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [stateful-deployments-engine](https://github.com/theworker02/stateful-deployments-engine) | public | Go | 1047 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [Parallax](https://github.com/theworker02/Parallax) | public | Rust | 1097 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [kraftverk](https://github.com/theworker02/kraftverk) | public | Rust | 603 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [commons](https://github.com/theworker02/commons) | public | JavaScript | 2623 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [centralizer](https://github.com/theworker02/centralizer) | public | Go | 3168 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [chimera](https://github.com/theworker02/chimera) | public | Rust | 421 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [unlearning-experiment](https://github.com/theworker02/unlearning-experiment) | private | Python | 15230 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [botscope](https://github.com/theworker02/botscope) | public | Python | 3474 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [virion](https://github.com/theworker02/virion) | private | Python | 919 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [silicera](https://github.com/theworker02/silicera) | public | Rust | 311 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [relaystate-protocol](https://github.com/theworker02/relaystate-protocol) | private | C# | 2939 | Systems / Deep IP | 900 | $180,000 | **$220,000** |
| [stackglass](https://github.com/theworker02/stackglass) | public | TypeScript | 2017 | Product System | 650 | $120,250 | **$150,000** |
| [lumaforge-engine](https://github.com/theworker02/lumaforge-engine) | private | TypeScript | 54 | Product System | 650 | $120,250 | **$150,000** |
| [Knot.js](https://github.com/theworker02/Knot.js) | public | TypeScript | 1663 | Product System | 650 | $120,250 | **$150,000** |
| [veyra-scientific](https://github.com/theworker02/veyra-scientific) | public | Python | 2645 | Product System | 650 | $120,250 | **$150,000** |
| [lattice](https://github.com/theworker02/lattice) | public | JavaScript | 1994 | Product System | 650 | $120,250 | **$150,000** |
| [rustoleum-lang](https://github.com/theworker02/rustoleum-lang) | private | Rust | 2433 | Product System | 650 | $120,250 | **$150,000** |
| [open-reason](https://github.com/theworker02/open-reason) | public | Python | 4096 | Product System | 650 | $120,250 | **$150,000** |
| [airtunnel](https://github.com/theworker02/airtunnel) | private | Python | 2453 | Product System | 650 | $120,250 | **$150,000** |
| [lexicon-error](https://github.com/theworker02/lexicon-error) | public | Python | 6760 | Product System | 650 | $120,250 | **$150,000** |
| [wallcore](https://github.com/theworker02/wallcore) | private | HTML | 2466 | Product System | 650 | $120,250 | **$150,000** |
| [ruby_llm_mesh](https://github.com/theworker02/ruby_llm_mesh) | public | Ruby | 800 | Product System | 650 | $120,250 | **$150,000** |
| [emerging-threat-watch-1](https://github.com/theworker02/emerging-threat-watch-1) | public | HTML | 11393 | Product System | 650 | $120,250 | **$150,000** |
| [conterfactual-engagement-ranking](https://github.com/theworker02/conterfactual-engagement-ranking) | private | Python | 5140 | Product System | 650 | $120,250 | **$150,000** |
| [ChronosCTC](https://github.com/theworker02/ChronosCTC) | public | Rust | 1601 | Product System | 650 | $120,250 | **$150,000** |
| [contracts-rb](https://github.com/theworker02/contracts-rb) | public | Ruby | 2128 | Product System | 650 | $120,250 | **$150,000** |
| [signalkey](https://github.com/theworker02/signalkey) | public | TypeScript | 2944 | Product System | 650 | $120,250 | **$150,000** |
| [postpilot](https://github.com/theworker02/postpilot) | private | TypeScript | 2230 | Product System | 650 | $120,250 | **$150,000** |
| [bootprint](https://github.com/theworker02/bootprint) | public | Ruby | 1945 | Product System | 650 | $120,250 | **$150,000** |
| [pubdiagnose](https://github.com/theworker02/pubdiagnose) | public | Dart | 542 | Product System | 650 | $120,250 | **$150,000** |
| [portbind](https://github.com/theworker02/portbind) | public | JavaScript | 807 | Focused Product | 420 | $73,500 | **$95,000** |
| [resonance](https://github.com/theworker02/resonance) | public | TypeScript | 431 | Focused Product | 420 | $73,500 | **$95,000** |
| [pagesmark](https://github.com/theworker02/pagesmark) | public | JavaScript | 730 | Focused Product | 420 | $73,500 | **$95,000** |
| [runledger](https://github.com/theworker02/runledger) | public | JavaScript | 741 | Focused Product | 420 | $73,500 | **$95,000** |
| [rowkit](https://github.com/theworker02/rowkit) | public | TypeScript | 678 | Focused Product | 420 | $73,500 | **$95,000** |
| [shiftlock](https://github.com/theworker02/shiftlock) | public | Go | 1360 | Focused Product | 420 | $73,500 | **$95,000** |
| [receipt-md](https://github.com/theworker02/receipt-md) | public | JavaScript | 713 | Focused Product | 420 | $73,500 | **$95,000** |
| [diffnoun](https://github.com/theworker02/diffnoun) | public | JavaScript | 679 | Focused Product | 420 | $73,500 | **$95,000** |
| [commitlint-lite](https://github.com/theworker02/commitlint-lite) | public | JavaScript | 727 | Focused Product | 420 | $73,500 | **$95,000** |
| [envshape](https://github.com/theworker02/envshape) | public | JavaScript | 750 | Focused Product | 420 | $73,500 | **$95,000** |
| [doldskrift](https://github.com/theworker02/doldskrift) | public | Rust | 1215 | Focused Product | 420 | $73,500 | **$95,000** |
| [cidrhas](https://github.com/theworker02/cidrhas) | public | JavaScript | 787 | Focused Product | 420 | $73,500 | **$95,000** |
| [AssaySentinel.jl](https://github.com/theworker02/AssaySentinel.jl) | public | Julia | 480 | Focused Product | 420 | $73,500 | **$95,000** |
| [arcframe](https://github.com/theworker02/arcframe) | public | TypeScript | 440 | Focused Product | 420 | $73,500 | **$95,000** |
| [bytesize](https://github.com/theworker02/bytesize) | public | JavaScript | 714 | Focused Product | 420 | $73,500 | **$95,000** |
| [tlsscope](https://github.com/theworker02/tlsscope) | public | TypeScript | 729 | Focused Product | 420 | $73,500 | **$95,000** |
| [specslice](https://github.com/theworker02/specslice) | public | JavaScript | 711 | Focused Product | 420 | $73,500 | **$95,000** |
| [licensehead](https://github.com/theworker02/licensehead) | public | JavaScript | 702 | Focused Product | 420 | $73,500 | **$95,000** |
| [sli-counter](https://github.com/theworker02/sli-counter) | public | JavaScript | 766 | Focused Product | 420 | $73,500 | **$95,000** |
| [modfence](https://github.com/theworker02/modfence) | public | TypeScript | 694 | Focused Product | 420 | $73,500 | **$95,000** |
| [jsonptrget](https://github.com/theworker02/jsonptrget) | public | JavaScript | 746 | Focused Product | 420 | $73,500 | **$95,000** |
| [heapscope](https://github.com/theworker02/heapscope) | public | Ruby | 1021 | Focused Product | 420 | $73,500 | **$95,000** |
| [gistfold](https://github.com/theworker02/gistfold) | public | JavaScript | 695 | Focused Product | 420 | $73,500 | **$95,000** |
| [fixturefreeze](https://github.com/theworker02/fixturefreeze) | public | JavaScript | 817 | Focused Product | 420 | $73,500 | **$95,000** |
| [wiretap](https://github.com/theworker02/wiretap) | public | Go | 276 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [taglock](https://github.com/theworker02/taglock) | public | Go | 285 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [themachine](https://github.com/theworker02/themachine) | private | Rust | 205 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [specmint](https://github.com/theworker02/specmint) | private | Python | 58 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [beforerun](https://github.com/theworker02/beforerun) | public | Go | 102 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [brownfield-equipment-node](https://github.com/theworker02/brownfield-equipment-node) | private | JavaScript | 109 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [cartographer](https://github.com/theworker02/cartographer) | public | TypeScript | 198 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [AUC-project](https://github.com/theworker02/AUC-project) | public | HTML | 61 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [aevryn](https://github.com/theworker02/aevryn) | private | Rust | 259 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [aftermath](https://github.com/theworker02/aftermath) | public | TypeScript | 229 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [atlas-of-knowledge](https://github.com/theworker02/atlas-of-knowledge) | public | Python | 279 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [deaddrop](https://github.com/theworker02/deaddrop) | public | Rust | 232 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [medlattice](https://github.com/theworker02/medlattice) | private | Python | 249 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [monkeylens](https://github.com/theworker02/monkeylens) | public | Ruby | 309 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [rivet](https://github.com/theworker02/rivet) | public | Python | 390 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [loomforge](https://github.com/theworker02/loomforge) | public | Python | 329 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [eigen-algorithym](https://github.com/theworker02/eigen-algorithym) | private | Python | 181 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [frameguard](https://github.com/theworker02/frameguard) | public | Dart | 387 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |
| [later](https://github.com/theworker02/later) | public | Ruby | 137 | Specialized Utility / Module | 320 | $52,800 | **$80,000** |

---

## Per-repository narratives

### aevryn

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/aevryn |
| Visibility | private |
| Primary language | Rust |
| Repo size (approx) | 259 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### aftermath

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/aftermath |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 229 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Aftermath is an execution-backed verification layer for coding agents. It independently examines diffs, builds, tests, linters, type checkers, formatters, smoke tests, dependency changes, public API drift, warnings, benchmark regressions, artifacts, and repository health; then produces a durable verification receipt (human + machine-readable).

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### airtunnel

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/airtunnel |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 2453 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### arcframe

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/arcframe |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 440 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** ocal-first repository intelligence for Cursor MCP and AI coding agents. Arc Index, Arc Graph, blast-radius impact analysis, and evidence-backed context. Analysis stays on your machine.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### AssaySentinel.jl

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/AssaySentinel.jl |
| Visibility | public |
| Primary language | Julia |
| Repo size (approx) | 480 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Scientific assay quality, drift detection, calibration surveillance, batch analysis, and reproducible measurement provenance for Julia.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### atlas-of-knowledge

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/atlas-of-knowledge |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 279 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** the Atlas of Knowledge is an open, machine-readable map of university knowledge. It combines original concept explanations, explicit prerequisite and relationship edges, auditable provenance, and deterministic release generation. It is not a mirror of syllabi, textbooks, or lecture notes.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### AUC-project

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/AUC-project |
| Visibility | public |
| Primary language | HTML |
| Repo size (approx) | 61 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** AUC is a portfolio of independent environmental systems supported by shared evidence, telemetry, and energy planning. It is not a single combined hazardous-process machine.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### Axiom-IDE

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/Axiom-IDE |
| Visibility | private |
| Primary language | TypeScript |
| Repo size (approx) | 41220 KB |
| Complexity tier | Platform |
| Estimated specialized hours | 1800 |
| Loaded rate used | USD $220 / hr |
| **Reproduction cost** | **USD $396,000** |
| **Commercial asking price** | **USD $450,000** (floor ≥ $80,000) |

**Product thesis:** A provider-neutral, local-first AI development environment built on the open-source Code - OSS foundation.  Axiom keeps the editor, terminal, source control, debugging, and VSIX workflows developers expect while making model selection, local privacy, tools, and context explicit and configurable.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### beforerun

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/beforerun |
| Visibility | public |
| Primary language | Go |
| Repo size (approx) | 102 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** BeforeRun is a zero-dependency Go CLI that scans an unfamiliar codebase before you install dependencies, open automated workspace tasks, build a dev container, or execute project scripts.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### bootprint

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/bootprint |
| Visibility | public |
| Primary language | Ruby |
| Repo size (approx) | 1945 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Bootprint is a local-first Ruby runtime fingerprint and compatibility diagnostic. It captures a sanitized description of an application environment, compares that description with CI, Docker, staging, or production, and turns raw drift into explanations, severity, evidence, remediation, and enforceable policy.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### botscope

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/botscope |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 3474 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** BotScope is an Internet-wide bot traffic census: the Global Observatory federates public crawler/IP panels, crawl catalogs, and optional CDN estimates into a worldwide automation picture ΓÇö alongside a local analyzer and native Qt desktop Observatory for authorized logs, sessions, and live capture.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### brownfield-equipment-node

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/brownfield-equipment-node |
| Visibility | private |
| Primary language | JavaScript |
| Repo size (approx) | 109 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### bytesize

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/bytesize |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 714 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Parse, format, and convert human byte sizes (SI and IEC). npm: https://www.npmjs.com/package/%40magnexis/bytesize

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### cartographer

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/cartographer |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 198 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** A typescript native navigation system for software architecture. Know where you are in the code.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### centralizer

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/centralizer |
| Visibility | public |
| Primary language | Go |
| Repo size (approx) | 3168 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Centralizer is a Go-based interoperability runtime that discovers, connects, supervises, and exposes software written across different programming languages through a unified interface.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### chimera

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/chimera |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 421 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Decentralized peer-to-peer distributed computation and rendering grid in Rust: gossip discovery, QUIC mesh, Wasm sandboxing, content-addressed storage, and a distributed memory fabric.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### ChronosCTC

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/ChronosCTC |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 1601 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Chronal runtime for Deutsch-consistent closed timelike curves A self-compiling spacetime engine ΓÇö from fixed-point kernels to Novikov cosmologies.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### cidrhas

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/cidrhas |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 787 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Test whether IPv4 addresses sit inside CIDR ranges, with explain and list. npm: https://www.npmjs.com/package/%40magnexis/cidrhas

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### commitlint-lite

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/commitlint-lite |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 727 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Lint conventional subjects, including the latest git log entry. npm: https://www.npmjs.com/package/%40magnexis/commitlint-lite

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### commons

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/commons |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 2623 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** COMMONS is an open-source, API-first social and coordination network for autonomous software agents. Agents can register identities, discover one another, publish untrusted social content, organize work in projects and Rooms, publish artifacts, and record independent verification. 

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### conterfactual-engagement-ranking

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/conterfactual-engagement-ranking |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 5140 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### contracts-rb

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/contracts-rb |
| Visibility | public |
| Primary language | Ruby |
| Repo size (approx) | 2128 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** `contracts-rb` adds small, explicit behavioral contracts to Ruby without imposing a type system. It supports parameter and return constraints, preconditions, postconditions, object invariants, state snapshots, mutation policies, exception declarations, introspection, and a dependency-free CLI.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### cross-region-private-networking

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/cross-region-private-networking |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 261 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Cross-region private networking fabric extending Render same-region private nets (independent; not affiliated). Proprietary ΓÇö sale/acquisition only.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### CUDAtoAMD

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/CUDAtoAMD |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 229 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** An early, open interoperability project for assessing and incrementally adapting CUDA-oriented source workloads to AMD's HIP/ROCm ecosystem.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### deaddrop

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/deaddrop |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 232 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Encrypted delay-tolerant networking for computers that are not always online together.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### deadwire

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/deadwire |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 99 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Deadwire is an Upstash-first recovery-intelligence control plane. It sits above Upstash Workflow and QStash; it does not replace their execution model. Deadwire groups DLQ entries into operational incidents, assembles provenance and side-effect evidence...

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### diffnoun

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/diffnoun |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 679 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Summarize a unified diff as add/remove/change with optional stats. npm: https://www.npmjs.com/package/%40magnexis/diffnoun

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### doldskrift

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/doldskrift |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 1215 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Encode structured information into a visual writing system designed for deterministic machine reconstruction.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### EdgeMirror

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/EdgeMirror |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 628 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Know before you deploy ΓÇö Cloudflare Workers localΓåöremote parity engine (independent, source-available proprietary). Commercial licenses: COMMERCIAL.md. Acquisition brief: ACQUISITION.md

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### eigen-algorithym

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/eigen-algorithym |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 181 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### emerging-threat-watch-1

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/emerging-threat-watch-1 |
| Visibility | public |
| Primary language | HTML |
| Repo size (approx) | 11393 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Independent, evidence-driven threat-intelligence investigations into 15 malware family / candidate case folders 

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### envshape

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/envshape |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 750 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Validate process.env or a dotenv file against a JSON key/type schema. npm: https://www.npmjs.com/package/%40magnexis/envshape

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### facet-lang

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/facet-lang |
| Visibility | private |
| Primary language | Ruby |
| Repo size (approx) | 7541 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Facet is a strict, gradually typed, concurrency-oriented superset of Ruby. Its compatibility promise is simple: Every supported Ruby program remains valid Facet unless it explicitly enables stricter guarantees that the program violates. 

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### fixturefreeze

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/fixturefreeze |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 817 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Freeze files or directories into fixtures/ and check them byte-for-byte. npm: https://www.npmjs.com/package/%40magnexis/fixturefreeze

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### frameguard

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/frameguard |
| Visibility | public |
| Primary language | Dart |
| Repo size (approx) | 387 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** FrameGuard ΓÇö performance regressions, testable. Flutter UI budgets, baselines, and CI gates. Local by default. No telemetry.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### gistfold

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/gistfold |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 695 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Check gist-style folders for README, example files, clone instructions, and TODO-free sources. npm: https://www.npmjs.com/package/%40magnexis/gistfold

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### heapscope

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/heapscope |
| Visibility | public |
| Primary language | Ruby |
| Repo size (approx) | 1021 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** HeapScope is a local, evidence-driven Ruby gem for diagnosing object retention, abnormal heap growth, allocation hot spots, long-lived objects, and leak-shaped patterns in long-running processes.  It is designed for Rails, Puma, Sidekiq, background jobs, CLIs, and CI.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### jsonptrget

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/jsonptrget |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 746 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Read RFC 6901 JSON Pointer values from stdin or a file.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### Knot.js

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/Knot.js |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 1663 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Knot challenges one of the oldest assumptions in the Node.js ecosystem: that an entire dependency tree must be installed into a project-local node_modules/ directory before a program can run.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### kraftverk

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/kraftverk |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 603 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Evidence-driven systems performance platform (AMD-exclusive)

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### later

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/later |
| Visibility | public |
| Primary language | Ruby |
| Repo size (approx) | 137 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** `later` is a local-first temporal runtime for plain Ruby. It persists scheduled operations in SQLite, recovers leased work after crashes, records execution history, and provides an expressive path from one delayed call to recurring jobs, events, futures, and validated workflow graphs.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### lattice

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/lattice |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 1994 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** LATTICE explores a different kind of physical product: modules that sense the world, make local decisions, show what they are doing, and pass useful information to another device or piece of software. The first product direction is a mirror-scale Signal Cube.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### lexicon-error

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/lexicon-error |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 6760 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** LexiconError is a desktop, offline-first reference for programming-language diagnostics: compiler codes, linter rules, runtime exceptions, and source-qualified message patterns. It uses a Tauri desktop shell, React/TypeScript UI, and local SQLite FTS5 index. Core search, detection, contributions.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### licensehead

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/licensehead |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 702 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Scan or fix SPDX-License-Identifier headers in JS/TS files. npm: https://www.npmjs.com/package/%40magnexis/licensehead

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### loomforge

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/loomforge |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 329 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** LoomForge is an early engineering prototype for a modular benchtop workstation that inserts pre-crimped wires into one supported connector family and verifies the completed connector through a mating electrical test interface.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### lumaforge-engine

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/lumaforge-engine |
| Visibility | private |
| Primary language | TypeScript |
| Repo size (approx) | 54 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### magaphragma-connectome

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/magaphragma-connectome |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 2701 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Unfinished takeover-ready Megaphragma/Vigilia connectome research infrastructure ΓÇö Affinity S7 FAST + Vast/local hybrid; heavy lifting done, full volume not finished. See HANDOFF.md.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### magnexis-quantum

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/magnexis-quantum |
| Visibility | public |
| Primary language | HTML |
| Repo size (approx) | 2660 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** A lightweight, server-rendered engineering document portal for an independent research program: email-free accounts, access applications, collection-level approvals, protected research documents, and real classical simulations. The included physical-system engineering is a confidential proposal. 

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### medlattice

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/medlattice |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 249 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### modfence

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/modfence |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 694 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** TypeScript import-boundary linter. Declare layers, ban cycles, explain illegal imports.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### monkeylens

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/monkeylens |
| Visibility | public |
| Primary language | Ruby |
| Repo size (approx) | 309 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** MonkeyLens captures the effective Ruby method table for selected classes and modules, records who owns every method, tracks source locations, visibility, signatures, and ancestor order, then compares that runtime against a committed baseline.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### new-connectome-project

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/new-connectome-project |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 11324 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Insectome ΓÇö static multi-species connectome studio (GitHub Pages)

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### nex-lang

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/nex-lang |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 9582 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Nexus (.nex) language ΓÇö TypeScript toolchain, self-hosting, design language, and Nex LSP for VS Code / Open VSX

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### Nexus-robotics-OS

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/Nexus-robotics-OS |
| Visibility | public |
| Primary language | HTML |
| Repo size (approx) | 355248 KB |
| Complexity tier | Platform |
| Estimated specialized hours | 1800 |
| Loaded rate used | USD $220 / hr |
| **Reproduction cost** | **USD $396,000** |
| **Commercial asking price** | **USD $450,000** (floor ≥ $80,000) |

**Product thesis:** Nexus Robotics OS is a Rust-first, hardware-agnostic robotics platform for skills, configurable intelligence, learning, simulation, safety, connected tools, and heterogeneous robotic hardware. It gives applications and robot skills one stable, capability-driven interface while preserving the robotics stack already in place: simulator, ROS 2 graph.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### OpenDashCAN

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/OpenDashCAN |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 1985 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** OpenDashCAN Desktop stays on your PC. It reads vehicle CAN somehow (USB adapter, listen-only Pi recorder, or offline log), decodes registered layouts, and surfaces VehicleState, ID rates, PhaseΓÇæ4 cluster gaps, adaptation plans, wiring checklists, and research docs.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### open-reason

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/open-reason |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 4096 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Open, verified dataset and pipeline for coding, science, mathematics, and human reasoning. No Reddit.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### pagesmark

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/pagesmark |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 730 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Initialize or check a GitHub Pages /docs starter site. npm: https://www.npmjs.com/package/%40magnexis/pagesmark

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### Parallax

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/Parallax |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 1097 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Polyglot migration and universal execution runtime Capture program state in one language, encode it as language-neutral IR, restore or migrate it in another.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### patentpulse

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/patentpulse |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 285 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** PatentPulse is a locally owned, 1.6 TB corpus of USPTO patent grants and published applications. It downloads official weekly XML dumps, stream-parses them without loading an archive into memory, and writes normalized SQLite and JSON Lines outputs for search, tokenization, embeddings, and model training.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### portbind

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/portbind |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 807 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Scan source files and globs for 0.0.0.0 and PORT bind patterns. npm: https://www.npmjs.com/package/%40magnexis/portbind

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### postpilot

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/postpilot |
| Visibility | private |
| Primary language | TypeScript |
| Repo size (approx) | 2230 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** PostPilot is an open-source ChatGPT plugin that connects a user's X account and lets ChatGPT draft, validate, review, publish, list, and delete posts through a remote MCP server.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### pubdiagnose

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/pubdiagnose |
| Visibility | public |
| Primary language | Dart |
| Repo size (approx) | 542 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** PubDoctor ΓÇö Diagnose your Dart dependencies.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### quantum-materials-1

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/quantum-materials-1 |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 345 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** This repository is private because it contains Magnexis Quantum's authored engineering proposals among other important documents.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### receipt-md

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/receipt-md |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 713 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Write a markdown PASS/FAIL receipt with notes and an optional JSON sidecar. npm: https://www.npmjs.com/package/%40magnexis/receipt-md

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### relaystate-protocol

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/relaystate-protocol |
| Visibility | private |
| Primary language | C# |
| Repo size (approx) | 2939 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** A Windows-first continuity layer and vendor-neutral protocol for transferring explicit live-task state between AI agents.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### reprise

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/reprise |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 199 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Reprise is a local-first recovery and compatibility control plane for changing backends. It models deployments, schema, functions, storage contracts, auth, configuration, and dependencies as evidence-backed historical state. It chooses a mutually compatible recovery candidate, verifies it in isolation, and refuses unsafe promotion by default.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### resonance

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/resonance |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 431 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** An open software platform and reference architecture for distributed acoustic event detection.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### rivet

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/rivet |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 390 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Rivet is an installable, safety-first adaptive robot runtime and capability-development platform for Raspberry Pi robotics. It gives applications one local boundary for hardware discovery, deterministic safety, resource adaptation, perception provenance, robot specialization, mission planning, and auditable competence.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### rowkit

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/rowkit |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 678 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Streaming JSONL/CSV toolkit: infer schemas, validate, sample, split, and dedupe.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### ruby_llm_mesh

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/ruby_llm_mesh |
| Visibility | public |
| Primary language | Ruby |
| Repo size (approx) | 800 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Unified multi-provider AI routing with circuit-breaking and local fallback for Ruby & Rails

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### runledger

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/runledger |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 741 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Append-only JSONL command ledger with record, list, filter, and summary. npm: https://www.npmjs.com/package/%40magnexis/runledger

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### rustoleum-lang

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/rustoleum-lang |
| Visibility | private |
| Primary language | Rust |
| Repo size (approx) | 2433 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### shiftlock

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/shiftlock |
| Visibility | public |
| Primary language | Go |
| Repo size (approx) | 1360 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Security-first Go resource fabric for ownership handoffs, fencing, and multi-resource coordination

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### signalkey

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/signalkey |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 2944 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** A local-first desktop workflow controller with a tactile hardware direction. SignalKey lets a person press a physical control, run an explicitly approved local workflow, and inspect its observed result. The desktop companion is at 0.1.0-alpha.2: the physical product is an engineering concept under development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### silicera

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/silicera |
| Visibility | public |
| Primary language | Rust |
| Repo size (approx) | 311 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Independent systems research software for hardware-native program specialization on AMD Zen.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### sli-counter

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/sli-counter |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 766 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Track good/bad events and fail when the success ratio drops below an SLO. npm: https://www.npmjs.com/package/%40magnexis/sli-counter

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### specmint

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/specmint |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 58 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### specslice

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/specslice |
| Visibility | public |
| Primary language | JavaScript |
| Repo size (approx) | 711 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Extract markdown headings, fenced languages, unique langs, and a TOC from specs. npm: https://www.npmjs.com/package/%40magnexis/specslice

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### stackglass

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/stackglass |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 2017 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Stackglass is the observability and verification layer for AI-assisted development.  Cursor writes and reasons about code. Stackglass gives that agent evidence about state, tests, failures, history, configuration, contracts, and documentation ΓÇö so it does not have to guess.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### stateful-deployments-engine

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/stateful-deployments-engine |
| Visibility | public |
| Primary language | Go |
| Repo size (approx) | 1047 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Stateful Deployments Engine (SDE) ΓÇö transactional cutover for volume-backed workloads. Proprietary pre-acquisition. Independent ΓÇö not affiliated with Railway.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### SVIE-concept

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/SVIE-concept |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 4879 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** SVIE is a sellable OEM engineering package for supercritical flash fuel delivery, camless DEVA valvetrain architecture, and belt-free multi-ratio hybrid drives ΓÇö delivered as code and specs, not slideware.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### taglock

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/taglock |
| Visibility | public |
| Primary language | Go |
| Repo size (approx) | 285 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Compile-time confidence for Go's runtime metadata, and compatibility intelligence for the contracts that metadata creates. TagLock statically analyzes Go struct tags as one serialized contract. It finds today's collisions, unsafe exposure, type errors, and namespace drift, then can snapshot those external representations and detect changes

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### themachine

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/themachine |
| Visibility | private |
| Primary language | Rust |
| Repo size (approx) | 205 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### tlsscope

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/tlsscope |
| Visibility | public |
| Primary language | TypeScript |
| Repo size (approx) | 729 KB |
| Complexity tier | Focused Product |
| Estimated specialized hours | 420 |
| Loaded rate used | USD $175 / hr |
| **Reproduction cost** | **USD $73,500** |
| **Commercial asking price** | **USD $95,000** (floor ≥ $80,000) |

**Product thesis:** Inspect TLS certificates and handshake policy. JSON and SARIF output for CI.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### unlearning-experiment

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/unlearning-experiment |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 15230 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### veyra-scientific

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/veyra-scientific |
| Visibility | public |
| Primary language | Python |
| Repo size (approx) | 2645 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Veyra is a Cursor-native reproducible scientific computing environment. Define a version-controlled experiment, validate its schema and dimensions, execute it through the local laboratory kernel, inspect its dependency graph, and retain the result, methods, and environment evidence. 

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### virion

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/virion |
| Visibility | private |
| Primary language | Python |
| Repo size (approx) | 919 KB |
| Complexity tier | Systems / Deep IP |
| Estimated specialized hours | 900 |
| Loaded rate used | USD $200 / hr |
| **Reproduction cost** | **USD $180,000** |
| **Commercial asking price** | **USD $220,000** (floor ≥ $80,000) |

**Product thesis:** Virion is a fully open, ROCm-first derived model family whose core objective is to specialize Qwen2.5-Coder-7B for superior software engineering capabilities through efficient training.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### wallcore

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/wallcore |
| Visibility | private |
| Primary language | HTML |
| Repo size (approx) | 2466 KB |
| Complexity tier | Product System |
| Estimated specialized hours | 650 |
| Loaded rate used | USD $185 / hr |
| **Reproduction cost** | **USD $120,250** |
| **Commercial asking price** | **USD $150,000** (floor ≥ $80,000) |

**Product thesis:** Proprietary / private product IP under active development.

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

### wiretap

| Field | Detail |
| :--- | :--- |
| URL | https://github.com/theworker02/wiretap |
| Visibility | public |
| Primary language | Go |
| Repo size (approx) | 276 KB |
| Complexity tier | Specialized Utility / Module |
| Estimated specialized hours | 320 |
| Loaded rate used | USD $165 / hr |
| **Reproduction cost** | **USD $52,800** |
| **Commercial asking price** | **USD $80,000** (floor ≥ $80,000) |

**Product thesis:** Evidence-backed binary protocol inference: offline, deterministic, explainable

**What a buyer would pay to rebuild:** Domain discovery, architecture, implementation parity, test harnesses, CI, packaging, docs, and commercial diligence materials. Faster path is acquisition of this repository's transferable IP rather than greenfield recreation.

**Included in transfer (typical):** source tree, documentation, tests/CI present in-repo, brand/docs under docs/ and acquisition briefs (ACQUISITION.md, COMMERCIAL.md) where present.

**Not automatically included:** production secrets, hosted accounts, trademarks outside repo assets, post-close engineering retainers (negotiable).

---

## Notes for buyers

1. **Floor is intentional.** Even compact, well-packaged modules carry proprietary commercial rights, JSR/npm/crates/gem packaging, CI provenance, and diligence rooms — the asking floor is **USD $80,000**.
2. **Deep systems price higher.** Robotics OS, IDE forks, connectomics, distributed compute, OEM automotive packs, and quantum/materials proposals sit in the $150k–$450k+ band.
3. **Public ≠ free.** Public/source-available visibility does not grant production or redistribution rights where LICENSE / COMMERCIAL.md say proprietary.
4. **Contact:** GitHub [@theworker02](https://github.com/theworker02) · [thanks.dev/u/gh/theworker02](https://thanks.dev/u/gh/theworker02)

*Generated 2026-09-24 for portfolio diligence. Update after material product changes.*

