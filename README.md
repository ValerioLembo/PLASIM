PLASIM
======

*General Circulation Models Planet Simulator (PlaSim)*
(Streamlined fork of https://github.com/HartmutBorth/PLASIM)

This repository has all necessary components to run the model.

This version of the model contains some improvements compared to https://github.com/HartmutBorth/PLASIM :

- *Tuning* as described in Angeloni et al. submitted to GMD.
- *srv2nc* A complete postprocessor to transform Plasim output to compressed netcdf4 format (no afterburner is needed), based on cdo. It converts both Plasim and LSG outputs.
- *most.x* without X11: Specifying the option "-c" to most.x, a text configuration file can be read. By default "most_last_used.cfg" is used, unless a file is specified.
- *Small fixes*

This model is a research model used in Meteorology and Earth Sciences.
You need knowledge in Meteorology, Climatology and skills in Linux, C and FORTRAN
for running the model and interpreting the results.

Please start reading the manual located in:
plasim/doc for the Planet Simulator
Then have a look at the README file for configuration and setup.

