# phoebe-corelib

Further development of the HPC C++ core library (collection of headers) of popular astrophysical package Phoebe 

  https://github.com/phoebe-project/phoebe2

which enables calculating of 

  * creating triangular mashes, areas, volumes and conversion of volume to 
    potential value for bodies:
     - spheres, 
     - rotating stars, 
     - aligned and misaligned binaries (Roche envelopes)
     - contact binaries
     
  * eclipsing of bodies
  
  * zero gradients (Lagrange) points of aligned and misaligned Roche configurations
    
  * Wilson-Deviney atmospheres
  
  * ...

The library has an Python API called 

  liphoebe.

The emphasis in development is on striving to get the most performance and precision 
of routines.

In tests I will demonstrate different aspects of the library and the use of Python API.
