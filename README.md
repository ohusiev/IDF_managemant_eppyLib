# IDF_managemant_eppyLib
management of *.idf files exported from Design Builder in Eppy scripting language available in Python for EnergyPlus simulation engine.

## Disclaimer:
This is very basic test of eppy library based on the documantation of EPPY LIBRARY: https://eppy.readthedocs.io/en/master/

The management of *.idf files made in self-education purpose to explore the functionality. 

The .idf files derived from the Design Builder (DB) software to learn how the functionality of library can be easily realised to avoid manual work and implement iterative change
of parameters within sertain components of DB model for further simulation in EnergyPlus engine.

The experiments made in Anaconda environment via jupyter notebook.

## Aim 

1. Learn how to manage change of certain components by incerting set of different values in itarative way
2. Practice the change of components of the building within the .idf file, for that:
  - by importing a certain parameters from excel .xls file, as list, array, ect;
  - implement the fuctionality of itaration through the array and after each correspondent circulte of iteration submit file to EnergyPlus engine simulation.

## Task 1

1. Establish change of certain elements:
  - Façade (Insul. thickness of in  *EPS Expanded Polystyrene layer*)
  - Windows Thermal transmittance (Uglass)
  - Windows (SHGC)	
  - Windows (Transmisión de luz)	
  - Infiltration
