# Confusion-Foreground
**Simulating the Extragalactic Gravitational-Wave Confusion Foreground**

**Abstract**

An important source of gravitational waves in the millihertz gravitational wave band, covered by space based observatories like the Laser Interferometer Space Antenna (LISA), are ultra-compact binaries: systems with two degenerate stellar remnants with orbital periods of minutes to a few hours. There will be tens of millions of these in the Milky  Way which will form an unresolved confusion foreground that simultaneously provides information about the underlying astrophysical population, but also competes with other sources in the band. This paper examines the extragalactic component of the ultra-compact binary confusion. Population synthesis method are used to create appropriate populations based on galaxy type, metallicity, and stellar mass, and placed in the nearby Universe out to a distance of 100 Mpc using the conglomerated data in the Gravitational Wave Galaxy Catalog (GWGC) for approximately 50,000 galaxies. The predicted level of the composite extragalactic foreground is estimated and the implications for LISA and future missions is discussed. The contributions from the nearest galaxies, the nearest clusters, and bright sources in the simulated populations are also examined.

**Procedure**

1. GWGC Catalog analysis.
Import Gravitational-Wave Galaxy Catalog data. Apply MLR (Mass-luminosity Relationship) and MZR (Mass-Metallicity Relationship) to obtain nessesary parameters (Stellar mass, metallcities, etc). Catagorize them into 4 groups by metallicities, prepare for binary population synthesis.

2. Baseline Galaxy GW Power Computation
After catagorize the potential sources into 4 groups, we perform the binary population simulaion for each type of galaxy. Construct baseline full galaxy populations ((dist=100 Mpc, Stellar mass=1e10 Solar Mass) from the imported fixed population (generated by COSMIC seperately). Compute the gravitational-wave power spectrum for each of the 4 baseline galaxies.

3. Extragalactic Confusion Foreground
From 4 baseline galaxy power spectrums, we generate their represented group power, and combine them to obtain the total extragalactic GW power spectrum. We compute the confusion foreground created by the extragalactic GW sources and the potential resolveable sources.
