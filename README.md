# ASGS 2016 Lite Ontology
This ontology is a lightweight [Web Ontology Language (OWL)](https://www.w3.org/OWL/), v2, representation of the structure of the [Australian Bureau of Statistics (ABS)](http://www.abs.gov.au)'s 2016 version of their [Australian Statistical Geography Standard (ASGS)](http://www.abs.gov.au/websitedbs/D3310114.nsf/home/Australian+Statistical+Geography+Standard+(ASGS)) product.

This ontology is based entirely on the structure of the 2016 ASGS as delivered by the ABS's public collection of [Web Feature Services (WFS)](http://www.opengeospatial.org/standards/wfs) that provides access to all of the dataset's parts. The listing of all of the various web services is:

* <https://geo.abs.gov.au/arcgis/rest/services/ASGS2016>

The *GetCapabilities* endpoint of the Mesh Blocks WFS is:

* <https://geo.abs.gov.au/arcgis/services/ASGS2016/MB/MapServer/WFSServer?service=wfs&version=2.0.0&request=GetCapabilities>

...and there are similar endpoints for each WFS.


## Ontology files
Currently there is only one content file for this ontology: [model.ttl](model.ttl), which encodes this ontology in RDF (turtle). 


## Purpose
This ontology has been developed to assist with delivering ASGS 2016 content as Linked Data for the LOC-I project, an Australian government project by [CSIRO](http://csiro.au), the [ABS](http://www.abs.gov.au) and [Geoscience Australia](http://www.ga.gov.au).

Data delivered according to this ontology is planned to be delivered via an online API that is not yet publicly available.


## License
The content of this ontology is licensed for use under the [Creative Commons v4.0 licence](https://creativecommons.org/licenses/by/4.0/) with a copy of that licence's deed in the [LICENSE](LICENSE) with within this repository.


## Contacts
Author:  
**Nicholas Car**  
*Senior Experimental Scientist*  
CSIRO Land &amp; Water, Environmental Informatics Group  
Brisbane, Queensland  
<nicholas.car@csiro.au>  
ORCID: [0000-0002-8742-7730](https://orcid.org/0000-0002-8742-7730)
