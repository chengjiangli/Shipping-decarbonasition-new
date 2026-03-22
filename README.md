# Shipping-decarbonisation-new

**Integrated Assessment of Alternative Marine Fuels for the Asia-Europe Green Shipping Corridor Through 2050**

This repository hosts the supporting data and models for an integrated assessment of low-carbon shipping pathways. The work evaluates alternative marine fuels using a hybrid approach combining life cycle assessment (LCA) and system dynamics (SD) modeling.

## Repository Structure

- `Supplementary dataset.pdf`  
  Contains the upstream calculation data input and raw data used for life cycle assessment. This dataset is designed to be imported into **GaBi** (LCA software) and a system dynamics model developed for **Vensim** to model the environmental performance of alternative marine fuels across their full life cycle (well-to-wake). It simulates the dynamic interactions among climate targets, energy demand, economic factors, and environmental performance. This model builds upon the LCA results from GABI and explores long-term decarbonisation trajectories under different policy and technology scenarios.

- `Climate-3E performance of alternate marine fuels`  
  Contains the data output of alternative marine fuels among climate targets, energy demand, economic factors, and environmental performance.

## Workflow Overview

1. **GaBi (LCA)**  
   - Import the supplementary dataset into GaBi.  
   - Perform life cycle inventory and impact assessment for candidate marine fuels (e.g., ammonia, methanol, hydrogen, etc.).  
   - Export key environmental indicators (e.g., GHG emissions, energy use) for use in the system dynamics model.

2. **Vensim PLE (System Dynamics)**  
   - Import the supplementary dataset into Vensim.  
   - Calibrate the model with LCA results and other exogenous inputs.  
   - Run simulations to analyze long-term decarbonisation pathways, policy implications, and feedback loops in the shipping sector.
