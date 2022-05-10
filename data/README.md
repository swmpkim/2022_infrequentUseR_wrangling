# About the datasets  

These datasets are subsets of real data, mostly from from Grand Bay NERR. They are **not** appropriate for publishable analyses - I've cut out too much - but the full datasets and associated metadata **are** available from the Reserve upon request.  

## **GNDfish**  
### Long-term fish monitoring: 2005-2014  

Quarterly monitoring occurred at 14 stations across the Reserve, in 5 different habitat types. A 20-ft bag seine (1/8 in Ace mesh) was pulled for 50m parallel to shore, except at seagrass sites where it was pulled 50m in to shore. Water quality (water temp, salinity, dissolved oxygen), weather (air temp, wind direction), and tide information (rising/falling/slack) were all recorded in the field. Fish caught in the seine pull were preserved and identified to species, and standard length was measured.  

For the workshop, the data was reduced to that of 9 key species at 6 sites (2 habitats) across 4 years (2008-2011).    

### Data files  

1.  `GNDfish_sites.csv`: Location information, including GPS coordinates, for the sites included here. Fields are:  
    a.  *site*: Site identifier. Sites in the study were numbered from 1-14. Sites included here are 2, 3, 6, 8, 11, and 14.  
    b.  *habitat_type*: Habitat grouping. Sites in the study were chosen to represent depositional edge, erosional edge, sandy beach, shell midden, or seagrass habitat. The two habitat types included for the workshop are *seagrass* and *erosional edge*.  
    c.  *lat*: latitude, decimal degrees.  
    d.  *long*: longitude, decimal degrees. Negative values because sites are west of the Prime Meridian.  
    e.  *location*: water body/bay name for the site.  
2.  `GNDfish_wq.csv`: Field water quality data for the sampled sites on the subset of dates included for the workshop. Each site on a single sample date occupies a row. Many columns have been trimmed from the original dataset to make this one. Fields are:    
    a.  *collection_id*: unique identifier for the site sampled on a given date.  
    b.  *site*: corresponds with site in `GNDfish_sites.csv` above.  
    c.  *season*: quarter of sampling: Spring, Summer, Winter, or Fall.  
    d.  *salinity_ppt*: salinity, measured in ppt/psu.  
    e.  *do_mgl*: dissolved oxygen, measured in mg/L.  
    f.  *water_temp_c*: water temperature, measured in degrees Celsius.  
3.  `GNDfish_lengths.csv`: Each measured fish occupies a row. Fields are:  
    a.  *collection_id*: corresponds with collection_id in `GNDfish_wq.csv`.  
    b.  *site*: corresponds with site in both csv files above.  
    c.  *species*: fish species, Latin name.  
    d.  *length_sl_mm*: standard length of fish, in mm.  


## **GNDveg**   
### Long-term vegetation monitoring: 2015-present  

Long term vegetation monitoring at GNDNERR is part of the System Wide Monitoring Program that captures spatial and temporal change between tidal and non-tidal transitional ecotones. The goal of this monitoring is to monitor vegetation communities over the long-term to see how they respond to changes in environmental conditions over time. Monitoring began on 7/23/14 and is ongoing.  

Vegetation monitoring at GNDNERR is performed at five sites with three transects per site and 153 1m x 1m plots in total. Sites were established along a coastal transition transect that extends from open water through various marsh types and ends in a freshwater emergent wetland surrounded by slash pine flatwoods. The distance between ecotones determined the number of sites per transect. Plots are approximately 10m apart.  

For the workshop, data was only included from 3 sites, for 3 years (2018, 2019, 2020). Five of the most common species were retained and all others were collapsed to a single 'other' category. This category was only needed at the JURO Mid site. Several columns were removed. The files included are `GNDveg2018.csv`, `GNDveg2019.csv`, and `GNDveg2020.csv`. Fields in each file are:  

a.  *Reserve*: 3-letter reserve code. Always 'GND' in these files.  
b.  *Date*: Date of sampling. Format m/d/yyyy.  
c.  *SiteID*: One of the five sites. Three are present in these files: 'spal', 'juro low', and 'juro mid'.  
d.  *TransectID*: Numeric; transect within a site.  
e.  *PlotID*: Numeric; plot within a transect.  
f.  *Lat*: Latitude, decimal degrees.  
g.  *Long*: Longitude, decimal degrees.  
h.  *Orthometric Height*: Ground elevation relative to NAVD88. On each sampling date, elevation is measured at each of the four corners of a plot using a Trimble R-8 or R-10 Real-Time Kinematic (RTK) GPS unit; the four corners have been averaged to create this column.  
i.  *Species*: Vegetation species, Latin name (or 'other').  
j.  *Cover*: Ocular cover in percent, estimated for each species.  


## GNDBCWQ  
### Long-term water quality monitoring: 2004-present  

Bayou Cumbest is one of four water quality stations at Grand Bay NERR that has been continually monitored as part of the NERRS System-Wide Monitoring Program (SWMP). Data from all Reserves' SWMP is available online at [cdmo.baruch.sc.edu](http://cdmo.baruch.sc.edu).  

The files included here have not undergone any QA/QC; they are files downloaded directly from the YSI EXO2 dataloggers, through KOR v.2. We have very specific procedures for managing SWMP data but these general files straight off the sondes should be similar to what others dealing with such data will work with.  

Files included are: `GNDBCWQ012422.csv` and `GNDBCWQ022422.csv`. Each file includes approximately a month's worth of 15-minute measurements.


## *C. elegans* toxicity  
### NOT a Reserve dataset  

This is a small subset of data, modified from supplementary Table 2 of the publication:  

Boyd, W. A., Smith, M. V., Co, C. A., Pirone, J. R., Rice, J. R., Shockley, K. R., & Freedman, J. H. (2016). Developmental effects of the ToxCast Phase I and Phase II chemicals in *Caenorhabditis elegans* and corresponding responses in zebrafish, rats, and rabbits. Environmental health perspectives, 124(5), 586-593. [https://doi.org/10.1289/ehp.1409645](https://doi.org/10.1289/ehp.1409645).
