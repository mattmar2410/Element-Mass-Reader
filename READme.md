# Element Mass

# Description

Finds average mass for the isotopes or elements:

*    mass, mass_units (u)
         The molar mass averaged over natural isotope abundance.

Atomic Weights and Isotopic Composition [#Coursey]_.

The atomic weights are available for elements 1 through 112, 114, & 116 and
isotopic compositions or abundances are given when appropriate. The atomic
weights data were published by Coplen [#Coplen]_ in Atomic Weights of the
Elements 1999, (and include changes reported from the 2001 review in
Chem. Int., 23, 179 (2001)) and the isotopic compositions data were
published by Rosman [#Rosman]_ and Taylor [#Taylor]_ in Isotopic Compositions
of the Elements 1997.  The relative atomic masses of the isotopes data were
published by Audi [#Audi]_ and Wapstra [#Wapstra]_ in the 1995 Update To The
Atomic Mass Evaluation.

This data has been compiled from the above sources for the user's convenience
and does not represent a critical evaluation by the NIST Physics Laboratory.
http://physics.nist.gov/PhysRefData/Compositions/

Neutron mass from NIST Reference on Constants, Units, and Uncertainty
http://physics.nist.gov/cuu/index.html

.. [#Coursey] Coursey. J. S., Schwab. D. J., and Dragoset. R. A., NIST,
       Physics Laboratory, Office of Electronic Commerce in Scientific
       and Engineering Data.
.. [#Coplen] Coplen. T. B. : U.S. Geological Survey, Reston, Virginia, USA.
.. [#Rosman] Rosman. K. J. R. : Department of Applied Physics, Curtin University
       of Technology, Australia.
.. [#Taylor] Taylor. P. D. P. : Institute for Reference Materials and
       Measurements, European Commission, Belgium.
.. [#Audi] Audi. G. : Centre de Spectrométrie Nucléaire et de Spectrométrie
       de Masse, Orsay Campus, France.
.. [#Wapstra] Wapstra. A. H. : National Institute of Nuclear Physics
       and High-Energy Physics, Amsterdam, The Netherlands.

## File instructions

### Running the file for isotopic masses

Use mass.py to run the function element_mass.

Enter the data as this:

```
element_mass('U235', 'Pu234')
```
make sure to separate the input with a comma

### Running the file for elemental mass

```
element_mass('U235', 'Pu', 'O')
```
The function will return the elemental mass of Pu and O and the isotopic mass of
U235
