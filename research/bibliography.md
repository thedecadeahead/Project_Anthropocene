# Master Bibliography

This file is the single index of every major source used across Project Anthropocene. It is the project's "show your work" reference: each entry links directly to a stable public source, and lists the research notes that rely on it.

Detailed argument and interpretation live in the domain-specific research files. This bibliography exists to prevent duplicate work, standardize citations, expose our evidence base, and record which sources materially influence canon.

## How to Read This File

Every source is a single linked entry in this format:

```text
- **[Linked title](stable URL or DOI)** — Author or institution, year. *Type.* `STATUS`
  Used in: [note](relative/path.md)
```

- The **link** points to a stable identifier (DOI, report landing page, or dataset home) rather than a temporary URL wherever one exists.
- **Used in** cross-links to every research note that draws on the source, so canon can be traced back to evidence in one step.
- Series that publish annually (e.g. FAO SOFI, IOM World Migration Report) link to the series landing page; consult the specific edition cited in the note.

## Status Tags

- `[FOUNDATIONAL]` — central synthesis or dataset used across the project.
- `[DOMAIN]` — important within a specific research area.
- `[LEAD]` — promising source not yet fully reviewed.
- `[SUPERSEDED]` — replaced by a newer edition or stronger source.
- `[DISPUTED]` — findings are materially contested or difficult to reproduce.

## Source Record Template

For sources that warrant a full record (foundational or contested ones), append a detailed block using this template:

```markdown
### [Short Source Name]

- **Full citation:**
- **Type:** peer-reviewed article | assessment | dataset | technical report | book | journalism | other
- **Stable identifier:** DOI, ISBN, report number, or URL
- **Scenario or pathway:**
- **Key relevance:**
- **Used in:**
- **Limitations:**
- **Last checked:** YYYY-MM-DD
```

---

## Climate

