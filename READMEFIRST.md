Description of Directory Contents
=================================

```README.md```  Detailed step by step instructions and account of the workflow used to carry out the Molecular Modelling of the Nisin NSR interaction.

```Docking``` This directory contains the scripts and pdb files necessary to create the input files and starting configurations for Nisin and Nsr before the simulation is initialised.

``` Simulation``` This directory contains the paramter input files for te amber16 programs. It also conatins the staring configuration pdb files for the LEaP program. In addition it has ptraj files which are simple scripts that are used once the simulation has completed to extract distance, RMSD, RMSF and hbond information from the trajectory files (files ending in *.mdcrd)

``` Rcode``` This directory contains the R scripts used to produce the plots fro figure X. It also contains the input files for each of the scripts. 

```MolecularModelling.pdf``` This is a pdf version of the workflow described in the README.


##Data Availibilty

Every file that was generated using the docking procedure and the subsequent simulation in Amber have been stored in 2 google drive accounts. The data generatedfrom the NSR-Nisin A simylation can be accesed using this link. The folder is around 32GB.  For the NSR-Nisin PV simulation the data can be accessed at using this link. 

##Final Point to note - The Nisin PV Simulation

The README and MolecularModelling.pdf descibe the steps required to model the NSR-Nisin A interaction. For the NSR-Nisin PV simulation the exact same steps can be carried out with the pdb file for Nisin PV in place of the pdb file for Nisin A. For completeness the starting confoguration pdb file for Nisin PV is also in the Simulation as well the *.ptraj files that can extract the distance, RMSD, RMSF and hbond information for the Nisin PV simulation. In addition in the Rcode directory are raw data files generated from the *.ptraj files used in the NSR-Nisin PV simulation.
