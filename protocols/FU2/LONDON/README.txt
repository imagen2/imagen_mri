Gareth Barker wrote on 12/10/2015:

Imagen (including imagen FU2) used a custom pulse sequence which read
a non-standard "tensor.dat" file. As the GE reconstruction writes values
from the product tensor.dat into the header (even if this isn't used!),
the DICOM headers were deliberately set to NOT contain any (incorrect)
diffusion info.

The b-values/vectors for all IMAGEN scans should be as per the attached
(in FSL format)...
