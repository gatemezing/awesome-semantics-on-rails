# Awesome Semantics on Rails [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Knowledge graphs, projects, resources and initiatives related to applying semantic web technology in the railways domain.

## Contents

- [Awesome Semantics on Rails ](#awesome-semantics-on-rails-)
  - [Contents](#contents)
  - [Ontologies](#ontologies)
    - [Ontology Implementations](#ontology-implementations)
    - [Transport and Mobility Ontologies](#transport-and-mobility-ontologies)
    - [Academic Papers](#academic-papers)
  - [Knowledge Graphs](#knowledge-graphs)
    - [SPARQL Endpoints](#sparql-endpoints)
    - [SHACL Rules](#shacl-rules)
    - [SKOS Concepts](#skos-concepts)
  - [Applications](#applications)
    - [Generic Applications](#generic-applications)
    - [Tools and Libraries](#tools-and-libraries)
    - [Community Effort](#community-effort)
  - [Slides](#slides)
  - [Conferences](#conferences)
    - [Railways conferences](#railways-conferences)
    - [Master Classes - Workshops](#master-classes---workshops)
  - [Other Awesome](#other-awesome)
  - [Contribute](#contribute)
  - [License](#license)

## Ontologies

### Ontology Implementations

* [ERA Ontology](https://rinf.data.era.europa.eu/era-vocabulary/) - ERA ontology covering topology, railway infrastructure and vehicle types. The namespace URI for the ontology is `http://data.europa.eu/949/`
* [railML Ontology](https://ontology.railml.org/) - Ontology of railML 3.2/3.3 and RailTopoModel 1.4 concepts for infrastructure, timetable, and rolling stock.
* [Verified Permission Ontology](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/vpa-ontology) - ERA Verified Permissions ontology (with use cases vehicle (type) authorisations & vehicle registrations)

* [Semantic RSM](https://github.com/UICrail/SemanticRSM) - RSM refoundation, based on direct RDF/OWL modelling


### Transport and Mobility Ontologies

* [Linked Connections Ontology](https://lovportal.lirmm.fr/ontologies/LC) - Public transport vocabulary for publishing train and other transit timetables as Linked Data, one connection between two stops at a time. The namespace URI is `http://semweb.mmlab.be/ns/linkedconnections#`
* [Linked GTFS](https://github.com/OpenTransport/vocabulary) - GTFS, the feed format many railway operators use to publish timetables, as an RDF vocabulary. The namespace URI is `http://vocab.gtfs.org/terms#`


### Academic Papers

* [Leveraging semantic technologies for digital interoperability in the European Railway domain](https://julianrojas.org/papers/iswc2021-in-use/) - The ERA ontology and knowledge graph in use. ISWC, 2021.
* [On Linking Heterogeneous Railway Knowledge Graphs](https://ceur-ws.org/Vol-4064/Sem4Tra-paper1.pdf) - Challenges in aligning ERA and OpenStreetMap rail infrastructure data. Sem4Tra workshop at SEMANTiCS, 2025.
* [RaCoOn Ontology](https://doi.org/10.1061/AJRUA6.0000859) - Enabling data integration in the rail industry using RDF and OWL. ASCE-ASME Journal of Risk and Uncertainty in Engineering Systems, 2017.
* [Rail Topology Ontology](https://arxiv.org/abs/2107.04378) - Rail Topology Ontology: A Rail Infrastructure Base Ontology. ISWC, 2021.
* [Railway track video Knowledge Base](https://ceur-ws.org/Vol-3632/ISWC2023_paper_501.pdf) - Knowledge graph linking railway infrastructure data to track videos. ISWC Posters, Demos and Industry Tracks, 2023.
* [Towards a Railway Topology Ontology](https://ceur-ws.org/Vol-2721/paper588.pdf) - Poster that introduced the Rail Topology Ontology for integrating rail data silos. ISWC Posters, Demos and Industry Tracks, 2020.


## Knowledge Graphs

### SPARQL Endpoints

* [ERA Endpoint](https://graph.data.era.europa.eu/sparql) - Sparql Endpoint of the European Union Agency for Railways containing more than 50 million triples of railway infrastructure and vehicle types. 
* [Ontorail Endpoint](https://app.ontorail.org/graphdb/sparql) - Ontorail project Endpoint
* [Catalogue of SPARQL queries](https://rinf.data.era.europa.eu/data-stories) - List of useful railway SPARQL queries


### SHACL Rules

* [ERA SHACL Rules](https://rinf.data.era.europa.eu/era-vocabulary/era-shapes) - ERA SHACL rules used for the ERA KG.
* [ERA Extension CCS TMS validator resources](https://github.com/ISAITB/validator-resources-era-ccs-tms/tree/master) - SHACL validator resources for ERA CCS TMS.

### SKOS Concepts

* [ERA SKOS concepts](https://rinf.data.era.europa.eu/era-vocabulary/era-skos) - ERA SKOS concepts used for the ERA KG.


## Applications

### Generic Applications

* [Apache Jena Fuseki GeoSPARQL](https://github.com/Matdata-eu/apache-jena-fuseki-geosparql) - GeoSPARQL-enabled Fuseki deployment for spatial RDF data.
* [ERA Ontology browser](https://rinf.data.era.europa.eu/era-vocabulary/) - Browse the ERA railway ontology and vocabulary. [Source code](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/era-ontology) (last updated 2026-10-16).
* [Infrastructure Search](https://rinf.data.era.europa.eu/search) - Search resources in the ERA endpoint.
* [Virtuoso Faceted Browser](https://linkeddata.uriburner.com/DAV/demos/daas/sparql-faceted-browser-claude_opus_5_5.html) - Faceted browsing demo for RINF data. [Source code](https://github.com/openlink/virtuoso-opensource) (last updated 2026-10-12).
* [Map Explorer](https://rinf.data.era.europa.eu/map-explorer) - Visualize EU railway infrastructure.
* [MatGUI](https://github.com/Matdata-eu/MatGUI) - Knowledge graph and SPARQL workbench.
* [RINF Application Guide](https://rinf.data.era.europa.eu/era-vocabulary/rinf-appGuide/) - Browse RINF technical parameters. [Source code](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/technical-documents/rinf-application-guide-technical-annex) (last updated 2026-10-07).
* [RINF Atlas](https://github.com/Matdata-eu/rinf-atlas) - Map and faceted search over the ERA Register of Infrastructure (RINF).
* [RailML to ERA](https://github.com/Matdata-eu/raillML-to-ERA) - Conversion tooling from RailML to ERA data.
* [RINF Routebook](https://github.com/Matdata-eu/rinf-routebook) - Explore railway routes and infrastructure details using public ERA RINF data.
* [Route Compatibility Check](https://rinf.data.era.europa.eu/route-compatibility) - Check vehicle-type compatibility with railway infrastructure.
* [TP-Lib](https://github.com/Matdata-eu/tp-lib) - Post-process GNSS coordinates onto a railway network.
* [YASGUI Graph Plugin](https://matdata-eu.github.io/yasgui-graph-plugin/) - Visualize SPARQL query results as a graph.

### Tools and Libraries

* [RInfData](https://github.com/bergmannjg/RInfData) - F# tooling to access ERA RINF data through the ERA knowledge graph.

### Community Effort

* [Ontorail project](https://app.ontorail.org/ontorail) - UIC project with a web application listing some conversions to semantics and glossaries.


## Slides

* [Linked Data Introduction](https://matdata-eu.github.io/slides-linked-data-introduction/) - Introduction to linked data. [Source code](https://github.com/Matdata-eu/slides-linked-data-introduction) (last updated 2026-10-15).
* [Railway Meso/Macro Topology](https://matdata-eu.github.io/slides-railway-meso-macro-topology/) - Operational points, primary locations, and sections of line in a mesoscopic railway topology. [Source code](https://github.com/Matdata-eu/slides-railway-meso-macro-topology) (last updated 2026-10-16).
* [Railway Topology](https://matdata-eu.github.io/slides-railway-topology/) - RailTopoModel, railML 3, and ERA ontology concepts for railway infrastructure. [Source code](https://github.com/Matdata-eu/slides-railway-topology) (last updated 2026-10-16).
* [RINF Data Provisioning](https://matdata-eu.github.io/slides-era-rinf-data-provisioning/) - Slides and guidance for building and publishing RINF data. [Source code](https://github.com/Matdata-eu/slides-era-rinf-data-provisioning) (last updated 2026-10-14).
* [Telematics XSD to ERA Ontology](https://matdata-eu.github.io/slides-telematics-xsd-to-era-ontology/) - Slides on mapping telematics XSD data to the ERA ontology. [Source code](https://github.com/Matdata-eu/slides-telematics-xsd-to-era-ontology) (last updated 2026-10-16).
* [Topology-Assisted Positioning](https://matdata-eu.github.io/slides-topology-assisted-positioning/) - Linear positioning systems and position concepts in RailTopoModel and railML 3. [Source code](https://github.com/Matdata-eu/slides-topology-assisted-positioning) (last updated 2026-10-17).
* [W3C Facade-X](https://matdata-eu.github.io/Slides-W3C-Facade-X/) - BaneNOR's experience with SPARQL-Anything, presented to the W3C Facade-X Community Group. [Source code](https://github.com/Matdata-eu/Slides-W3C-Facade-X) (last updated 2026-10-15).


## Conferences

### Railways conferences

* Rail Data Forum - Powered by the European Union Agency for Railways.
     - 2024: [Rail Data Forum 2024](https://www.era.europa.eu/content/rail-data-forum-2024)
     - 2025: [Rail Data Forum 2025](https://www.era.europa.eu/content/rail-data-forum-2025) - Cluj-Napoca, Romania.
* [RailML Conference](https://www.railml.org/en/public-relations/news/reader/44th-railml-conference.html) - RailML conference
* [SEMIC](https://joinup.ec.europa.eu/collection/semic-support-centre/semic-conference) - EU SEMIC conference
* [Sem4Tra](https://semantic-transportation.github.io/sem4tra-kg-website/) - International Workshop on Semantics for Transport and Logistics, colocated with the SEMANTiCS Conference.
     - 2026: [Paper and workshop materials](https://github.com/Matdata-eu/paper-sem4tra2026) - Seventh workshop, held in Ghent on 15 September 2026.
  

### Master Classes - Workshops

* [SHACL validation](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/rail-data-forum-2025/data-validation-masterclass) - Master class for SHACL at RDF 2025, Cluj, Romania.

* [Railway Data Modelling](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/rail-data-forum-2025/railway-data-modelling) - Workshop on railway modelling at RDF 2025, Cluj, Romania.

* [SPARQL for beginners](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/rail-data-forum-2025/sparql-for-beginners-masterclass) - Master class on SPARQL for beginners at RDF 2025, Cluj, Romania.

* [RDFisation](https://gitlab.com/era-europa-eu/public/interoperable-data-programme/era-ontology/rail-data-forum-2025/rdfisation-masterclass) - Master class on RDF conversion using YARRRML/RML at RDF 2025, Cluj, Romania.

## Other Awesome
* [Awesome SHACL Resources](https://github.com/semantalytics/awesome-semantic-web#shacl) - SHACL specifications, extensions, test suites, and implementations.
* [Awesome Semantic Web](https://github.com/semantalytics/awesome-semantic-web)
* [Awesome Knowledge Graph Construction Tools](https://github.com/kg-construct/awesome-kgc-tools)
* [awesome-knowledge-graph](https://github.com/totogo/awesome-knowledge-graph)
  

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.  
Some of the content were copied from other awesome lists


## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Ghislain A. has waived all copyright and related or neighboring rights to this work.
