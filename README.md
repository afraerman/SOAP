# SOAP: Spacecraft Orbit and Attitude Prediction tool

This software was developed in the Laboratory of Ballistic And Navigation Support For Space Projects of Astro Space Center of PN Lebedev Physics Institute

## Required Files:

- Due to its large size, the ephemeris file must be downloaded into the "Files" folder from the website https://naif.jpl.nasa.gov/pub/naif/generic_kernels/spk/planets/ (de440.bsp is used by default).
- For the same reason, the EGM2008.dat file contains information on harmonics only up to the 500th order.

## Execution:

On Linux OS, execution is performed by running the /linux/build/soap program. To run the program, it is sufficient to specify the path to the project parameters file.

## Parameter Files:

- all_parameters.json --- This file contains all available parameters but cannot be used as the program's input file itself.
- gracefo.json --- This file contains the launch parameters of a spacecraft similar in characteristics to the GRACE-FO C spacecraft.
- spectrR.json --- This file contains the launch parameters of a spacecraft similar in characteristics to the Spektr-R spacecraft of the RadioAstron space project.
