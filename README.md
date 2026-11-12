# ionian
[![DOI](https://zenodo.org/badge/1455219930.svg)](https://doi.org/10.5281/zenodo.24163002)

This project develops an agent-based model that explores the relationship between maritime geography, resource control, and emergent social structures in the Late Helladic IIIC Ionian and Adriatic seas.

The model aims to simulate how geographical maritime bottlenecks naturally lead to localized power centers. It is designed as an exploratory test to help investigate if social structures emerge organically from socially blind environmental conditions.

- **Agents:** Local groups / Settlements.
- **Environment:** Spatial grid representing the Ionian and Adriatic maritime landscape (environmental resistance).
- **Key processes:** Maritime traffic movement, bottleneck interception, population attraction, and wealth accumulation (imports).
- **Temporal scale:** Abstract simulation ticks representing the LH IIIC post-palatial transition.

```text

model/       → NetLogo model files (.nlogo)
data/        → Input datasets (CSV, shapefiles, etc.)
results/     → Simulation outputs
analysis/    → R scripts for network and centrality analysis
docs/        → Documentation and notes

```text


1. [NetLogo](https://ccl.northwestern.edu/netlogo/)
2. [R](https://www.r-project.org/) (optional, for spatial network analysis)

1. Open `model/ionian_trade_v1.nlogo` in NetLogo.  
2. Use the Interface tab to initialise and run the simulation.  
3. Use **BehaviorSpace** (NetLogo menu → Tools → BehaviorSpace) to run batch experiments.  
4. Store output files in the `results/` folder for later analysis.

Simulation results will include key indicators such as settlement carrying capacity (population) and prestige goods accumulation. Analysis scripts in `analysis/` will generate plots comparing the emergent social patterns to the LH IIIC archaeological record.

This project is licensed under the [LICENSE](LICENSE) file included in the repository.

If you use or adapt this model, please cite:
> Vereketi, Ermioni. (2026). *ionian: An agent-based model of LH IIIC maritime trade*. Version 0.1. DOI: [https://doi.org/10.5281/zenodo.24163003](https://doi.org/10.5281/zenodo.24163003)

This work was developed as part of the course *Agent-based Modelling for Archaeologists: From Concept to Application and Publication*, taught by Andreas Angourakis at the University of Cologne.
