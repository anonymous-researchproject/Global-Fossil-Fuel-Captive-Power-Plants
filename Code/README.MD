Code scripts for "A Plant-by-Plant Decarbonization Pathway for Global Fossil-Fuel Captive Power Plants"

All data files are expected under ./data/ relative to the notebook directory.

- Biomass_agriculture.ipynb: Calculates crop residue biomass and theoretical energy potential (GJ) for 18 crop types at 5 km global resolution.
- Biomass_forest.ipynb: Calculates available forest residue energy potential (GJ) by combining above-ground biomass, climate zones, BCEFs, and plantation forest maps.
- Final_NPV.ipynb: Computes MAC (marginal abatement cost) curves and NPV for multiple mitigation options (solar, wind, grid, CCS, biomass, BECCS, coal-to-gas, renewables+storage) for captive power plants; generates Figures 1–5.
- Solution_search.ipynb: Solves least-cost mitigation pathways under 20%/40%/60% emission reduction targets using linear programming (PuLP), plus least-cost and most-mitigation benchmark scenarios.
