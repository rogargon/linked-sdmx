# SDMX to QB

## What is this?

XSLT 2.0 scripts to transform Generic [SDMX 2.0](http://sdmx.org/?page_id=16#package) data and metadata to RDF/XML using the [RDF Data Cube](http://www.w3.org/TR/vocab-data-cube/) and related vocabularies for statistical Linked Data. Its purpose is:

* To automagically transform SDMX-ML data and metadata into RDF/XML as semantically and complete as possible.
* To support SDMX publishers to also publish their data using RDF.
* To improve access and discovery of statistical cross-domain knowledge.

## What is inside?

It comes with scripts and sample data.

### Scripts
* XSLT 2.0 templates to transform Generic SDMX-ML data and metadata. It includes the main XSL template for generic SDMX-ML, an XSL for common templates and functions, and an RDF/XML configuration file to set preferences like base URIs, delimiters in URIs, how to mapping annotation types.
* Bash script that transforms sample data using saxonb-xslt.

### Samples
Sample SDMX Message and Structure data retrieved from several organizations like BIS, OECD, UN, ECB, WB, IMF, FAO, Eurostat, BFS.

### Requirements
An XSLT 2.0 processor to transform, and some configuring using the provided config.rdf file.

## How to contribute
* See [open GitHub issues](https://github.com/csarven/sdmx-to-qb/issues?state=open) if you want to hack, or create issues if you encounter bugs, or enhancements within the scope of this project.
* Please send pull requests or help improve documentation.
* Reach out to organizations that publish data using the SDMX-ML to collaborate on this effort.
