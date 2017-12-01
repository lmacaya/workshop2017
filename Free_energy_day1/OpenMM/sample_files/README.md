# Supporting/sample files for OpenMM session

## Manifest:

### Provided:
- [`toluene.pdb`](toluene.pdb): PDB file of small molecule tolene, oriented with respect to T4 lysozyme L99A protein. File from `openforcefield` package data folder.
- [`T4-protein.pdb`](T4-protein.pdb): A T4 lysozyme mutant (L99A) which binds toluene and other small molecules. File from `openforcefield` package data folder.
- [`mobley_20524.mol2`](mobley_20524.mol2): Phenol (from FreeSolv) as in the `solvation_free_energies` directory.
- `mobley_20524.prmtop`, `.inpcrd`, `.top`, and `.gro`: Phenol (from FreeSolv) parameterized systems in AMBER and GROMACS formats. In the AMBER case, phenol is in vacuum; in the GROMACS case, in TIP3P water.
- [`input.pdb`]: OpenMM example villin headpiece input pdb (openmm/examples/input.pdb)

### Potentially generated:
- `mixture_output.pdb`: Output of energy minimization of a mixture