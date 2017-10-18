# Hot carrier cooling

[Jupyter notebooks](http://jupyter.org) outlining theory and calculations for hot polaron cooling in halide perovskites including CH<sub>3</sub>NH<sub>3</sub>PbI<sub>3</sub> and CsPbI<sub>3</sub>.

Static renders of the notebooks are available here, but simply download the repository and open using `jupyter notebook` for interactive versions.

### Files

![Polaron_effective_mass_theories.ipynb](Polaron_effective_mass_theories.ipynb) contains Julia codes to evaluate effective-mass theories (in the asymptotic variational limit, as presented by Feynman in the original 1955 paper). You can express Frohlich α values, mass renormalisations, Schultz polaron radius and volumes, exciton effective mass theory radius and spectra; summations with Bose-Einstein statistics over phonon modes to get specific heat capacities; Franck-Condon overtone spectrum from polaron variational solution; overlaid plots of polaron wavefunction and Schultz's definition of radius; some notes on the derivations in Schultz. 

Additionally the codes used to generate data for Figure 2 using the ![PolaronMobility.jl](https://github.com/jarvist/PolaronMobility.jl) package are available. Here is a specific (October 2017) point in history, which reproduces the data for the publication figure: ![ThermalPathways.jl](https://github.com/jarvist/PolaronMobility.jl/blob/139795b49b72f2acb413abe4247e5fa158a037df/HalidePerovskites/ThermalPathways.jl).

![Diffusion_eqn_for_hot_sphere.ipynb](Diffusion_eqn_for_hot_sphere.ipynb) outlines the derivation of the analytical expression for heat diffusion for a hot sphere. This was used for calculating the final stage of cooling to equilibrium.

![Polaron_cooling_via_heat_diffusion.ipynb](Polaron_cooling_via_heat_diffusion.ipynb) contains Python codes to generate the polaron Temperature-Radius (Figure 3) and Energy-Time (Figure 4) plots.

### Publication

_"Slow cooling of hot polarons in halide perovskite solar cells"_ by Jarvist M. Frost, Lucy D. Whalley and Aron Walsh (2017)


### License

The notebooks are made available under the GNU General Public Licence (GPL) v3. See the LICENSE file for the full text.
