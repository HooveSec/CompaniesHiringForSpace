# Open-source space data and software

Public data, APIs, and software you can use to learn orbital mechanics, satellite operations, Earth observation, and space cybersecurity — the same skills many of the companies in this repo hire for. Prefer projects with an OSI-approved license and a public source repository.

Directories that go deeper than this page: [Orbital Index Awesome Space](https://github.com/orbitalindex/awesome-space), [NASA AMMOS Open Mission Software Landscape](https://nasa-ammos.github.io/landscape/), and [FOSS Space](https://www.fossspace.com/).

## Open data and APIs

| Name | What it is | Link |
| --- | --- | --- |
| NASA Open APIs | Imagery, Mars rover data, exoplanets, DONKI, and other NASA datasets behind a free API key | [api.nasa.gov](https://api.nasa.gov/) |
| NASA Earthdata | Earth science data (MODIS, VIIRS, SMAP, and related missions) via Earthdata Login | [earthdata.nasa.gov](https://www.earthdata.nasa.gov/) |
| NASA Open Data Portal | Agency-wide open datasets, code, and APIs | [data.nasa.gov](https://data.nasa.gov/) |
| ESA Copernicus Data Space | Sentinel optical/SAR Earth-observation data (open and free) | [dataspace.copernicus.eu](https://dataspace.copernicus.eu/) |
| USGS Landsat | Landsat archive and Earth Explorer | [earthexplorer.usgs.gov](https://earthexplorer.usgs.gov/) |
| CelesTrak | Public TLEs, SATCAT, and supplemental orbital data | [celestrak.org](https://celestrak.org/) |
| Space-Track | Official U.S. space-object catalog (free account required) | [space-track.org](https://www.space-track.org/) |
| JPL Horizons | High-precision solar-system ephemerides | [ssd.jpl.nasa.gov/horizons](https://ssd.jpl.nasa.gov/horizons/) |
| NOAA Space Weather | Alerts and data for solar activity that affects satellites and GNSS | [swpc.noaa.gov](https://www.swpc.noaa.gov/) |
| ESA DISCOS | ESA's Database and Information System Characterising Objects in Space | [discosweb.esoc.esa.int](https://discosweb.esoc.esa.int/) |
| SatNOGS Network | Open satellite ground-station network, observations, and telemetry | [network.satnogs.org](https://network.satnogs.org/) |

## Flight software and satellite stacks

| Name | What it is | Link |
| --- | --- | --- |
| NASA core Flight System (cFS) | Modular spacecraft flight-software framework used on many NASA missions (Apache 2.0) | [github.com/nasa/cFS](https://github.com/nasa/cFS) |
| NASA F´ (F Prime) | Component-based flight software and embedded systems framework from JPL | [github.com/nasa/fprime](https://github.com/nasa/fprime) |
| Cubesat Space Protocol (libcsp) | Small C-language network stack commonly used on CubeSats | [github.com/libcsp/libcsp](https://github.com/libcsp/libcsp) |
| LibreCube | Open CubeSat hardware/software architecture | [librecube.org](https://librecube.org/) |
| Linux4Space | Yocto-based Linux distribution aimed at space systems | [linux4space.org](https://linux4space.org/) |
| Open Source Satellite | Open microsatellite platform and design ecosystem | [opensourcesatellite.org](https://www.opensourcesatellite.org/) |

## Mission design and astrodynamics

| Name | What it is | Link |
| --- | --- | --- |
| NASA GMAT | General Mission Analysis Tool for trajectory design, optimization, and navigation | [github.com/nasa/gmat](https://github.com/nasa/gmat) |
| Orekit | Java/Python astrodynamics library used in operations and research | [orekit.org](https://www.orekit.org/) |
| Basilisk | Modular astrodynamics and spacecraft simulation from CU Boulder AVS Lab | [hanspeterschaub.info/basilisk](https://hanspeterschaub.info/basilisk/) |
| Open Space Toolkit | Libraries for environment modeling, orbit, and access computation | [github.com/open-space-collective](https://github.com/open-space-collective) |
| Tudat(Py) | TU Delft astrodynamics toolbox (Python/C++) | [docs.tudat.space](https://docs.tudat.space/) |
| Skyfield | Python astronomy/satellite position library built on JPL ephemerides | [rhodesmill.org/skyfield](https://rhodesmill.org/skyfield/) |

## Ground systems, visualization, and amateur ops

| Name | What it is | Link |
| --- | --- | --- |
| NASA Open MCT | Web-based mission-control framework | [github.com/nasa/openmct](https://github.com/nasa/openmct) |
| Gpredict | Real-time satellite tracking and orbit prediction | [github.com/csete/gpredict](https://github.com/csete/gpredict) |
| CesiumJS | 3D globe/map engine often used for satellite visualization | [cesium.com/platform/cesiumjs](https://cesium.com/platform/cesiumjs/) |
| SatNOGS Client | Client software for participating in the SatNOGS ground-station network | [gitlab.com/librespacefoundation/satnogs](https://gitlab.com/librespacefoundation/satnogs) |
| NASA AMMOS Landscape | Interactive catalog of open-source mission design, ground, and ops software | [nasa-ammos.github.io/landscape](https://nasa-ammos.github.io/landscape/) |

## Space cybersecurity (open frameworks and research)

| Name | What it is | Link |
| --- | --- | --- |
| SPARTA | Aerospace Corporation framework for space-attack TTPs (companion papers are in [Awesome Space Media](AwesomeSpaceMedia.md)) | [sparta.aerospace.org](https://sparta.aerospace.org/) |
| Hack-A-Sat | U.S. Air Force / Space Force satellite-hacking CTF (archives and writeups) | [hackasat.com](https://www.hackasat.com/) |
| Aerospace Village | Community and DEF CON village focused on aviation and space security | [aerospacevillage.org](https://www.aerospacevillage.org/) |
| Space Odyssey research | IEEE S&P 2023 experimental satellite firmware analysis (open artifacts) | [CISPA QEMU/AVR32](https://github.com/CISPA-SysSec/SpaceOdyssey-QEMU-AVR32) |

## How to use this list

If you are trying to get hired, pick one stack and ship something public:

1. Pull TLEs from CelesTrak or Space-Track and propagate them with Skyfield, Orekit, or GMAT.
2. Command a simulated spacecraft with cFS or F´ on a Raspberry Pi or in CI.
3. Decode a SatNOGS observation, or replay a Hack-A-Sat / SPARTA scenario and write up what you learned.

That kind of artifact is more useful in a space-security or flight-software interview than another generic resume bullet.
