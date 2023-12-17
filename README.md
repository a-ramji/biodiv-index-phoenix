# Investigating Biodiversity Intactness in the Phoenix metropolitan area
![bii-image](figures/bii-image.png)
Image credits: Global 100m Projections of Biodiversity Intactness for the years 2017-2020 [Technical Whitepaper](https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io-biodiversity/Biodiversity_Intactness_whitepaper.pdf)
### Context & Purpose

In 2021, Maricopa County, which encompasses the Phoenix metropolitan area, was the US county that added the most developed land since 2001 [1](https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/). Urban sprawl creates pressure on biodiversity and natural areas.

This repository contains a Python notebook with data exploration and analysis into the change in Biodiversity Intactness in the Phoenix metropolitan area in 2017 and 2020. I explore a dataset showing values for biodiversity intactness index (BII) [2](https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io-biodiversity/Biodiversity_Intactness_whitepaper.pdf), [3](https://planetarycomputer.microsoft.com/dataset/io-biodiversity) to find changes in this BII around the Phoenix area from 2017 to 2020.


### Repository Structure

```bash
├── LICENSE
├── README.md
├── biodiversity_index_phoenix.ipynb  # primary analysis notebook
├── data
│   ├── tl_2022_04_cousub.cpg
│   ├── tl_2022_04_cousub.dbf
│   ├── tl_2022_04_cousub.prj
│   ├── tl_2022_04_cousub.shp
│   ├── tl_2022_04_cousub.shp.ea.iso.xml
│   ├── tl_2022_04_cousub.shp.iso.xml
│   └── tl_2022_04_cousub.shx
└── figures
    ├── bii_phoenix_final.png
    └── phoenix_county.png
```



### Data Citation

- BII data:`io-biodiversity` collection, from the Microsoft Planetary Computer's STAC catalog. This dataset was generated by [Impact Observatory](https://www.impactobservatory.com/), in collaboration with [Vizzuality](https://www.vizzuality.com/). It contains terrestrial biodiversity intactness data at 100m resolution. 

Microsoft Planetary Computer, STAC Catalog. Biodiversity Intactness (*'io-biodiversity'*). [Dataset].  https://planetarycomputer.microsoft.com/dataset/io-biodiversity Accessed 6 December 2023.


- United States Census Bureau, County Subdivision shapefiles for Arizona. County subdivision level census data from 2022.
   
United States Census Bureau. (2022). *Arizona County Subdivision 2022 TIGER/Line Shapefiles*. [Data File]. U.S. Census Bureau, Geography Division. https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions Accessed 6 December 2023.

### References

1. Levitt, Z., &amp; Eng, J. (2021, August 11). *Where America’s developed areas are growing: 'Way off into the horizon’*. The Washington Post. https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/
2. Mazzarello, J., &amp Hyde, S. (2022, August). *Global 100m Projections of Biodiversity Intactness for the years 2017-2020*. [Technical White Paper]. Impact Observatory, Vizzuality.
3. Microsoft Planetary Computer, STAC Catalog. Biodiversity Intactness (*'io-biodiversity'*). [Dataset].  https://planetarycomputer.microsoft.com/dataset/io-biodiversity Accessed 6 December 2023.





