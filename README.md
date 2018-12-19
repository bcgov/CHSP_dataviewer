---
<!--
Copyright 2018 Province of British Columbia

This work is licensed under the Creative Commons Attribution 4.0 International License.
To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/.
-->


# CHSP-dataviewer

This repo contains the code for the extraction, tabulation, and visualisation of data from Statistics Canada's Canadian Housing Statistics Project (CHSP) using the statistical programming tool [R](https://cran.r-project.org/).


The data are pulled directly from Statistics Canada's CANSIM database, using the R package [`cansim`](https://github.com/mountainMath/cansim) R package. For more information and examples, please refer to the repo [CANSIM-dataviewer](https://github.com/bcgov/CANSIM-dataviewer).

The data presented here are tailored for users in British Columbia.

---

## Scripts

[Preliminary pull and wrangle](scr/housing_residency_status.Rmd)


---

## Statistics Canada reference materials

[Canadian Housing Statistics Program, 2018](https://www150.statcan.gc.ca/n1/daily-quotidien/181211/dq181211b-eng.htm): from _The Daily_, 2018-12-11

Program page: [Canadian Housing Statistics Program (CHSP)](http://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=5257)


### data

The table used:

* Residency status of residential properties by property type and period of construction, provinces of Nova Scotia, Ontario and British Columbia

  - Table: 46-10-0018-01 
  
  - https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=4610001801


### Geography references

* [Geographic Attribute File](https://www150.statcan.gc.ca/n1/en/catalogue/92-151-X)

* [Geographic Attribute File, Reference Guide](https://www150.statcan.gc.ca/n1/pub/92-151-g/92-151-g2016001-eng.htm)

* [Census Geography](https://www12.statcan.gc.ca/census-recensement/2016/geo/index-eng.cfm)

* [Geography Catalogue, Census year 2016](https://www150.statcan.gc.ca/n1/pub/92-196-x/92-196-x2016001-eng.htm)

* [Correspondence Files, Reference Guide](https://www150.statcan.gc.ca/n1/pub/92-156-g/92-156-g2016001-eng.htm)





### Project Status

### Getting Help or Reporting an Issue

To report bugs/issues/feature requests, please file an [issue](https://github.com/bcgov/%3Crepo-name%3E/issues/).

### How to Contribute

If you would like to contribute, please see our [CONTRIBUTING](CONTRIBUTING.md) guidelines.

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

### License: Scripts and Applications

    Copyright 2017 Province of British Columbia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at 

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

### License: Data

Data downloaded and/or saved in this repository is sourced from Statistics Canada, and is covered under the [Statistics Canada Open Licence Agreement](http://www.statcan.gc.ca/eng/reference/licence).



This repository is maintained by [BC Stats](http://www.bcstats.gov.bc.ca). Click [here](https://github.com/bcgov/BCStats) for a complete list of our repositories on GitHub.


happy Wednesday!
