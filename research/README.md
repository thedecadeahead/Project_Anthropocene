# Research Library

The Project Anthropocene research library contains the evidence, source notes, models, assumptions, and open questions used to construct the setting.

Research is kept separate from canon so that contributors can inspect how a fictional outcome was derived.

## Show Your Work: The Master Bibliography

[`bibliography.md`](bibliography.md) is the single, one-stop index of every major source used across the project. Each entry links directly to a stable public source (DOI, report landing page, or dataset home) and lists the research notes that rely on it, so any canon claim can be traced back to its evidence in one step.

Every domain research note also carries a `## Sources` section whose citations link out directly and point back to the relevant section of the master bibliography. Start at the bibliography for a project-wide view, or at a note for the argument in context.

## Directory Structure

```text
research/
├── README.md
├── bibliography.md
├── 00_Research_Questions.md
├── climate/
├── agriculture/
├── water/
├── ecology/
├── health/
├── demography/
├── migration/
├── economics/
├── infrastructure/
├── energy/
├── technology/
├── geopolitics/
├── governance/
├── conflict/
└── historical_analogues/
```

Directories should be created as research is added rather than filled with empty placeholders.

## Purpose of Each Domain

- **climate** — temperature, precipitation, extreme weather, sea level, cryosphere, and tipping risks.
- **agriculture** — crop physiology, food systems, fisheries, livestock, soils, and agricultural adaptation.
- **water** — groundwater, river systems, drought, desalination, allocation, and water conflict.
- **ecology** — biodiversity, ecosystem shifts, invasive species, extinction, and rewilding.
- **health** — heat mortality, disease, nutrition, mental health, and medical-system resilience.
- **demography** — population growth, decline, age structure, fertility, mortality, and urbanization.
- **migration** — internal displacement, international migration, managed retreat, and refugee policy.
- **economics** — insurance, finance, labor, trade, inequality, and systemic risk.
- **infrastructure** — housing, transportation, communications, ports, grids, and public works.
- **energy** — generation, storage, fuels, grids, extraction, and transition pathways.
- **technology** — artificial intelligence, robotics, biotechnology, materials, manufacturing, and medicine.
- **geopolitics** — borders, strategic resources, alliances, state competition, and regional power shifts.
- **governance** — state capacity, local government, emergency authority, institutions, and legitimacy.
- **conflict** — civil unrest, interstate war, insurgency, organized crime, and security responses.
- **historical_analogues** — past societies facing environmental, economic, epidemiological, or institutional shocks.

## File Naming

Use descriptive lowercase file names separated by underscores.

Examples:

```text
wheat_heat_stress.md
mississippi_basin_drought.md
coastal_insurance_retreat.md
late_bronze_age_systemic_collapse.md
```

Avoid generic names such as `notes.md` or `sources.md` unless the file is an index.

## Research Status

Research files should use one of these statuses:

- `seed` — question or source lead with minimal analysis.
- `active` — research in progress.
- `review` — ready for fact-checking and methodological review.
- `stable` — sufficiently supported for current worldbuilding use.
- `superseded` — retained for history but replaced by stronger work.

## Required Metadata

Substantial research notes should begin with YAML metadata:

```yaml
---
title: Example Topic
status: active
domain: agriculture
regions:
  - global
time_period:
  - 2025-2100
researchers:
  - GitHubUsername
last_reviewed: 2026-07-12
sources_count: 0
---
```

## Research Workflow

1. Start with a specific question.
2. Search for primary and synthesis sources.
3. Record scenario assumptions and geographic scope.
4. Separate observed findings from projected outcomes.
5. Identify uncertainty and disagreement.
6. Derive possible worldbuilding implications.
7. Propose canon only after the research is reviewable.

## Relationship to Canon

Research does not become canon automatically.

A research note may support multiple possible futures. Canon should select one pathway deliberately and explain why that pathway was chosen.

When canon relies on a research note, link the files in both directions whenever practical.