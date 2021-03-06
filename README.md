# PDS4 Resources

## Current Standard

The current version of the standard is _1D00_ aka _1.13_,  released _December 2, 2019_

[Standards Document](https://pds.nasa.gov/datastandards/documents/sr/current)

[Information Model](https://pds.nasa.gov/datastandards/documents/im/current)

[Schema](https://pds.nasa.gov/datastandards/schema/released/pds/v1/PDS4_PDS_1D00.xsd)

[Schematron](https://pds.nasa.gov/datastandards/schema/released/pds/v1/PDS4_PDS_1D00.sch)

## PDS Resources

[Concepts Document](https://pds.nasa.gov/datastandards/documents/concepts)

[Data Preparer's Handbook](https://pds.nasa.gov/datastandards/documents/dph/current)

## Current Discipline Dictionaries

Based on [PDS4 Schema Page](https://pds.nasa.gov/datastandards/schema/released/)

| Discipline             | Version  | Schema                                                                                                  | Schematron                                                                                              | IngestLDD                                                                                                                         | Docs                                                                                                              | GitHub                                                               |
|------------------------|----------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| Cartography            | 1.13.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/cart/v1/PDS4_CART_1D00_1933.xsd)               | [sch](https://pds.nasa.gov/datastandards/schema/released/cart/v1/PDS4_CART_1C00_1933.xsd)               | [ldd](https://raw.githubusercontent.com/pds-data-dictionaries/ldd-cart/master/src/1.D.0.0/PDS4_CART_1D00_IngestLDD_CART_1933.xml) | [docx](https://github.com/pds-data-dictionaries/ldd-cart/raw/master/src/1.D.0.0/PDS4_CART_ldd_user_guide_v0.docx) | [github](https://github.com/nasa-pds-data-dictionaries/ldd-cart)     |
| Display                | 1.11.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/disp/v1/PDS4_DISP_1B00.xsd)                    | [sch](https://pds.nasa.gov/datastandards/schema/released/disp/v1/PDS4_DISP_1B00.sch)                    |                                                                                                                                   | [wiki](http://sbndev.astro.umd.edu/wiki/Filling_Out_the_Display_Dictionary_Classes)                               |                                                                      |
| Geometry               | 1.11.1.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/geom/v1/PDS4_GEOM_1B10_1700.xsd)               | [sch](https://pds.nasa.gov/datastandards/schema/released/geom/v1/PDS4_GEOM_1B10_1700.sch)               |                                                                                                                                   | [wiki](http://sbndev.astro.umd.edu/wiki/Filling_Out_the_Geometry_Dictionary_Classes)                              | [github](https://github.com/nasa-pds-data-dictionaries/ldd-geom)     |
| Imaging                | 1.11.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/img/v1/PDS4_IMG_1B00_1610.xsd)                 | [sch](https://pds.nasa.gov/datastandards/schema/released/img/v1/PDS4_IMG_1B00_1610.sch)                 | [ldd](https://raw.githubusercontent.com/pds-data-dictionaries/ldd-img/master/PDS4_IMG_IngestLDD.xml)                              | [md](https://github.com/pds-data-dictionaries/ldd-img/blob/user-guide/IMG_user_guide.md)                          | [github](https://github.com/nasa-pds-data-dictionaries/ldd-imaging)  |
| Imaging, Surface       | 1.11.1.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/img_surface/v1/PDS4_IMG_SURFACE_1B10_1110.xsd) | [sch](https://pds.nasa.gov/datastandards/schema/released/img_surface/v1/PDS4_IMG_SURFACE_1B10_1110.sch) |                                                                                                                                   |                                                                                                                   |                                                                      |
| Instrument Types       | 1.13.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/ctli/v1/PDS4_CTLI_1D00_1000.xsd)               | [sch](https://pds.nasa.gov/datastandards/schema/released/ctli/v1/PDS4_CTLI_1D00_1000.sch)               |                                                                                                                                   |                                                                                                                   |                                                                      |
| Mission Information    | 1.11.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/msn/v1/PDS4_MSN_1B00_1100.xsd)                 | [sch](https://pds.nasa.gov/datastandards/schema/released/msn/v1/PDS4_MSN_1B00_1100.sch)                 |                                                                                                                                   |                                                                                                                   |                                                                      |
| Missions, Surface      | 1.11.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/msn_surface/v1/PDS4_MSN_SURFACE_1B00_1100.xsd) | [sch](https://pds.nasa.gov/datastandards/schema/released/msn_surface/v1/PDS4_MSN_SURFACE_1B00_1100.sch) |                                                                                                                                   |                                                                                                                   |                                                                      |
| Multidimensional       | 1.9.0.0  | [xsd](https://pds.nasa.gov/datastandards/schema/released/mission/multi/v1/PDS4_MULTI_1900_1000.xsd)     | [sch](https://pds.nasa.gov/datastandards/schema/released/mission/multi/v1/PDS4_MULTI_1900_1000.sch)     | [ldd](https://raw.githubusercontent.com/pds-data-dictionaries/ldd-multi/master/src/1.0.0.0/ldd-multi.xml)                         | [md](https://github.com/pds-data-dictionaries/ldd-multi/blob/master/src/1.0.0.0/README.md)                        | [github](https://github.com/nasa-pds-data-dictionaries/ldd-multi)    |
| Processing Information | 1.11.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/proc/v1/PDS4_PROC_1B00_1100.xsd)               | [sch](https://pds.nasa.gov/datastandards/schema/released/proc/v1/PDS4_PROC_1B00_1100.xsd)               |                                                                                                                                   |                                                                                                                   |                                                                      |
| Ring-Moon Systems      | 1.8.0.0  | [xsd](https://pds.nasa.gov/datastandards/schema/released/rings/v1/PDS4_RINGS_1800_1500.xsd)             | [sch](https://pds.nasa.gov/datastandards/schema/released/rings/v1/PDS4_RINGS_1800_1500.sch)             |                                                                                                                                   | [md](https://github.com/pds-data-dictionaries/ldd-rings/tree/master/src/1.6.0.0/README.md)                        | [github](https://github.com/nasa-pds-data-dictionaries/ldd-rings)    |
| Spectral               | 1.11.0.0 | [xsd](https://pds.nasa.gov/datastandards/schema/released/sp/v1/PDS4_SP_1C00_1100.xsd)                   | [sch](https://pds.nasa.gov/datastandards/schema/released/sp/v1/PDS4_SP_1C00_1100.xsd)                   | [ldd](https://raw.githubusercontent.com/pds-data-dictionaries/ldd-spectral/master/src/1.1.0.0/1.C.0.0/SpectraLDD-1C00_1100.xml)   | [wiki](http://sbndev.astro.umd.edu/wiki/Filling_Out_the_Spectral_Dictionary_Classes)                              | [github](https://github.com/pds-data-dictionaries/ldd-spectral)      |
| Spectral Library       | 1.8.0.0  | [xsd](https://pds.nasa.gov/datastandards/schema/released/speclib/v1/PDS4_SPECLIB_1000.xsd)              | [sch](https://pds.nasa.gov/datastandards/schema/released/speclib/v1/PDS4_SPECLIB_1000.sch)              |                                                                                                                                   |                                                                                                                   |                                                                      |

[Mission Dictionaries](dictionaries/mission.html)

[Superseded Dictionaries](dictionaries/superseded.html)

[Dictionaries In Development](dictionaries/in_development.html)

[All Dictionaries](dictionaries/index.html)

## Context Products

* [PDS4 Context Products](https://pds.nasa.gov/data/pds4/context-pds4/)
  * [Spacecraft](https://pds.nasa.gov/data/pds4/context-pds4/instrument_host/)
  * [Missions](https://pds.nasa.gov/data/pds4/context-pds4/investigation/)
  * [Facilities](https://pds.nasa.gov/data/pds4/context-pds4/facility/)
  * [Telescopes](https://pds.nasa.gov/data/pds4/context-pds4/telescope/)
  * [Instruments](https://pds.nasa.gov/data/pds4/context-pds4/instrument/)

## External Resources

* [SBN Wiki](http://sbndev.astro.umd.edu/wiki/SBN_PDS4_Wiki)
  * [Small Bodies Target Names](http://sbndev.astro.umd.edu/wiki/Target_Names)
  * [Authoring a Data Dictionary Ingest File](http://sbndev.astro.umd.edu/wiki/Creating_the_Ingest_LDD_Dictionary_Input_File)
  * [Standard Values Quick Reference](http://sbndev.astro.umd.edu/wiki/Standard_Values_Quick_Reference#In_.3CPrimary_Result_Summary.3E.2F.3CScience_Facets.3E_3)
* [AGU 2017 Training](https://pds.jpl.nasa.gov/datastandards/training/2017-agu/)

## Tools

* Label and Product Creation
  * [PLAID](https://plaid.jpl.nasa.gov/) - [github](https://github.com/nasa-pds/PLAID)
  * [OLAF](https://olaf.psi.edu)
* Data Dictionary Creation
  * [LDDTool](https://pds.jpl.nasa.gov/tools/about/ldd/)
  * [LD3](https://ld3.psi.edu) - [github](https://github.com/sbn-psi/ldd-transform)
  * [Sample Data Dictionary Project Template](https://github.com/nasa-pds-data-dictionaries/ldd-template)
* Product Validation
  * [Validate](https://pds.jpl.nasa.gov/tools/about/validate/)
* Prodct Viewers
  * [PDS4 Viewer](http://sbndev.astro.umd.edu/wiki/PDS4_Viewer) - [github](https://github.com/Small-Bodies-Node/pds4_tools)

Additional tools are available at the [PDS Tool Registry](https://pds.nasa.gov/tools/tool-registry/)

## Nodes

* [Atmospheres](https://pds-atmospheres.nmsu.edu/)
* [Engineering](https://pds-engineering.jpl.nasa.gov/)
* [Geosciences](http://pds-geosciences.wustl.edu/)
* [Imaging](https://pds-imaging.jpl.nasa.gov/)
* [NAIF](https://naif.jpl.nasa.gov/naif/)
* [Planetary Plasma Interactions](https://pds-ppi.igpp.ucla.edu/)
* [Rings](https://pds-rings.seti.org/)
* [Small Bodies](https://pds-smallbodies.astro.umd.edu/)
  * [Asteroids/Dust](https://sbn.psi.edu)