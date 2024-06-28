# The HPAI Contextual Data Specification

  - [About](#about)
  - [What are ontologies and how do they improve data quality?](#what-are-ontologies-and-how-do-they-improve-data-quality)
  - [The  Contextual Data Specification Package](#the--contextual-data-specification-package)
    - [Version Control](#version-control)
    - [Package Contents](#package-contents)
      - [Data Collection Template](#data-collection-template)
      - [Field and Term Reference Guides](#field-and-term-reference-guides)
      - [Curation SOP](#curation-sop)
      - [DataHarmonizer Instructions and SOP](#dataharmonizer-instructions-and-sop)
      - [New Term Request (NTR) SOP](#new-term-request-ntr-sop)
  - [Contacts](#contacts)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## About

This data specification harmonizes contextual data to support the monitoring of Highly Pathogenic Avian Influenza virus, developed in collaboration with [Public Health Alliance for Genomic Epidemiology (PHA4GE)](https://pha4ge.org/). The specification aims to facilitate comprehensive monitoring by providing standardized, ontology-based fields and terms. Implemented through the DataHarmonizer tool, it is designed to ensure consistency and accuracy in data collection and analysis. Comprehensive field and reference guides, along with various curation and new term request SOPs, support its implementation.

<Blurb>
<SETUP: you'll need to manual create "term request" and "field request" labels in order for the issue forms to apply them when generated. You'll also want to go through documentation and replace all the <INSERT values with appropriate information.>

## What are ontologies and how do they improve data quality?

Labs collect, encode and store information in different ways. They use different fields, terms and formats, they categorize variables in different ways, and the meanings of words change depending on the focus of the organization (think of the word “plant”. To someone in agriculture, “plant” could mean an organism that carries out photosynthesis, while a food regulator might understand the word “plant” to mean a factory where food products are made). This variability makes comparing, integrating and analyzing data generated by different organizations like trying to compare apples, oranges and bananas, which is difficult to do.

Ontologies are collections of controlled vocabulary that are arranged in a hierarchy, where all the terms are linked using logical relationships. Ontologies are open source and meant to represent “universal truth” as much as possible (so not tied to one organization’s vocabulary of use case). Ontologies encode synonyms, which enables mapping between the specific languages used by different organizations, and every term in the ontology is assigned a globally unique and persistent identifier. Using ontology terms to standardize GRDI-AMR contextual data not only helps make data more interoperable by using a common language, it also helps to make contextual data [FAIR](https://www.go-fair.org/fair-principles/) (Findable, Accessible, Interoperable, Reusable).

## The HPAI Contextual Data Specification Package

This specification is currently implemented via a DataHarmonizer validation template, with accompanying **Field** and **Term reference guides** (which provide definitions and additional specific guidance) and a curation **Standard Operating Procedure (SOP)**. Please note, this specification is not only available in the DataHarmonizer and can be implemented in any data capture tool, please refer to the field and term reference guides for the data types and picklists.

New terms and/or term changes can be requested through GitHub using the [issue request forms](https://github.com/cidgoh/HPAI_Contextual_Data_Specification/issues/new/choose), with additional guidance on how to do so outline in the New Term Request (NTR) SOP. This resources are available in the files of this repository and listed below under **Package Contents**.

### Version Control

Please note that development of the specification is dynamic and it will be updated periodically to address user needs. Versioning is done in the format of `x.y.z`.

`x` = Field level changes <br>
`y` = Term value / ID level changes <br>
`z` = Definition, guidance, example, formatting, or other uncategorized changes

Descriptions of changes are provided in [release notes](https://github.com/cidgoh/HPAI/releases) for every new version.

### Package Contents

#### Data Collection Template
- [Pathogen Genomics Package (**HPAI**)](https://github.com/cidgoh/pathogen-genomics-package/releases)
  - Template schema files can be found as `.yaml`/`.json`/`.tsv` under [pathogen-genomics-package/templates/](https://github.com/cidgoh/pathogen-genomics-package/tree/main/templates)**HPAI**
- [DataHarmonizer App](https://github.com/cidgoh/DataHarmonizer)
  - The DataHarmonizer is a standardized browser-based spreadsheet editor and validator.
  - Instructions on "Getting Started" downloading and using the application can be found under **DataHarmonizer Instructions and SOP** below.
  - Further information about application functionality can be found on the [DataHarmonizer Wiki](https://github.com/cidgoh/pathogen-genomics-package/wiki/DataHarmonizer-Getting-Started).

#### Field and Term Reference Guides
- [XLSX version]()
- PDF version
  - [Field Reference Guide]()
  - [Term Reference Guide]()
- [Online version]()

#### Curation SOP
- [PDF version]()
- [Online version]()

#### DataHarmonizer Instructions and SOP
- [PDF version]()
- [Online version]()

#### New Term Request (NTR) SOP
- [PDF version]()
- [Online version]()

## Contacts
For more information and/or assistance, contact Emma Griffiths at emma_griffiths@sfu.ca or submit a repository [issue request](https://github.com/cidgoh/HPAI_Contextual_Data_Specification/issues).

## License

_Pending / To Be Determined_

## Acknowledgements

Brought to you by The [Centre for Infectious disease Genomics and One Health](https://cidgoh.ca/) and [Public Health Alliance for Genomic Epidemiology(PHA4GE)](https://pha4ge.org/)

![LogoCIDGOH2](https://github.com/cidgoh/specification-repo-template/assets/48695054/87fa713d-8fd7-453d-8542-fc413069e842)
