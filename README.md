# FTLE_JJ
Finite time Lyapunov exponent (FTLE) analysis on pitching airfoil with dynamic stall vortex shedding

## FTLE short description
Given a velocity field around a pitching airfoil, particles are instantiated and integrated through time and track its trajectory. The FTLE is then calculated which quantifies the Lagrangian stretching between neighboring particles. Particles may also be integrated backward in time and calculate the FTLE field. High values of FTLE in the positive and negative integration correspond to the unstable and stable manifolds. This is because particles are stretching for pFTLE and converging for nFTLE. Locating the intersections of these manifolds shows the saddle point which can provide insight like vortex shedding dynamics.

## Implementation Summary
  1. Read velocity/vorticity field data
  2. Create particles in space
  3. Integrate particles forwards/backwards
  4. Create flow map (new position of the particles plotted on the original grid)
  5. Calculate FTLE field
  6. Filter regions of high FTLE values
  7. Find saddle points

--- 
## Created by 
Justine John A. Serdoncillo  
JJ  
University of Minnesota - Twin Cities  
Aerospace and Engineering Mechanics  
serdo004@umn.edu  
