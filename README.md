# O-CO2_cross-sections
Raw data and codes used in M. Gacesa, R. J. Lillis, and K. J. Zahnle, "O(3P)+CO2 scattering cross sections at superthermal collision energies for planetary aeronomy" (submitted to J. Geophys. Res. Planets, 2019) publication.

These files are distributed under GNU General Public License v3.0 and include NO liability or warranty of any kind. No support is provided by the authors. We cannot promise (but we may try!) to answer any questions related to this dataset nor to prepare different products for you.

Please cite this work as:
Marko Gacesa, Lillis, Robert J., & Zahnle, Kevin J. (2019). O(3P)+CO_2 scattering cross sections at superthermal collision energies for planetary aeronomy: Raw data pre-release (Version v0.9-beta) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.3256699


File structure:
--------------
table_integral-CS_3pes.dat       -> integral elastic cross sections for O(3P)+CO2(j=0) -> O(3P)+CO2(j=0)
table_momentum-transfer-CS_3pes  -> momentum transfer cross sections; same states as above

./CSs_3pes/ -> state-to-state cross sections for 41 collision energy points (0.029-5 eV). Statistically weighted over three potential energy surfaces. See the publication for details.

./DCSs_3pes/ -> differential cross sections (elastic and total=elastic+inelastic) as a function of scattering angle for 41 collision energy points. Statistically weighted over three potential energy surfaces. See the publication for details.

To upload (as of 6/25/2019):
- 3 VRTP subtroutines for MOLSCAT code (https://www.giss.nasa.gov/tools/molscat/ also https://github.com/molscat/molscat) used to calculate the electronic potentials from interpolated potential energy surfaces correlating to the lowest asymptote (3A2, 3B1, 3B2)
- raw data for other initial scattering states
