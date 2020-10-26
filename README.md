# O-CO2_cross-sections - data only
Raw scattering cross section data used in M. Gacesa, R. J. Lillis, and K. J. Zahnle, "O(3P)+CO2 scattering cross sections at superthermal collision energies for planetary aeronomy" (https://arxiv.org/abs/1906.11368) publication.

The files are distributed under GNU General Public License v3.0 and include NO liability or warranty of any kind. No support is provided by the authors. We cannot promise (but we may try!) to answer any questions related to this dataset nor to prepare different data products for you.

Please cite this work as:
Gacesa, Marko & Lillis, Robert J., & Zahnle, Kevin J. (2019). O(3P)+CO_2 scattering cross sections at superthermal collision energies for planetary aeronomy: Raw data pre-release (Version v0.9-beta) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.3256699


File structure:
--------------
table_integral-CS_3pes.dat       -> integral elastic cross sections for O(3P)+CO2(j=0) -> O(3P)+CO2(j=0)
table_momentum-transfer-CS_3pes  -> momentum transfer cross sections; same states as above

./CSs_3pes/ -> state-to-state cross sections for 41 collision energy points (0.029-5 eV). Statistically weighted over three potential energy surfaces. See the publication for details.

./DCSs_3pes/ -> differential cross sections (elastic and total=elastic+inelastic) as a function of scattering angle for 41 collision energy points. Statistically weighted over three potential energy surfaces. See the publication for details.

./DCS_inelastic_3pes/ -> differential cross sections, state-to-state (ji->jf) with kinetic energy transfer Te(ji,jf) to the target rotational state ji calculated using a simple kinematic model (see the article). 