- **[IPCC AR6 Working Group I — *Climate Change 2021: The Physical Science Basis*](https://www.ipcc.ch/report/ar6/wg1/)** — IPCC, 2021. *Assessment.* `[FOUNDATIONAL]`
  Used in: [climate/baseline_scenario.md](climate/baseline_scenario.md), [climate/sea_level_bounds.md](climate/sea_level_bounds.md)
- **[IPCC AR6 Working Group II — *Climate Change 2022: Impacts, Adaptation and Vulnerability*](https://www.ipcc.ch/report/ar6/wg2/)** — IPCC, 2022. *Assessment.* `[FOUNDATIONAL]`
  Used in: [agriculture/wheat_heat_risk.md](agriculture/wheat_heat_risk.md), [agriculture/multiple_breadbasket_failure.md](agriculture/multiple_breadbasket_failure.md), [water/water_stress_and_systemic_risk.md](water/water_stress_and_systemic_risk.md), [health/extreme_heat_and_habitability.md](health/extreme_heat_and_habitability.md), [demography/population_change_after_crisis.md](demography/population_change_after_crisis.md), [migration/climate_migration_and_destination_stress.md](migration/climate_migration_and_destination_stress.md), [economics/climate_insurance_retreat.md](economics/climate_insurance_retreat.md), [governance/state_capacity_and_emergency_rule.md](governance/state_capacity_and_emergency_rule.md), [conflict/climate_as_conflict_multiplier.md](conflict/climate_as_conflict_multiplier.md)
- **[IPCC AR6 Working Group III — *Climate Change 2022: Mitigation of Climate Change*](https://www.ipcc.ch/report/ar6/wg3/)** — IPCC, 2022. *Assessment.* `[FOUNDATIONAL]`
  Used in: [energy/grid_resilience_and_fragmentation.md](energy/grid_resilience_and_fragmentation.md)
- **[IPCC AR6 Synthesis Report — *Climate Change 2023*](https://www.ipcc.ch/report/ar6/syr/)** — IPCC, 2023. *Assessment.* `[FOUNDATIONAL]`
  Used in: [climate/baseline_scenario.md](climate/baseline_scenario.md), [climate/sea_level_bounds.md](climate/sea_level_bounds.md)
- **[UNEP *Emissions Gap Report 2025: Off Target*](https://www.unep.org/resources/emissions-gap-report-2025)** — UN Environment Programme, 2025. *Assessment.* `[FOUNDATIONAL]`
  Used in: [climate/baseline_scenario.md](climate/baseline_scenario.md)
- **[Sweet et al. — *Global and Regional Sea Level Rise Scenarios for the United States* (NOAA Technical Report NOS 01)](https://oceanservice.noaa.gov/hazards/sealevelrise/sealevelrise-tech-report.html)** — NOAA, 2022. *Technical report.* `[DOMAIN]`
  Used in: [climate/sea_level_bounds.md](climate/sea_level_bounds.md)

## Agriculture and Food Systems

- **[Asseng, S., et al. "Rising temperatures reduce global wheat production."](https://doi.org/10.1038/nclimate2470)** — *Nature Climate Change* 5, 143–147, 2015. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [agriculture/wheat_heat_risk.md](agriculture/wheat_heat_risk.md)
- **[Zhao, C., et al. "Temperature increase reduces global yields of major crops in four independent estimates."](https://doi.org/10.1073/pnas.1701762114)** — *PNAS* 114(35), 2017. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [agriculture/wheat_heat_risk.md](agriculture/wheat_heat_risk.md)
- **[Saini, H. S., Sedgley, M., and Aspinall, D. "Effect of heat stress during floral development on pollen tube growth and ovary anatomy in wheat."](https://doi.org/10.1071/PP9830137)** — *Australian Journal of Plant Physiology* 10(2), 137–144, 1983. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [agriculture/wheat_heat_risk.md](agriculture/wheat_heat_risk.md)
- **[Sarkar, S., et al. "Tolerance mechanisms for breeding wheat against heat stress: A review."](https://doi.org/10.1016/j.sajb.2021.01.003)** — *South African Journal of Botany* 138, 262–277, 2021. *Peer-reviewed review.* `[DOMAIN]`
  Used in: [agriculture/wheat_heat_risk.md](agriculture/wheat_heat_risk.md)
- **[Kornhuber, K., et al. "Risks of synchronized low yields are underestimated in climate and crop model projections."](https://doi.org/10.1038/s41467-023-38906-7)** — *Nature Communications* 14, 3528, 2023. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [agriculture/multiple_breadbasket_failure.md](agriculture/multiple_breadbasket_failure.md)
- **[Puma, M. J., Bose, S., Chon, S. Y., and Cook, B. I. "Assessing the evolving fragility of the global food system."](https://doi.org/10.1088/1748-9326/10/2/024007)** — *Environmental Research Letters* 10(2), 024007, 2015. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [agriculture/multiple_breadbasket_failure.md](agriculture/multiple_breadbasket_failure.md)
- **[FAO *The State of Food Security and Nutrition in the World* (SOFI)](https://www.fao.org/publications/sofi)** — FAO, annual series. *Assessment.* `[DOMAIN]`
  Used in: [agriculture/multiple_breadbasket_failure.md](agriculture/multiple_breadbasket_failure.md)

## Water

- **[UNESCO / UN-Water *World Water Development Report 2024: Water for Prosperity and Peace*](https://www.unesco.org/reports/wwdr/en/2024)** — UNESCO, 2024. *Assessment.* `[DOMAIN]`
  Used in: [water/water_stress_and_systemic_risk.md](water/water_stress_and_systemic_risk.md)
- **[FAO AQUASTAT — global water information system](https://www.fao.org/aquastat/en/)** — FAO. *Dataset.* `[DOMAIN]`
  Used in: [water/water_stress_and_systemic_risk.md](water/water_stress_and_systemic_risk.md)
- **[WRI Aqueduct Water Risk Atlas](https://www.wri.org/aqueduct)** — World Resources Institute. *Dataset.* `[DOMAIN]`
  Used in: [water/water_stress_and_systemic_risk.md](water/water_stress_and_systemic_risk.md)

## Ecology and Biodiversity

_No sources cataloged yet._

## Health

- **[Raymond, C., Matthews, T., and Horton, R. M. "The emergence of heat and humidity too severe for human tolerance."](https://doi.org/10.1126/sciadv.aaw1838)** — *Science Advances* 6(19), eaaw1838, 2020. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [health/extreme_heat_and_habitability.md](health/extreme_heat_and_habitability.md)
- **[Vecellio, D. J., Wolf, S. T., Cottle, R. M., and Kenney, W. L. "Evaluating the 35 °C wet-bulb temperature adaptability threshold for young, healthy subjects (PSU HEAT Project)."](https://doi.org/10.1152/japplphysiol.00738.2021)** — *Journal of Applied Physiology* 132(2), 340–345, 2022. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [health/extreme_heat_and_habitability.md](health/extreme_heat_and_habitability.md)
- **[Sherwood, S. C., and Huber, M. "An adaptability limit to climate change due to heat stress."](https://doi.org/10.1073/pnas.0913352107)** — *PNAS* 107(21), 2010. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [health/extreme_heat_and_habitability.md](health/extreme_heat_and_habitability.md)
- **[ISO 7243:2017 — Ergonomics of the thermal environment (WBGT index)](https://www.iso.org/standard/67188.html)** — International Organization for Standardization, 2017. *Standard.* `[DOMAIN]`
  Used in: [health/extreme_heat_and_habitability.md](health/extreme_heat_and_habitability.md)

## Demography and Migration

- **[UN DESA Population Division — *World Population Prospects 2024*](https://population.un.org/wpp/)** — United Nations, 2024. *Dataset.* `[FOUNDATIONAL]`
  Used in: [demography/population_change_after_crisis.md](demography/population_change_after_crisis.md)
- **[UNFPA *State of World Population*](https://www.unfpa.org/swop)** — United Nations Population Fund, annual series. *Assessment.* `[DOMAIN]`
  Used in: [demography/population_change_after_crisis.md](demography/population_change_after_crisis.md)
- **[Institute for Health Metrics and Evaluation (IHME)](https://www.healthdata.org/)** — IHME. *Dataset / research program.* `[DOMAIN]`
  Used in: [demography/population_change_after_crisis.md](demography/population_change_after_crisis.md)
- **[Clement, V., et al. *Groundswell Part 2: Acting on Internal Climate Migration*](https://openknowledge.worldbank.org/handle/10986/36248)** — World Bank, 2021. *Technical report.* `[DOMAIN]`
  Used in: [migration/climate_migration_and_destination_stress.md](migration/climate_migration_and_destination_stress.md)
- **[IDMC *Global Report on Internal Displacement* (GRID)](https://www.internal-displacement.org/global-report/grid2024/)** — Internal Displacement Monitoring Centre, annual series. *Assessment.* `[DOMAIN]`
  Used in: [migration/climate_migration_and_destination_stress.md](migration/climate_migration_and_destination_stress.md)
- **[IOM *World Migration Report*](https://worldmigrationreport.iom.int/)** — International Organization for Migration, series. *Assessment.* `[DOMAIN]`
  Used in: [migration/climate_migration_and_destination_stress.md](migration/climate_migration_and_destination_stress.md)
- **[UNHCR — Environment, disasters and climate change guidance](https://www.unhcr.org/what-we-do/build-better-futures/environment-disasters-and-climate-change)** — UN High Commissioner for Refugees. *Policy guidance.* `[DOMAIN]`
  Used in: [migration/climate_migration_and_destination_stress.md](migration/climate_migration_and_destination_stress.md)

## Economics and Insurance

- **[U.S. Treasury Federal Insurance Office — *Analyses of U.S. Homeowners Insurance Markets, 2018–2022: Climate-Related Risks and Other Factors*](https://home.treasury.gov/policy-issues/financial-markets-financial-institutions-and-fiscal-service/federal-insurance-office)** — U.S. Department of the Treasury, 2025. *Technical report.* `[DOMAIN]`
  Used in: [economics/climate_insurance_retreat.md](economics/climate_insurance_retreat.md)
- **[U.S. GAO — Climate change and federal fiscal exposure (High Risk Series)](https://www.gao.gov/climate-change)** — U.S. Government Accountability Office, recurring. *Technical report.* `[DOMAIN]`
  Used in: [economics/climate_insurance_retreat.md](economics/climate_insurance_retreat.md)
- **[Financial Stability Oversight Council — *Report on Climate-Related Financial Risk*](https://home.treasury.gov/policy-issues/financial-markets-financial-institutions-and-fiscal-service/fsoc/studies-and-reports)** — FSOC, 2021. *Technical report.* `[DOMAIN]`
  Used in: [economics/climate_insurance_retreat.md](economics/climate_insurance_retreat.md)

## Infrastructure and Energy

- **[IEA *Electricity Grids and Secure Energy Transitions*](https://www.iea.org/reports/electricity-grids-and-secure-energy-transitions)** — International Energy Agency, 2023. *Assessment.* `[DOMAIN]`
  Used in: [energy/grid_resilience_and_fragmentation.md](energy/grid_resilience_and_fragmentation.md)
- **[IEA *Renewables 2024*](https://www.iea.org/reports/renewables-2024)** — International Energy Agency, 2024. *Assessment.* `[DOMAIN]`
  Used in: [energy/grid_resilience_and_fragmentation.md](energy/grid_resilience_and_fragmentation.md)
- **[NERC *Long-Term Reliability Assessment*](https://www.nerc.com/pa/RAPA/ra/Pages/default.aspx)** — North American Electric Reliability Corporation, annual series. *Assessment.* `[DOMAIN]`
  Used in: [energy/grid_resilience_and_fragmentation.md](energy/grid_resilience_and_fragmentation.md)
- **[U.S. DOE Grid Deployment Office — grid resilience and transformer supply-chain work](https://www.energy.gov/topics/grid-deployment-and-transmission)** — U.S. Department of Energy. *Technical report.* `[DOMAIN]`
  Used in: [energy/grid_resilience_and_fragmentation.md](energy/grid_resilience_and_fragmentation.md)
- **[ITU — Emergency telecommunications and disaster resilience](https://www.itu.int/en/ITU-D/Emergency-Telecommunications/Pages/default.aspx)** — International Telecommunication Union. *Policy guidance.* `[DOMAIN]`
  Used in: [infrastructure/communications_after_fragmentation.md](infrastructure/communications_after_fragmentation.md)
- **[Matracia, M., Saeed, N., Kishk, M. A., and Alouini, M.-S. "Post-Disaster Communications: Enabling Technologies, Architectures, and Open Challenges."](https://doi.org/10.1109/OJCOMS.2022.3192040)** — *IEEE Open Journal of the Communications Society* 3, 1177–1205, 2022. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [infrastructure/communications_after_fragmentation.md](infrastructure/communications_after_fragmentation.md)
- **[IETF RFC 9171 — Bundle Protocol Version 7 (Delay-Tolerant Networking)](https://datatracker.ietf.org/doc/rfc9171/)** — Internet Engineering Task Force, 2022. *Standard.* `[DOMAIN]`
  Used in: [infrastructure/communications_after_fragmentation.md](infrastructure/communications_after_fragmentation.md)
- **[TeleGeography Submarine Cable Map](https://www.submarinecablemap.com/)** — TeleGeography. *Dataset.* `[DOMAIN]`
  Used in: [infrastructure/communications_after_fragmentation.md](infrastructure/communications_after_fragmentation.md)
- **[UNIDO *Industrial Development Report*](https://www.unido.org/idr)** — UN Industrial Development Organization, series. *Assessment.* `[DOMAIN]`
  Used in: [infrastructure/industrial_capacity_and_maintenance.md](infrastructure/industrial_capacity_and_maintenance.md)
- **[U.S. DOE *2023 Critical Materials Assessment*](https://www.energy.gov/eere/wind/articles/doe-announces-new-critical-materials-assessment-and-funding-program)** — U.S. Department of Energy, 2023. *Technical report.* `[DOMAIN]`
  Used in: [infrastructure/industrial_capacity_and_maintenance.md](infrastructure/industrial_capacity_and_maintenance.md)
- **[USGS *Mineral Commodity Summaries*](https://www.usgs.gov/centers/national-minerals-information-center/mineral-commodity-summaries)** — U.S. Geological Survey, annual series. *Dataset.* `[DOMAIN]`
  Used in: [infrastructure/industrial_capacity_and_maintenance.md](infrastructure/industrial_capacity_and_maintenance.md)
- **[IEA — Critical minerals](https://www.iea.org/topics/critical-minerals)** — International Energy Agency. *Assessment / dataset.* `[DOMAIN]`
  Used in: [infrastructure/industrial_capacity_and_maintenance.md](infrastructure/industrial_capacity_and_maintenance.md)

## Technology

- **[IEA *Electricity 2024* — data-centre electricity-demand analysis](https://www.iea.org/reports/electricity-2024)** — International Energy Agency, 2024. *Assessment.* `[DOMAIN]`
  Used in: [technology/ai_robotics_survival.md](technology/ai_robotics_survival.md)
- **[NIST *Artificial Intelligence Risk Management Framework 1.0*](https://www.nist.gov/itl/ai-risk-management-framework)** — National Institute of Standards and Technology, 2023. *Framework.* `[DOMAIN]`
  Used in: [technology/ai_robotics_survival.md](technology/ai_robotics_survival.md)
- **[IFR *World Robotics*](https://ifr.org/worldrobotics/)** — International Federation of Robotics, annual series. *Dataset.* `[DOMAIN]`
  Used in: [technology/ai_robotics_survival.md](technology/ai_robotics_survival.md)
- **[SIA & BCG *Strengthening the Global Semiconductor Supply Chain in an Uncertain Era*](https://www.semiconductors.org/strengthening-the-global-semiconductor-supply-chain-in-an-uncertain-era/)** — Semiconductor Industry Association & Boston Consulting Group, 2021. *Technical report.* `[DOMAIN]`
  Used in: [technology/semiconductor_supply_chain.md](technology/semiconductor_supply_chain.md)
- **[SIA & BCG *Emerging Resilience in the Semiconductor Supply Chain*](https://www.semiconductors.org/emerging-resilience-in-the-semiconductor-supply-chain/)** — Semiconductor Industry Association & Boston Consulting Group, 2024. *Technical report.* `[DOMAIN]`
  Used in: [technology/semiconductor_supply_chain.md](technology/semiconductor_supply_chain.md)
- **[Khan, S. M., Mann, A., and Peterson, D. *The Semiconductor Supply Chain: Assessing National Competitiveness*](https://cset.georgetown.edu/publication/the-semiconductor-supply-chain/)** — Center for Security and Emerging Technology (CSET), Georgetown University, 2021. *Technical report.* `[DOMAIN]`
  Used in: [technology/semiconductor_supply_chain.md](technology/semiconductor_supply_chain.md)
  _Note: earlier note text attributed this title to the U.S. Department of Commerce; the exact-title report is the CSET issue brief cited here. Verify before relying on the attribution in canon._
- **[U.S. DOE — *Semiconductor Supply Chain Deep Dive Assessment*](https://www.osti.gov/biblio/1871585)** — U.S. Department of Energy, 2022. *Technical report.* `[DOMAIN]`
  Used in: [technology/semiconductor_supply_chain.md](technology/semiconductor_supply_chain.md)

## Governance, Geopolitics, and Conflict

- **[OECD *States of Fragility*](https://www3.compareyourcountry.org/states-of-fragility/)** — OECD, series. *Assessment / dataset.* `[DOMAIN]`
  Used in: [governance/state_capacity_and_emergency_rule.md](governance/state_capacity_and_emergency_rule.md)
- **[World Bank Worldwide Governance Indicators](https://www.worldbank.org/en/publication/worldwide-governance-indicators)** — World Bank. *Dataset.* `[DOMAIN]`
  Used in: [governance/state_capacity_and_emergency_rule.md](governance/state_capacity_and_emergency_rule.md)
- **[UNDRR *Global Assessment Report on Disaster Risk Reduction* (GAR)](https://www.undrr.org/gar)** — UN Office for Disaster Risk Reduction, series. *Assessment.* `[DOMAIN]`
  Used in: [governance/state_capacity_and_emergency_rule.md](governance/state_capacity_and_emergency_rule.md)
- **[IMF — Climate change research](https://www.imf.org/en/Topics/climate-change)** — International Monetary Fund. *Research.* `[DOMAIN]`
  Used in: [governance/state_capacity_and_emergency_rule.md](governance/state_capacity_and_emergency_rule.md), [geopolitics/fragmentation_of_globalism.md](geopolitics/fragmentation_of_globalism.md)
- **[Mach, K. J., et al. "Climate as a risk factor for armed conflict."](https://doi.org/10.1038/s41586-019-1300-6)** — *Nature* 571, 193–197, 2019. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [conflict/climate_as_conflict_multiplier.md](conflict/climate_as_conflict_multiplier.md)
- **[von Uexkull, N., and Buhaug, H. "Security implications of climate change: A decade of scientific progress."](https://doi.org/10.1177/0022343320984210)** — *Journal of Peace Research* 58(1), 3–17, 2021. *Peer-reviewed article.* `[DOMAIN]`
  Used in: [conflict/climate_as_conflict_multiplier.md](conflict/climate_as_conflict_multiplier.md)
- **[SIPRI — Climate change and risk](https://www.sipri.org/research/peace-and-development/climate-change-and-risk)** — Stockholm International Peace Research Institute. *Research.* `[DOMAIN]`
  Used in: [conflict/climate_as_conflict_multiplier.md](conflict/climate_as_conflict_multiplier.md)
- **[UNEP — Climate and security risks](https://www.unep.org/topics/climate-action/climate-and-security-risks)** — UN Environment Programme. *Research.* `[DOMAIN]`
  Used in: [conflict/climate_as_conflict_multiplier.md](conflict/climate_as_conflict_multiplier.md)
- **[WTO *World Trade Report*](https://www.wto.org/english/res_e/publications_e/wtr_e.htm)** — World Trade Organization, series. *Assessment.* `[DOMAIN]`
  Used in: [geopolitics/fragmentation_of_globalism.md](geopolitics/fragmentation_of_globalism.md)
- **[UNCTAD *Review of Maritime Transport*](https://unctad.org/rmt)** — UN Conference on Trade and Development, annual series. *Assessment.* `[DOMAIN]`
  Used in: [geopolitics/fragmentation_of_globalism.md](geopolitics/fragmentation_of_globalism.md)
- **[World Bank *Global Economic Prospects*](https://www.worldbank.org/en/publication/global-economic-prospects)** — World Bank, series. *Assessment.* `[DOMAIN]`
  Used in: [geopolitics/fragmentation_of_globalism.md](geopolitics/fragmentation_of_globalism.md)
- **[OECD — Supply-chain resilience and strategic dependencies](https://www.oecd.org/en/topics/trade.html)** — OECD. *Research.* `[DOMAIN]`
  Used in: [geopolitics/fragmentation_of_globalism.md](geopolitics/fragmentation_of_globalism.md)

## Historical Analogues

_No sources cataloged yet._

## Bibliography Maintenance

- Prefer stable identifiers (DOI, report landing page) over temporary links.
- Note when a source has been superseded, but do not silently remove it if canon previously relied upon it.
- Record the date a web source was last checked in any detailed record block.
- Link every source to the research notes that use it, and keep those cross-links current when notes are renamed or added.
- Avoid placing a source in multiple sections; cross-reference it instead.
- Do not treat inclusion in this bibliography as endorsement of every claim in a source.
- Links last verified: 2026-07-16.
