BIOCONTAINERS HACKATHON 2017: Reproducible Bioinformatics
---------------------------------------------------------

- Date: 9-11 October 2017
- Place: Institut Henri Poincaré, 11 Rue Pierre et Marie Curie, 75005 Paris, France
- [BioHachathon Workshop: Eventbrite Registration](https://www.eventbrite.co.uk/e/biocontainers-hackathon-reproducible-bioinformatics-tickets-35601135956) (**Closed**)

# Purpose

The “ELIXIR Software Deployment Group” is one of the six working groups of the ELIXIR tools platform. It has been recently formed to support bioinformatics software deployment efforts including packages and containers. At the moment this group is sustained by ELIXIR Nodes sharing common interest to work together on a harmonised strategy.This group would like to accelerate and consolidate the Containers platform as a Service, and the integration with other groups like Workflows & workbenches and Software tools (Bio.Tools) as defined in the ELIXIR work plan 2017. To do so we proposed to have a 2.5 days hackathon. In practice the hackathon will give us the opportunity to work in four different topics:

- Consolidate the integration between: Biocontainers [1] (biocontainers.pro), BioConda (https://bioconda.github.io/) and Bioshadock [2] (http://bioshadock.genouest.org/) initiatives.
- Define the future architeture of BioContainers: Containers registry, Containers Automatic Deplyment Systems. Also the integration with Bio.tools and Workflow systems such as Galaxy and CWL.
- Improve the metadata definition for BioContainers/BioConda.
- In addition, we will define a strategy (Metadata) for “Training Containers”, design an infrastructure for hosting containers in ELIXIR and engage the training community to create containers for training purposes. We will start developing containers for training.

# Current Agenda

## October 9  - 2017

- (9:00  - 9:10  AM) Registration & Welcome, Introduction (Victoria Dominguez Del Angel, IFB Elixir-FR)
- (9:10  - 9:30  AM) BioContainers: Current Status and Challenges (**Talk, Yasset Perez-Riverol, EMBL-EBI, UK**)
- (9:50  - 10:05 AM) BioConda and Mulled: Automatic Creation of Dockerfile-free BioContainers (**Talk, Bjorn, Freiburg, Germany**)
- (10:20 - 10:40 AM) **Coffee Break**
- (10:40 - 11:00 AM) Dockerfile - based BioContainers: (**Talk, Olivier Sallou, France**)
- (11:20 -         ) Planning of the Activities for 2 days Hackathon (**Yasset Perez-Riverol, EMBL-EBI, UK**)


### Hackathon Topics:

#### Metadata Session (10:40 - 1:00 PM)

- BioContainers Metadata Specification: 
   - Predicted name space?
   - Containers (BioContainers) and Packages (BioConda) Current Specification.
   - BioContainers for Services and databases (e.g. https://github.com/reactome/container)
   - BioContainers Metadata
      - License: Mandatory? [SPDX standard identifiers](https://spdx.org/licenses/) & the [SPDX specification](https://spdx.org/specifications)
      - Minimun Metadata inside each container. 
      - Base Images 
      - Versioning
      - Identifiers handling to other metadata services such as biotools, pubmed, RRID ([example](https://identifiers.org/rrid/RRID:SCR_005476)), or omicstools. 
   - Metadata for Training Containers.
      - Use Cases. 
      - Integration with Tess ELIXIR 
      - Data?, Materials?
   - Metadata Validator Tool. (**Hackathon**) Someone interested?  
   
#### Parallel Session: Training session in BioContainers (10:40 - 1:00 PM).
     Trainer (Olivier Sallou)     
 
 - What is Docker, rkt? Seeting your machine.   
 - What is BioContainers? 
 - How to create a BioContainers.  
   - Dockerfile Container. 
   - Conda Package Container. 
 - How to contribute with BioContainers. 
 
#### Architecture Session (2:00 - 4:00 PM) 
 
 - BioContainers Deployment Architecture:
   - Mulled BioContainers Architeure:
      - Current structure and Improvements. 
      - Backups, tarballs, source code, images. 
   - DockerFile-based Biocntainers Architecture:
      - Current Structure and Improvements.
      - Future architecture. 
      - Initial implementation of DockerFile-based containers.
   - Singularity Images.
   
#### Hackathon on Current Containers (2:00 - 6:00 PM) 

 - Review of current BioContainers:
   - Solve Duplications, broken and non-functional containers.
   - Create and Build current requested Containers.
 - Creation of Training Containers.
   - Training session on BioContainers and Containers in BioInformatics

#### Wrap-up of the sessions

## October 10 - 2017

- (9:00  - 9:20  AM) Galaxy Workflows integration with Containers. (**Talk, Bjorn, Freiburg, Germany**)
- (9:20  - 9:40  AM) Docker-based genomics tools and workflows (**Talk, Brian D. O'Connor, US**)
- (9:40  - 10:00 AM) Common Workflow languages and containers  (**Talk, Michael R Crusoe, US**)
- (10:00 - 10:20 AM) Coffee Break. 

### Hackathon Topics:

#### Workflows and BioContainers (10:20 - 1:00 PM)

  - MultiTools containers: Current approach and challenges. 
  - Workflow dependency conversion to MultiBioContainer.

#### Parallel Session: Hackathon (10:20 - 1:00 PM)
  
  - Creation of training containers (Rafael Jimenez, Victoria, Yasset Perez-Riverol). 
  - Annotation of BioConda/BioDocker Containers with Biotools Ids. 
  - Architecture for deployment of containers (Pablo Moreno / Olivier Sallou)
    

#### Parallel Session: BioContainers/Conda Registry (2:00 - 4:00 PM) 

  - Improvements of Metadata Search.
  - Reimplementation to handle BioConda/BioContainers/Singularity recipies.
  - Registry API.
  - CLI tool with same campabilities that the Web Interface.

#### Parallel Session: Creation of Training Containers (2:00 - 6:00 PM) 
  
  - Creation of Training Containers. 
  - Creation of Workflow Containers using multitools approach.   

#### Wrap-up of the sessions
#### Working Dinner at 7h30 PM at "Le Procope", 13 rue de l'Ancienne Comédie 75006 Paris



### October 11 - 2017 

- (9:00  - 9:20  AM) PRIDE and ProteoGenomics in Cloud (**Yasset Perez-Riverol, EMBL-EBI, UK**)
- (9:20  - 9:40  AM) PhenoMeNal overview and container orchestration for Galaxy batch scheduling with Kubernetes (**Talk, Pablo Moreno, EMBL-EBI, UK**)


#### (9:00 - ) Parallel Session: Hackathon. 
 
  - Creation of Training Containers. 
  - Creation of Workflow Containers using multitools approach.

#### (9:00 - ) Parallel Session: Community Engagement.  

  - Engagement with Community/Insdustry/Journals
  - Publications RoadMap and Grants/Fundings Posibilities
    - Discussion of current Grant proposal in ELIXIR.  
  - ELIXIR Software Deployment Group & BioContainers Group
    - Organization
    - RoadMap
    - Integration with other Initiatives.
  - Plans for 2018.

- (11:30 AM) Conclusions and Wrap-up of the Hackathon.


## Bibliography
[1] Leprevost, F. D. V.; Grüning, B. A.; Aflitos, S. A.; Röst, H. L.; Uszkoreit, J.; Barsnes, H.; Vaudel, M.; Moreno, P.; Gatto, L.; Weber, J.; et al. BioContainers: an open-source and community-driven framework for software standardization. Bioinformatics 2017.

[2] Moreews, F.; Sallou, O.; Ménager, H.; Bras, Y. L.; Monjeaud, C.; Blanchet, C.; Collin, O. BioShaDock: a community driven bioinformatics shared Docker-based tools registry. F1000Research 2015.
