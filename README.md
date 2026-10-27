# Wireless Power Transmission: Feasibility and Cost Analysis

A summary of whether long-distance wireless electricity transmission is physically possible, what has been demonstrated, and what it might cost, with a focus on space-based solar power (SBSP).

**Status:** Personal research project, last updated October 2026.
**Not original research.** This compiles public sources and adds clearly labeled estimates.

## Key findings

- **Physically possible:** Yes. Near-field coils, microwave beams, and small orbital demonstrations have all worked.
- **Not yet proven:** Gigawatt-scale beaming, kilometer-scale in-orbit assembly, and cost-competitive electricity.
- **Cost:** Published estimates for space solar range from about $2 to $12 per installed watt, versus about $0.70 to $1.20 per watt for terrestrial solar. That is roughly $2 to $12 billion per gigawatt-class plant.
- **Main cost driver:** Launch cost and satellite mass per kW. Claims that space solar becomes competitive near $200/kg come from companies with a stake in the outcome and should be treated cautiously.
- **Tesla's original idea** (using the Earth and atmosphere as a free conductor) is not viable. Energy always has to come from a transmitter.

## Repository contents

- `wireless_power_summary.xlsx`: the live model with formulas
- `feasibility.csv`, `cost_estimates.csv`, `launch_cost_scenarios.csv`, `players_timeline.csv`, `sources.csv`: read-only snapshots of each tab

The CSV files store calculated values, not formulas. Use the `.xlsx` to change inputs.

## What is in the spreadsheet

| Tab | Contents |
|---|---|
| Feasibility | What is proven, demonstrated, or not yet proven |
| Cost Estimates | Plant cost = capacity (GW) x $/W, premium vs terrestrial solar |
| Launch Cost Scenarios | Total launch cost at $3,000, $1,500, $500 and $200 per kg |
| Players & Timeline | Companies and organizations, milestones, target dates |
| Sources | Where each figure came from |

## How to use it

- **Blue cells** are inputs. Change them and the formulas update.
- **Yellow cells** are my own assumptions, not sourced figures: demo and pilot costs, the 5 kg/kW satellite mass, the 100-plant global network, and the $500/kg launch scenario.
- Open the `.xlsx` in Excel, LibreOffice, or Google Sheets.

## Method

1. Collected published cost ranges, launch prices, and demonstration milestones from public sources (listed below).
2. Built formulas so cost scales with plant capacity and launch price.
3. Labeled every figure that is an estimate rather than a cited number.

## Limitations

- Source figures are projections. An independent NASA analysis shows roughly 20-fold variation depending on assumptions.
- Company targets (for example, commercial supply by 2030) are claims, not results.
- Launch cost is only one component. Manufacturing, in-orbit assembly, ground receivers, and regulation are not fully modeled.
- Efficiency losses along the beam chain are not modeled in the cost sheet.
- Figures were gathered from article summaries. Check the original articles before relying on any number.

## Sources

- Sustainable Atlas, "Space-based solar power costs in 2026": https://sustainableatlas.org/post/cost-space-based-solar-power-energy-beaming-1808
- Space.com, coverage of SpaceX Starship and Virtus Solis: https://www.space.com/spacex-starship-solar-power-beaming-virtus-solis
- PowerMag report (July 9, 2026), as summarized by xenospectrum.com: https://xenospectrum.com/en/space-solar-power-nasa-lcoe-gap/
- SpaceQ, coverage of NASA's space-based solar power report: https://spaceq.ca/?p=35542
- Enlit, "Space-based solar needs cost and performance improvements says NASA" (Jan 2024): https://www.enlit.world/library/space-based-solar-needs-cost-and-performance-improvements-says-nasa
- Meticulous Research, SBSP market report (2026-2036): https://www.meticulousresearch.com/product/space-based-solar-power-market-6895
- SmallSat News, "Space Energy Initiative Calls for UK Co-Funding of Orbital Solar Power Demonstrator" (Aug 17, 2026): https://smallsatnews.com/2026/08/17/space-energy-initiative-calls-for-uk-co-funding-of-orbital-solar-power-demonstrator/
- Environment+Energy Leader, "Space-based solar power faces its infrastructure test": https://environmentenergyleader.com/stories/space-based-solar-power-faces-its-infrastructure-test,137561

## License

MIT. See `LICENSE`.

## Contributing

Corrections and better sources are welcome. Open an issue or pull request.
