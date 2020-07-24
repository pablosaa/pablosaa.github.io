A Microwave Radiative Transfer for the Atmosphere.

Based on the Radiative Transfer code RT3 and RT4 by Franz Evans et al. 2004.
Main contribution is the netCDF input for the RT code adapted to Wyoming radiosone data processed by the repository [[WyoSondes](https://github.com/pablosaa/WyoSondes)], and forecast models like AROME-Arctic or WRF is supported.

The code supports multiple atmospheric profile entries in a (lat,lon) grid and for a range of time series. It also support multiple microwave frequencies and multiple observation angles in a single run.

The output of the simulations are stored in netCDF, containing variables like:
Brightness Temperatures for all frequencies and H- & V-polarization at the TOA and ground level,
The original profiles, The microphysics profiles, e.g. atmospheric attenuation by gases, clouds, rain, and
Surface meteorological variables.
