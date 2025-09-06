# Development of Bi-Mn Machine Learned Interatomic Potential (MLIP)

In this project, an attempt has been made to develop the Bi-Mn MLIP which can then be used in Molecular Dynamics (MD) simulations to study various properties of the alloy. 
To properly develop an MLIP for the Bi-Mn alloy system, first a reference dataset is to be built which will contain all the forces, stresses and energies of stable as well as strained configurations.
In the Mn folder, there is a QuantumEspresso [1] .in (input) code which performs a Self-Consistent Field (SCF) calculation for the Mn Im-3m spacegroup at 0K temperature. Further commits will be pushed which will include SCF calculations for other Mn and Bi spacegroups, ab-initio Molecular Dynamics to get data for Mn and Bi structures at higher temperatures as well as usage of the PyMatGen [2] python library to generate strained structures.

The work is stull undergoing development and I will continue adding .in and .out files for this project as we carry on with our DFT and AIMD (ab-initio Molecular Dynamics) calculations.

# References
1. Shyue Ping Ong, William Davidson Richards, Anubhav Jain, Geoffroy Hautier, Michael Kocher, Shreyas Cholia, Dan Gunter, Vincent Chevrier, Kristin A. Persson, Gerbrand Ceder. *Python Materials Genomics (pymatgen) : A Robust, Open-Source Python Library for Materials Analysis.* Computational Materials Science, 2013, 68, 314–319. https://doi.org/10.1016/j.commatsci.2012.10.028
2. P. Giannozzi et al., “QUANTUM ESPRESSO: a modular and open-source software project for quantum simulations of materials,” J. Phys.: Condens. Matter, vol. 21, no. 39, p. 395502, Sep. 2009. https://doi.org/10.1088/0953-8984/21/39/395502.
