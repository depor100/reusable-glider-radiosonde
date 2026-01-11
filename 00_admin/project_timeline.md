# Reusable Glider Radiosonde — Project Timeline

This document defines the **chronological project timeline** for the development of a reusable glider radiosonde, from initial research to a system potentially suitable for large‑scale real‑world deployment. The timeline is **phase‑based** following waterfall methodology practices.

Each phase includes:

- **Purpose** (why the phase exists)
- **Key activities** (issues to be addressed)
- **Concrete deliverables** (outputs that must exist before progressing)



---



## Phase 0 — Problem Framing & Project Definition

### Purpose

- Establish a clear, defensible problem statement and define what “success” means relative to existing radiosonde systems
- No formal system requirements are defined at this stage

### Key Activities

- Define environmental, economic, and operational motivations
- Identify primary stakeholders
- Define system boundaries and intended use cases

### Deliverables

- Project charter
  - State aims and objectives
  - State scope of the project (Explicit non‑goals and out‑of‑scope items)
  - Set high‑level comparative success criteria (compared to benchmark in phase 1)
    - cost
    - data quality
    - sustainability
    - regulatory compliance
    - operational capabilities



---



## Phase 1 — Benchmarking Review of Existing Radiosonde Systems

### Purpose

- Establish a **quantitative operational baseline** for existing radiosonde systems against which all subsequent design decisions and performance claims will be evaluated
- This phase characterises the current state of operational radiosonde deployments in terms of economic cost, technical capability, and environmental impact

### Key Activities

- Identify representative commercially deployed radiosonde systems used in European operational practice
- Collect quantitative data on cost, performance, deployment, and disposal
- Assess compliance with relevant meteorological, aviation, and telecommunications standards
- Extrapolate economic and environmental impacts to regional and global deployment scales

### Deliverables

#### Economic Benchmarking

Quantify the economic characteristics of current radiosonde operations.

- Hardware unit cost and per-launch operational cost
- Typical launch frequency and annual deployment rates
- Cost per vertical atmospheric profile and per unit of usable data
- Extrapolated annual expenditure at:
  - UK scale
  - European scale
  - Global scale
- Identification of dominant cost drivers (manufacture, logistics, unrecovered hardware)

#### Technical Benchmarking

Characterise the technical baseline of existing radiosonde systems.

- Typical operational mission profile (launch, ascent, termination)
- Sensor suite, sampling rates, and measurement accuracy
- Onboard hardware and software architecture
- Communications systems, frequencies, and data pipelines
- Power systems, endurance, and mass breakdown
- Compliance with:
  - Meteorological measurement standards
  - Aviation and airspace regulations
  - Spectrum allocation and telemetry regulations

#### Environmental Benchmarking

Quantify the environmental consequences of current radiosonde practices.

- Recovery rates and expected loss per launch
- Materials unrecovered or released into the environment per mission
- End-of-life pathways (land, ocean, degradation)
- Estimated annual material loss at:
  - UK scale
  - European scale
  - Global scale
- Identification of dominant environmental impact drivers

#### Benchmark Summary

- Consolidated reference baseline for:
  - Economic cost
  - Technical performance
  - Regulatory constraints
  - Environmental impact
Explicit identification of limitations and inefficiencies in current radiosonde systems




---



## Phase 2 — Review of Reusable & Recoverable Radiosonde Concepts

### Purpose

Understand the current state of the art in reusable, steerable, or recoverable atmospheric sensing platforms.

### Key Activities

- Review glider‑based, parafoil‑based, and UAV‑assisted radiosonde concepts
- Identify prior failures, limitations, and unresolved challenges
- Analyse recovery strategies and autonomy approaches
- Identify regulatory and operational barriers encountered historically

### Deliverables

- State‑of‑the‑art review document
- Gap analysis identifying what remains unsolved or underexplored
- Initial justification for a glider‑based approach



---



## Phase 3 — Regulatory & Standards Landscape Analysis

### Purpose

Ensure early alignment with real‑world deployment requirements and avoid late‑stage infeasibility.

### Key Activities

