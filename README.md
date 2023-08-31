# Mat-dp database

[![DOI](https://zenodo.org/badge/685456625.svg)](https://zenodo.org/badge/latestdoi/685456625)

Mat-dp database contains material intensities of different energy and transport technologies. It is part of the Mat-dp project, so it can be used to model material demand and other implications of material use alongside other Mat-dp tools.

## Structure
Two types of database files are available to download and use. 
1. The first type is a spreadsheet where information is presented in different tabs. The tabs included are:

   a) a tab to describe the material names;
   
   b) a tab to add material emissions or other desired indicators associated to material. Please note that an example is given on how to structure this, but users must add their own values and add any desired columns with other indicators if this is to be used alongside Mat-dp pipeline. To help, the tab includes a suggestion on which [Ecoinvent](https://ecoinvent.org/) object titles to use and some Notes to make recommendations on assumptions to make. However, users can add their own data from their desired source;
   
   c) three tabs of material intensities by technology (for mean, min and max values); and
   
   d) a tab with data sources by technology.
   
3. Two comma-separated-value (csv) files are included. The first is a file with material intensities in matrix form (wide format), where each column is a different material, and the second one includes the material intensities in long format, allowing for Mat-dp database uses that require machine-readable formats.

Other information included in this repository is a data descriptor json file which describes the csv file of material intensities in long format, since this is the most likely file to be used outside of the Mat-dp project

## Linking Mat-dp database with Mat-dp pipeline

The database can be used as a data input for analysing and visualising material demand for given user scenarios. To use the database in the pipeline, please refer to the [following repository](https://github.com/Mat-dp/mat-dp-pipeline).

Please note that some data requires editing in the database so the user can include other indicators apart from material demand (1. b) above).

## Contributing to Mat-dp-database

Contributions are welcome! 

If you wish to include new information on material intensities of other technologies in the published version of the database, please [get in touch via e-mail](mailto:refficiency-enquiries@eng.cam.ac.uk) mentioning "Mat-dp-database" in the subject. If you have questions, need assistance or need better instructions for contributing, please let us know.

## Acknowledgements
The authors would like to thank other contributors to the database: Maaike E. Hakker (electricity generation), Hugh Thomas (transport), and Tatiana Vandermark (electricity transmission and distribution).
