# blade-sorting
Genetic algorithm

A blade sorting method based on the genetic algorithm is used to minimize the rotor / turbine unbalance of an aero-engine.

i) Estabilished the optimization model by 
  a) analyzing the unbalance caused by the deviation of the mass moment of the blades
  b) considering the concentricity of the disk

ii) Designed the selection operator, crossover operator, and mutation operator of the algorithm.

Inputs:
  number of blades,
  mass of each blade,
  radius of the gravity center of each blade,
  mass moment of the disk,
  angle between mass moment of the disk and referential
  
Output:
  unbalance amount achieved,
  assembly location for each blade
