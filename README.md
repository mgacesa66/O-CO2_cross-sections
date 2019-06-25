# O-CO2_cross-sections
Raw data and codes used in "O(3P)+CO2 scattering cross sections at superthermal collision energies for planetary aeronomy" publication.

Structure:
-----------
table_integral-CS_3pes.dat       -> integral elastic cross sections for O(3P)+CO2(j=0) -> O(3P)+CO2(j=0)
table_momentum-transfer-CS_3pes  -> momentum transfer cross sections; same states as above
./CSs_3pes/ -> state-to-state cross sections for 41 collision energy points (0.029-5 eV). Statistically weighted over three potential energy surfaces. See the publication for details.
./DCSs_3pes/ -> differential cross sections as a function of scattering angle for 41 collision energy points. Statistically weighted over three potential energy surfaces. See the publication for details.

To upload (6/25/2019):
- 3 VRTP subtroutines for MOLSCAT code (https://www.giss.nasa.gov/tools/molscat/ also https://github.com/molscat/molscat) used to calculate the electronic potentials from interpolated potential energy surfaces correlating to the lowest asymptote (3A2, 3B1, 3B2)
- raw data for other initial scattering states
