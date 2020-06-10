# COVID19_emissions
Mobility  -based estimates of emission change from COVID19 for 2020 and projections forward

These data are
National emissions: are daily national emissions for 10 species
CO2,CH4,N2O,SO2,Black Carbon,Organic Carbon, Carbon Monoxide,NMVOCs,NH3 and NOx

Sceanrios of emission, concentration and forcing are also given in the pathway directory

Gridded emisisons are too big for GitHub so are here:https://zenodo.org/record/3854866#.XszKwBNKjEY

Global pathways are emission scenarios and outputs from FaIRv1.5 https://github.com/OMS-NetZero/FAIR, with model tuning parameters

There  is the baseline scenario in the pathway directory for the global pathways. Otherwise the baseline the EDGAR version 5.0, 2015. We compute a fractional change per sector from mobility data and them then sum over the sectors average daily emisison to present in emssion change per day. The baseline would be the EDGAR 2015 annal values divided by 365, summed over all sectors.

The annual gridmaps from EDGAR for 2015 are also used as the basis for the gridmap fields, see the file for details

Uses Google mobility data to estimate 2020 emission change due to COVID 19 restrictions and then examine its climate impact
Uses the sector based analyses of Le Quere et al. (2020) nature.com/articles/s41558-020-0797-x  as a basis


Based on a submitted paper
## Current and future global climate impacts resulting from COVID-19
Piers M. Forster, Harriet I. Forster, Mat J. Evans, Matthew J. Gidden, Chris D. Jones, Christoph  A. Keller, Robin Lamboll, Corinne Le Quéré, Joeri Rogelj, Deborah Rosen, Carl-Friedrich Schleussner, Thomas Richardson, Christopher J. Smith, Steven T. Turnock.

Funding was provided by the European Union’s Horizon 2020 Research and Innovation Programme under grant agreement nos. 820829 (CONSTRAIN)http://constrain-eu.org/  and UKRI NERC grant NE/N006038/1 (SMURPHS). CDJ was supported by the Joint UK BEIS/Defra Met Office Hadley Centre Climate Programme (GA01101) and CRESCENDO (EU Project 641816). CLQ was supported by the Royal Society (grant no. RP\R1\191063), and the European Commission H2020 4C grant (no. 821003). MJE is grateful for computational support from the University of York’s HPC service (Viking). 

Various data sources are used to create these emission scenarios:

Google LLC "Google COVID-19 Community Mobility Reports". https://www.google.com/covid19/mobility/  Accessed: 11 May 2020.
Apple LLC “Apple Mobility Trends Reports” https://www.apple.com/covid19/mobility Accessed: 11 May 2020.

EDGAR version 5.0 national and sector split and gridded emissions data is available from https://data.europa.eu/doi/10.2904/JRC_DATASET_EDGAR

Cowtan & Way temperature observations are available from https://www-users.york.ac.uk/~kdc3/papers/coverage2013/had4_krig_annual_v2_0_0.txt

Le Quéré et al. (2020) emissions data are available from https://www.icos-cp.eu/gcp-covid19

The air quality data is available from https://openaq.org/. The GEOS modelled air pollution data used in this study/project have been provided by the Global Modeling and Assimilation Office (GMAO) at NASA Goddard Space Flight Center and is available from https://opendap.nccs.nasa.gov/dods/gmao/geos-cf/assim 

Future scenarios are based on Climate Action Tracker projections https://climateactiontracker.org/publications/addressing-the-climate-and-post-covid-19-economic-crises/




