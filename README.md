# Atmospheric Science Resources

Talks from the Cloud Feedback Model Intercomparison Project in 2020: [Allison Wing on convective aggregation / organization](https://www.youtube.com/watch?v=EImE4z_POwA)
- *Humidity distribution* - More organized convection &#8594; Moist regions are moister and dry regions are drier, both column-integrated and at individual levels, and the mean state is drier with greater spatial variability in humidity.
- *Cloud distribution* - More organized convection &#8594; Reduction in high cloud fraction (because the mean state is warmer and then increases upper-level stability?) and potential increase in low-level clouds.
- *Energy budget* (Project 1) - More organized convection &#8594; increased outgoing longwave radiation, little change in shortwave radiation, and more cooling to space.
- *Climate sensitivity* - More organized convection &#8594; more negative climate feedback but quantitatively a large range in this feedback. The feedback parameter has a strong correlation with dI_org/dT, the temperature sensitivity of organization.
- *Hydrological cycle* (Project 2) - 50% of mean precipitation comes from mesoscale storms in the tropics, and more organized convection &#8594; 20-25% more mean precipitation. Local extremes also depend on organization but in unclear ways.

Physics Seminar in 2015: [David Romps on Humidity and Instability](https://youtu.be/FN7k2ZT1DqY)
- *Entrainment / Detrainment* - turbulent mixing of clear air into the cloudy regions / turbulent mixing of cloudy air into the clear-sky regions

[Dynamical core](dynamical-core.pdf) - The dynamical core of an atmospheric model solves the momentum, mass, and energy balances on a spatiotemporal grid using highly efficient numerical methods.

[Physical parameterization](physical-parameterizations.pdf) - Physical parameterizations are use to approximate the processes, like cloud droplet formation and ice crystal nucleation, that occur on subgrid scales.

[Radiative-convective equilibrium](radiative-convective-equilibrium.pdf) - The dominant energetic balance in the tropics is between convective heating and radiative cooling.

[Column water vapor and precipitation relation](peters-and-neelin.pdf) - A critical value of column-integrated water vapor is needed to initiate intense tropical precipitation.

[Zero buoyancy plume model](https://singh.sci.monash.edu/plume.shtml), [increasing CAPE in a warmer world](https://www.pnas.org/content/pnas/114/44/11657.full.pdf) - CAPE increases with environmental saturation deficit in proportion to entrainment, and CAPE extremes will intensify with warming.

[Environmental controls on tropical MCS precip](schiro-et-al.pdf) - Our previous work on the precipitation intensity from mesoscale storms and its dependence on environmental conditions like CAPE and CWVC. Useful comparisons, e.g. with Fig 1.

[Organization of tropical convection[tompkins-et-al.pdf](https://github.com/sylviasullivan/atmsci-resources/files/7085381/tompkins-et-al.pdf)
](tompkins-et-al.pdf) - An older paper that also looks at organized convection and its environmental properties in a long-channel simulation setup, discussing ``dry banding" among other phenomena

# Technical German

[Neue sturmaufl??sende Klimamodelle](stuermische-zeiten-fuer-klimaforschung.pdf) - Artikel ??ber neue Klimamodelle von der Zeitschrift Physik in unserer Zeit

# Coding tools

[xarray](https://xarray-contrib.github.io/xarray-tutorial/oceanhackweek-2020/xarray-oceanhackweek20.html) - How to read netcdf files, see their dimensions and variables, etc. in Python

[ncdump](https://www.unidata.ucar.edu/software/netcdf/workshops/2011/utilities/NcdumpExamples.html) - A command to return header (-h) information about a netcdf file or see values (-v) of a certain variable

[cdo](https://code.mpimet.mpg.de/projects/cdo/embedded/cdo.pdf) - Powerful set of commands to read and edit netcdf files. cdo -infov -selvar,\<variable\> file.nc will generate the same output as ncdump -h file.nc

[Linux for beginners](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview)

[Row-major versus column-major order](https://en.wikipedia.org/wiki/Row-_and_column-major_order) - MATLAB is column-major, whereas numpy is row-major.

# Data

ERA-Interim (ERAI) reanalysis data is found in /work/bb1018/b380873/MCS_clim/ausgabe/meteo\_clim/nc/ERAI. The same files but with the additional variable of storm core extent are available in /work/bb1018/b380873/MCS_clim/ausgabe/meteo\_clim/nc/ERAI_coresize_added. The RCE channel (ch) simulations for a surface temperature of 300 K are available in /work/bb1018/b380873/RCE-CAPE-exploration/RCE-sims/ch_cam300ri0/.
