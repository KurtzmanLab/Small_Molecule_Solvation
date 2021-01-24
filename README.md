# The study of small molecule solvation by PME-GIST

## File description
Under each folder named by molecule name, the follwing files are included:

*molecule.sdf*: the initial structure file of the molecule.
*molecule_MD#_GIST-2016-energy-dens.dx*: the energy density calculated by GIST-2016 using minima image convention algorithm. \n
*molecule_MD#_PME-GIST-energy-dens.dx*: the energy density calculated by PME-GIST using particle mesh Ewald algorithm. \n
*molecule_MD#_GIST-TSsix-dens.dx*: the temperatue*(300K)*entropy calculated by GIST. \n
*molecule_MD#_polulation.dx*: the number of water molecule in each voxel. \n
*molecule_radial_distribution.png*: the solvation energy, entropy and free energy integrated within the region of different distance to the solute. \n

"#" stands for the MD replicate index







