+++
title = "Reproducibility in Catalysis Research with Managed Workflows and RO-Crates"
template = "item.html"
[extra]
author = "Patrick Austin"
institution = "Science and Technology Facilities Council"
author_url = ""
time = "15:25 BST"
highlight = false
+++

With FAIR principles increasing in importance within many fields, the challenge of ensuring that these principles are fully embedded in research outputs applies not just to the (meta)data itself, but also to the methods used to process and analyse it. If metadata associated with the raw data is lost in the analysis process, the Findability may be compromised. If the parameters used in the analysis of the data are not recorded, then Reusability can be compromised. 
Within the PSDI project, addressing this challenge has been the focus of work by the Experimental Data Capture (Pathfinder 1) and Reproducible Computational Workflows (Pathfinder 7) teams. The paper “Facilitating Reproducibility in Catalysis Research with Managed Workflows and RO-Crates: A Galaxy Case Study” (https://doi.org/10.1002/cctc.202401676) presented an example of how the tools and services developed by these Pathfinders can improve reproducibility with the example of catalysis experiments using the X-ray Absorption Spectroscopy (XAS) technique. Catalysis experiments with published raw data were identified, and analysis was repeated using the web based workflow management platform Galaxy. This identified a number of areas where, despite data being published, a lack of metadata made reproduction of the processed output data challenging. By contrast, Galaxy automatically records parameters used in analysis, tracks provenance of inputs and outputs, and enables researchers to export a single Research Object Crate (RO-Crate) which describes the entirety of the analysis performed so that it is both comprehensively described and easily reproducible.
This presentation will describe these tools and services and how their utilisation can improve the FAIRness of research outputs in this example use case.

### Acknowledgements
Dr. Abraham Nieva-de-la-Hidalga,  Dr. Leandro Liborio,  Subindev Devadasan,  Dr. Tom Underwood,  Dr. Alexander Belozerov,  Dr. Martin Wilding,  Dr. Nitya Ramanan,  Prof. C. Richard A. Catlow

{{ render_logos(paths=["images/image.png", "images/image-1.png", "images/image-2.png", "images/image-3.png", "images/image-4.png"], alt=["Science and Technology Facilities Council logo", "Cardiff University logo", "Catalysis Hub logo", "Physical Sciences Data Infrastructure logo", "European Open Science Cloud, EuroScienceGateway logo"]) }}

#### Funding acknowledgement
PSDI acknowledges the funding support by the EPSRC grants EP/X032701/1, EP/X032663/1 and EP/W032252/1
EuroScienceGateway was funded by the European Union programme Horizon Europe (HORIZON-INFRA-2021-EOSC-01-04) under grant agreement number 101057388 and by UK Research and Innovation (UKRI) under the UK government’s Horizon Europe funding guarantee grant number 10038963.
