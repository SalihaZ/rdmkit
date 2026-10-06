---
title: IFB
contributors: [Olivier Collin, Marie-Christine Jacquemot, Paulette Lieby, Flora D'Anna, Anne-Françoise Adam-Blondon]
editors: [Korbinian Bösl, Bert Droesbeke, Flora D'Anna]
description: The French Bioinformatics Institute (IFB) offers IT infrastructure and bioinformatics expertise to support researchers in Life Sciences.
page_id: ifb
affiliations: ["ELIXIR Europe", "FR"]
related_pages: 
  Your_tasks: [dmp, data_organisation, storage, data_publication, data_transfer, metadata, data_analysis]
  Your_domain: []
training:
  - name: IFB Search query in TeSS
    registry: TeSS
    url: https://tess.elixir-europe.org/search?q=IFB
  - name: FAIR principles in bioinformatics and data management
    url: https://moodle.france-bioinformatique.fr/course/index.php?categoryid=2&lang=fr
  - name: Data management training at the IFB
    url: https://www.france-bioinformatique.fr/en/training/
  - name: Doranum, the french national resources to support the scientific community for data management and sharing
    url: https://doranum.fr
  - name: Documentation for the IFB core cluster
    url: https://ifb-elixirfr.gitlab.io/cluster/doc/
  - name: Documentation for the Biosphere cloud federation
    url: https://ifb-elixirfr.github.io/biosphere/
---

## What is the IFB data management tool assembly?

[ELIXIR-FR / IFB](https://www.ifb-elixir.fr/) develops an infrastructure in order to support Life science data management all along the data life cycle. ELIXIR-FR / IFB benefits from and contributes to both the ELIXIR’s RDM community and Recherche Data Gouv [Recherche.Data.Gouv](https://recherche.data.gouv.fr/en), the French National ecosystem supporting data management.

## Who can use the IFB data management tool assembly?

The ELIXIR-FR / IFB infrastructure for Life science data is accessible to researchers in France and their collaborators. Eligible researchers can apply through the IFB help desk page and get support through the dedicated help pages. Depending on the resources, fees may apply. It is therefore advisable to contact ELIXIR-FR / IFB during the planning phase of the project.


## For what can you use the IFB data management tool assembly?

{% include image.html file="fr_ifb_assembly_update.svg" caption="Figure 1. The French Bioinformatics Institute (IFB) tool assembly." alt="IFB RDMkit" %}

### Data management planning

IFB recommends [DMP-OPIDoR](https://dmp.opidor.fr) or {% tool "data-stewardship-wizard" %} as tools for writing a Data Management Plan (DMP).

IFB hosts its own instance [DSW@IFB](https://dsw.france-bioinformatique.fr/wizard/dashboard), freely accessible to the french research community. IFB has co-developed with the other National Research Infrastructures in Biology and Health ([INBS](https://www.ibisa.net/inbs/)) a multidisciplinary DMP model for facilities, covering bioimaging, genomics, proteomics, cytometry and metabolomics.

DMP-Opidor is hosted and maintained at INIST-CNRS and tailored to the needs of the French research community. Its machine-actionable format is fully compliant with the RDA DMP Common Standard and covers both data and software management within a single plan.
 

### Data collection

IFB facilitates data and [metadata collection](https://rdmkit.elixir-europe.org/collecting) through the [madbot](https://madbot.france-bioinformatique.fr/) software that stores metadata along with links to the data in their storage place during the project or through instances of Seek. Storage capacities are provided by IFB’s National Network of Computing Resources [NNCR](https://nncr-clusters.france-bioinformatique.fr/). 

To support data collection along with standard metadata, IFB is providing [{% tool "fairdom-seek" %}](https://seek4science.org/) instance is available at [GenOuest](https://research-sharing.cesgo.org). 

### Data processing and analysis 

IFB infrastructure gives you access to several flavours of computing resources, according to your needs and expertise:

* Several [clusters](https://www.ifb-elixir.fr/en/services/computing-infrastructure/ifb-clusters/). 
* The [Galaxy France](https://usegalaxy.fr) portal operated by IFB members in complement of the [Galaxy Europe](https://usegalaxy.eu). 
* The cloud federation [Biosphere](https://biosphere.france-bioinformatique.fr). A list of the different appliances is available on the [RainBio catalogue](https://biosphere.france-bioinformatique.fr/catalogue/). 

Each of the computing resources offers its own storage solution tailored for the needs of the users (fast access, capacitive).

IFB infrastructure can also help you with bioinformatics analysis of your data. Many of the IFB member platforms can provide [expertise](https://www.ifb-elixir.fr/en/services/data-analysis/) for data analysis in many domains (genomics, metagenomics, transcriptomics) as well as software development. A list of the tools developed by all IFB members is available [here](https://www.ifb-elixir.fr/en/services/tools-services-catalog/). 

For bioimage analysis, researchers can explore {% tool "biii" %}, the BioImage Informatics Index. Biii is a community-driven registry that catalogues bioimage analysis software, workflows, training resources and example datasets.

### Data sharing and publishing
It is good practice to publish your data in repositories. IFB encourages researchers to browse the list of {% tool "elixir-deposition-databases-for-biomolecular-data" %} and the {% tool "elixir-core-data-resources" %} to identify the appropriate repository for their data type. In addition, a list of [trusted repositories](https://recherche.data.gouv.fr/en/repositories) is maintained by Recherche Data Gouv.

IFB members contribute to domain-specific thematic repositories hosted in France: - {% tool "imgt" %}, - {% tool "orphadata-science" %} 
For the semantic annotation of data, software and services, IFB recommends the use of {% tool "edam" %}, a comprehensive ontology of bioinformatics operations, data types, formats and topics. 
To ensure that published data are findable and citable, IFB promotes the attribution of persistent identifiers through {% tool "datacite" %}.

Research software produced in life science projects can be preserved and shared through {% tool "software-heritage" %}, the universal archive of software source code. 

The french scientific community benefit from [Recherche.Data.Gouv](https://recherche.data.gouv.fr/en) a national Dataverse repository. This repository is associated with [thematic reference centres](https://recherche.data.gouv.fr/en/page/thematic-reference-centers-providing-expertise-for-individual-scientific-fields) and data management clusters. IFB is the reference centre for Life Science. 

### Compliance monitoring & measurement

IFB infrastructure promotes the implementation of the FAIR principles. To this end, IFB provides and encourages the use of the [FAIR-Checker](https://fair-checker.france-bioinformatique.fr/), a web interface aimed at monitoring the level of FAIRification of data resources. This tool uses the FAIRMetrics APIs to provide a global assessment and recommendations. It also uses semantic technologies to help users in annotating their resources with high-quality metadata.
