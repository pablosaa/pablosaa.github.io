
A stand-alone program written mainly in Fortran 90 and C++, with interface as MEX function for _MATLAB_ and optional output as _MATLAB_ variables or directly as _NetCDF_ archives.

Within the project ADMIRARI, a Micro Rain Radar (MRR) has been used to enrich the radiometer measurements with a reflectivity profile, mainly with a slant configuration. For strong convective cases the MRR Firmware is troublesome since the spectrum suffers from uncertain noise level, folding and aliasing issues. Therefore only the MRR raw data is meaningful to be processed from scratch. This code not only solves the problem of aliasing and folding but also improves the spectrum noise level estimation thereafter the instrument sensitivity.