- Identify relevant aviation authorities and airspace regulations
- Review standards for meteorological instrumentation
- Investigate spectrum regulations for telemetry
- Identify certification or approval pathways

### Deliverables

- Regulatory requirements summary
- Compliance checklist (airworthiness, tracking, failsafes, data standards)
- Identified constraints shaping system design



---



## Phase 4 — System Architecture & Concept of Operations (CONOPS)

### Purpose

Define the complete system lifecycle before detailed design begins.

### Key Activities

- Define mission phases from launch to recovery
- Decompose the system into subsystems
- Define ground segment and data flow
- Identify primary failure modes

### Deliverables

- System block diagram
- Mission phase diagram
- High‑level failure mode list
- Updated success criteria aligned with constraints



---



## Phase 5 — First‑Order Feasibility & Sizing Analysis

### Purpose

Verify that the proposed concept is physically and operationally plausible.

### Key Activities

- Glide performance vs wind envelope analysis
- Mass and wing loading estimation
- Power and thermal feasibility at altitude
- Communications link budget estimation

### Deliverables

- Feasibility analysis report
- Preliminary mass, power, and cost budgets
- Go / No‑Go decision for detailed development



---



## Phase 6 — Modelling, Simulation & Autonomy Development

### Purpose

De‑risk the project by validating guidance and recovery logic in simulation.

### Key Activities

- Develop simplified flight dynamics models
- Implement wind field and uncertainty models
- Design guidance and navigation logic
- Perform Monte Carlo recovery simulations

### Deliverables

- Simulation codebase
- Autonomy logic documentation
- Recovery probability and performance envelopes



---



## Phase 7 — Detailed Design & Trade Studies

### Purpose

Freeze system design choices based on quantitative evidence.

### Key Activities

- Airframe configuration trade studies
- Avionics and sensor selection
- Communications architecture selection
- Manufacturing and assembly planning

### Deliverables

- Trade study reports
- Frozen system architecture
- Updated mass, power, and cost budgets



---



## Phase 8 — Prototype Development: Glide‑Only Vehicle

### Purpose

Validate aerodynamic performance and stability without full system complexity.

### Key Activities

- Build first physical prototype
- Conduct controlled glide tests
- Instrument vehicle for data collection

### Deliverables

- Glide‑only prototype
- Flight test reports
- Empirical glide performance data



---



## Phase 9 — Prototype Development: Autonomous Glide‑Back System

### Purpose

Demonstrate closed‑loop autonomy and recovery capability.

### Key Activities

- Integrate avionics and autonomy stack
- Conduct autonomous flight testing
- Evaluate navigation accuracy and robustness

### Deliverables

- Autonomous prototype
- Recovery accuracy statistics
- Failure and robustness analysis



---



## Phase 10 — High‑Altitude & Operational Testing

### Purpose

Validate performance under representative radiosonde operating conditions.

### Key Activities

- Balloon deployment integration
- Cold‑soak and low‑pressure testing
- End‑to‑end data collection trials

### Deliverables

- High‑altitude test reports
- Data quality comparison vs benchmark radiosonde
- Recovery success statistics



---



## Phase 11 — Scalability, Economics & Deployment Assessment

### Purpose

Evaluate readiness for large‑scale real‑world adoption.

### Key Activities

- Lifecycle cost modelling
- Manufacturing scalability assessment
- Operational deployment analysis
- Regulatory readiness reassessment

### Deliverables

- Cost‑per‑flight and amortisation model
- Scalability and manufacturability report
- Deployment readiness assessment



---



## Phase 12 — Documentation, Dissemination & Knowledge Transfer

### Purpose

Translate engineering work into reproducible, shareable knowledge.

### Key Activities

- Compile technical documentation
- Prepare academic or technical publications
- Open‑source selected components where appropriate

### Deliverables

- Complete system documentation
- Final technical report or academic paper
- Supplementary materials (datasets, code, appendices)



---



## Final Outcome

A reusable glider radiosonde system that has been **engineered, validated, and documented** to a standard suitable for serious consideration by research institutions, industry partners, or operational meteorological agencies.