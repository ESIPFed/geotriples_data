# geotriples_data
Source code management for RDF data generated by [GeoTriples](https://github.com/LinkedEOData/GeoTriples)

# What is GeoTriples?
GeoTriples is a software package which enables transformation of geospatial data into [RDF](https://www.w3.org/RDF/) graphs using [R2RML](https://www.w3.org/TR/r2rml/) and [RML](http://rml.io/) mappings. This ultimately enables data providers to publish geospatial data as Linked Open Geospatial Data.

# What data is hosted here?
Please see the [wiki entry].

# Why not just store this data in the COR directly?
Source code management (SCM) provides a rich mechanism for change control and community development which COR does not. COR is not set up to be a SCM resource. Similarly, SCM is not set up to be a COR.

# How is the data provided as Linked Open Geospatial Data?
Any RDF resources deposited into this repository are automatically fetched by a webhook and sucked into the [ESIP Community Ontology Repository](http://cor.esipfed.org/). This enables improved interaction with the resources via the semantic technology stack that COR provides. 

# Who can contribute?
Anyone, please [open an issue](https://github.com/ESIPFed/geotriples_data/issues) and submit a pull request.

# License
geotriples_data is permissively licensed under the [Apache License v2.0](https://apache.org/licenses/LICENSE-2.0) a copy of which ships with this repository.