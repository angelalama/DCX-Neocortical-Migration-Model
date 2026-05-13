# DCX-Neocortical-Migration-Model
Agent-based neurocomputational model of DCX-dependent neuronal migration and neocortical lamination using NetLogo.

## Overview
This project explores the role of doublecortin (DCX) in neuronal migration and cortical layer formation from  an evolutionary-development (evo-devo) perspective. The model was developed as part of ongoing research in computational neuroscience and neocortical evolution at the UNESCO UniTwin e-Lab on Morphodynamics, Neuroscience and Behavior.
Using an agent-based approach implemented in Netlogo, the simulations investigate how different levels of DCX loss-of-function affect radial neuronal migration and the formation of neocortical layers.

## Scientific Background
The emergence of the neocortex has been associated with evolutionary adaptations related to sensory integration, spatial navigation, and increasing cortical complexity. DCX (doublecortin) is a microtubule-associated protein involved in neuronal migration during cortical development, and alterations in DCX function are known to affect cortical organization.
This project investigate how reduced DCX function may alter migration dynamics and laminar organization during neocortical development.


## Hypothesis
Reduced DCX funciton disrupts radial neuronal migration, preventing neurons from reaching their correct cortical positions, particularly in superficial layers.

## Methods
- Agent-based computational modeling
- NetLogo simulation environment
- Evo-devo modeling framework
- Differential migration dynamics under:
   - 20% DCX loss-of-function
   - 40% DCX loss-of-funciton
   - 60% DCX loss-of-function
- Three simulation replicates per condition
  he model integrates: neuronal migration, cortical layer formation, and apoptosis-related mechanisms.

## Simulation Overview
Neurons originate in the intermediate zone and migrate radially toward deep and superficial cortical layers.
The simulations reproduce a typical development sequence in which neurons first populate deep cortical regions (Layer 6) and subsequently superficial regions (Layer 2).
![NetLogo Simulation] (figures/NetLogo_interface.png)

## Results
The simulations show a dose-dependent reduction in neuronal mmigration under increasing DCX loss-of-function conditions.

### Layer 6
Intermediate and severe DCX disruption produced the strongest migration deficits, with the most severe condition showing an approximately tenfold decrease relative to control simulations.

### Layer 2
Migration toward superficial layers also decreased progressively, with an approximately fivefold reduction under severe DCX disruption.

These findings suggest that DCX may have contributed to critical migratory mechanisms associated with the evolution of gyrencephalic brains
![Migration Results] (figures/Migration_results.png)

## Computational Tools
1. NetLogo
2. Python
3. Agent-based modeling
4. Dynamical systems approaches

## Future Directions
Future versions of the model aim to incorporate:
- Biologically realistic neuronal dynamics
- Synaptic interactions
- Connectivity analysis
- Multiescale simulation approaches integrating circuit and whole-brain dynamics

## Repository Structure
model/       -> NetLogo simulation files
analysis/    -> Python/R analysis scripts
results/     -> Simulations outputs and plots
figures/     -> Figures and screenshots
docs/        -> Abstracts and supplementary documents

## Author
Developed by Angela Lama Vargas
UNESCO UniTwin e-Lab on Morphodynamics, Neuroscience and Behavior

This project was developed as part of ongoing research in computational neuroscience and neocortical evolution

## Keywords
Computational neuroscience - neuronal migration - DCX - neocortex - agent-based modeling - evo-devo - cortical lamination - NetLogo

