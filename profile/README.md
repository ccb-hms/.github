# The Center for Computational Biomedicine
## About Us
[The Center for Computational Biomedicine](https://computationalbiomed.hms.harvard.edu/) (CCB) is a multi-disciplinary team of computational and quantitative scientists that develops shared data and analytic resources.

We serve as a Hub for computational science education across Harvard Medical School, offering skills workshops, guided learnings, and tailored educational resources.

We collaborate on projects with labs, programs, and departments to develop tools, platforms, and other data science and computational resources that broadly enable discovery and innovation. 

Our strong mandate is to enable graduate students, postdoctoral fellows, research staff, and faculty across all departments of the HMS quadrangle. View our Projects, Tools and Educational Resources to see our work and contact us to develop more resources together. 

> Increasingly complex data sets and advancing computation methods represent a challenge but also an opportunity to develop tools and interfaces that will help researchers and students reach sound, reproducible conclusions. Although not simple, these problems are solvable and their promise is great. 

-- Dr. Robert Gentleman, Executive Director

## Organization
At our core, CCB is made of four work groups: Computational Biology, Data & Analytics Platforms, Knowledge Representation, and Education.

### [Computational Biology](https://computationalbiomed.hms.harvard.edu/projects/genetics-genomics/)
CCB’s Computational biology group aims at building sustainable tools and integrated data science products that empower experimental data-generating groups to explore, analyze, and interpret their data.  We aim to provide experimental groups with data analysis competence regarding computational, statistical, and bioinformatic aspects. This also includes to enable researchers to easily put their datasets in context of existing databases of high-throughput genomic datasets.

### [Data & Analytics Platforms](https://computationalbiomed.hms.harvard.edu/projects/data-analytics-platforms/)
Machine learning and biostatistics applications in modern clinical- and bio- informatics require analytic platforms that are built to scale, and to serve domain-specific needs. The Data and Analytic Platforms Group at CCB delivers these solutions for researchers spanning epidemiology, bioinformatics, healthcare economics, and basic science specialties. 

### [Knowledge Representation](https://computationalbiomed.hms.harvard.edu/projects/knowledge-representation/)
Artificial Intelligence applications require Knowledge Representation and Reasoning to encode knowledge in a way that computers can reason with. The Knowledge Representation group at CCB develops ontology-based solutions to facilitate the annotation, search, and meta-analysis of biomedical data originating from diverse sources. The data include electronic health records, healthcare insurance claims, genomics, environmental exposure, among others.

### [Education](https://computationalbiomed.hms.harvard.edu/education/)
CCB is committed to serving as a centralized resource for computational, bioinformatics, and statistical education for graduate students, postdocs, faculty, and research staff across HMS. We work alongside departments and other research communities at HMS to tailor education for their research domain and current skill levels. We customize a variety of educational resources, including self-guided modules, trainings, bootcamps, and course materials.


## Projects and Repositories to Notice
### [Epiconductor](epiconductor.org)
In the field of Epidemiology, large and complex datasets present challenges to potential user’s access and analysis of the data. In addition, better mechanisms are needed for researchers to publish shareable scripts that would reproduce their analyses.
Epiconductor aims to address these challenges by establishing a community that will: 1) Package and share code to standardize data and data access and 2) Become a resource for sharing and accessing software packages, training materials, and connecting with fellow researchers to analyze these data resources.

### [HSDM Computer Vision](https://computationalbiomed.hms.harvard.edu/projects/project-details/hsdm-research-data-repository/)
The Dentex Challenge 2023 aims to provide insights into the effectiveness of AI in dental radiology analysis and its potential to improve dental practice by comparing frameworks that simultaneously point out abnormal teeth with dental enumeration and associated diagnosis on panoramic dental X-rays. The dataset comprises panoramic dental X-rays obtained from three different institutions using standard clinical conditions but varying equipment and imaging protocols, resulting in diverse image quality reflecting heterogeneous clinical practice. It includes X-rays from patients aged 12 and above, randomly selected from the hospital's database to ensure patient privacy and confidentiality.

### [Text2Term](https://computationalbiomed.hms.harvard.edu/tools-and-technologies/tools-tech-details/text2term-ontology-mapping/)
Our open-source tool text2term maps free-text descriptions of biomedical entities to controlled terms in ontologies. The tool is highly configurable and can be used in multiple ways that cater to different users and expertise levels—it is available on PyPi and can be used programmatically as any Python package; it can also be used via a command-line interface; or via our hosted, graphical user interface-based Web application (https://text2term.hms.harvard.edu); or by deploying a local instance of our interactive application using Docker.

### [Bioplex](https://computationalbiomed.hms.harvard.edu/projects/project-details/extensions-and-updates-to-the-bioplex-r-and-python-packages/)
CCB implemented programmatic access to the BioPlex PPI networks and integration with related resources from within R and Python. Besides PPI networks for 293T and HCT116 cells, this includes access to CORUM protein complex data, PFAM protein domain data, PDB protein structures, and transcriptome and proteome data for the two cell lines. The implemented functionality serves as a basis for integrative downstream analysis of BioPlex PPI data with domain-specific R and Python packages, including efficient execution of maximum scoring subnetwork analysis, protein domain-domain association analysis, mapping of PPIs onto 3D protein structures, and analysis of BioPlex PPIs at the interface of transcriptomic and proteomic data.

### [Merfish](https://computationalbiomed.hms.harvard.edu/projects/project-details/multiplexed-error-robust-fluorescence-in-situ-hybridizationmerfish/)
CCB worked on making MERFISH datasets accessible to the wider R/Bioconductor community, and connecting MERFISH data with the R/Bioconductor ecosystem of analysis packages and fostered new developments. This effort included first implementing access to publicly available MERFISH datasets from within R/Bioconductor and connecting the data package to novel ways of analyzing spatial transcriptomic data. Afterwards, the CCB team worked on connecting the data package and analysis results with integrative visualization tools to enable interactive exploration of segmentation, expression, and cell metadata on images.

### [Mouse Aging Multi-omics Data Integration](https://computationalbiomed.hms.harvard.edu/projects/project-details/aging-intervention-multi-omics-data-integration-and-biomarker-discovery/)
CCB works with Rubin Lab to develop a FAIR analysis-ready data resource of different aging omics datasets including the aging mouse brain single cell study (Ximerakis et al., 2019), aging mouse brain parabiosis single cell study (Ximerakis et al., 2023), aging mouse brain parabiosis proteomics study (Rubin lab, unpublished), aging mouse brain microbiome manipulation single nucleus study (Rubin lab, unpublished), and microbiome manipulation plasma proteomics (Rubin lab, unpublished).

### [Computational Needs Survey](https://computationalbiomed.hms.harvard.edu/education/skills-surveys/)
We put out a yearly survey to graduate students and postdocs to broadly identify needs, attitudes, and preferences for computational training at HMS. Areas we survey include statistics, machine learning, imaging, computational biology, and computational skills. Survey results are made freely available for groups across HMS to help them plan their educational offerings.

## Repository Organization
### Computational Biology
|Repository                                                                                                                       |Project          |
|---------------------------------------------------------------------------------------------------------------------------------|-----------------|
|[AlphaMissenseR](https://github.com/ccb-hms/AlphaMissenseR)                                                                      |AlphaMissense                                                                                                                                                     |
|[BioPlex](https://github.com/ccb-hms/BioPlex)                                                                                    |[BioPlex](https://computationalbiomed.hms.harvard.edu/projects/project-details/extensions-and-updates-to-the-bioplex-r-and-python-packages/)                      |
|[BioPlexAnalysis](https://github.com/ccb-hms/BioPlexAnalysis)                                                                    |[BioPlex](https://computationalbiomed.hms.harvard.edu/projects/project-details/extensions-and-updates-to-the-bioplex-r-and-python-packages/)                      |
|[BioPlexPy](https://github.com/ccb-hms/BioPlexPy)                                                                                |[BioPlex](https://computationalbiomed.hms.harvard.edu/projects/project-details/extensions-and-updates-to-the-bioplex-r-and-python-packages/)                      |
|[BioPlexSplicing](https://github.com/ccb-hms/BioPlexSplicing)                                                                    |[BioPlex](https://computationalbiomed.hms.harvard.edu/projects/project-details/extensions-and-updates-to-the-bioplex-r-and-python-packages/)                      |
|[GraphViewer](https://github.com/ccb-hms/GraphViewer)                                                                            |[BioPlex](https://computationalbiomed.hms.harvard.edu/projects/project-details/extensions-and-updates-to-the-bioplex-r-and-python-packages/)                      |
|[EndothelialAtlasDocker](https://github.com/ccb-hms/EndothelialAtlasDocker)                                                      |[EndothelialAtlas](https://computationalbiomed.hms.harvard.edu/projects/project-details/rna-sequencing-atlas-of-vascular-endothelial-cells/)                      |
|[MerfishData](https://github.com/ccb-hms/MerfishData)                                                                            |[Merfish](https://computationalbiomed.hms.harvard.edu/projects/project-details/multiplexed-error-robust-fluorescence-in-situ-hybridizationmerfish/)               |
|[MerfishDataAnalysis](https://github.com/ccb-hms/MerfishDataAnalysis)                                                            |[Merfish](https://computationalbiomed.hms.harvard.edu/projects/project-details/multiplexed-error-robust-fluorescence-in-situ-hybridizationmerfish/)               |
|[OSCA.intro.qmd](https://github.com/ccb-hms/OSCA.intro.qmd)                                                                      |OSCA quarto                                                                                                                                                       |
|[MouseAgingData](https://github.com/ccb-hms/MouseAgingData)                                                                      |[Rubin Multi-omics](https://computationalbiomed.hms.harvard.edu/projects/project-details/aging-intervention-multi-omics-data-integration-and-biomarker-discovery/)|
|[MutantHuntWGS](https://github.com/ccb-hms/MutantHuntWGS)                                                                        |Winston YeastWGS                                                                                                                                                  |
|[BiocChallenges](https://github.com/ccb-hms/BiocChallenges)                                                                      |                                                                                                                                                                  |
|[cachehttp](https://github.com/ccb-hms/cachehttp)                                                                                |                                                                                                                                                                  |
|[CyCIFData](https://github.com/ccb-hms/CyCIFData)                                                                                |                                                                                                                                                                  |
|[expressionviewer](https://github.com/ccb-hms/expressionviewer)                                                                  |                                                                                                                                                                  |
|[getting-started-with-genomics-tools-and-resources](https://github.com/ccb-hms/getting-started-with-genomics-tools-and-resources)|                                                                                                                                                                  |
|[graphframes](https://github.com/ccb-hms/graphframes)                                                                            |                                                                                                                                                                  |
|[Imputation](https://github.com/ccb-hms/Imputation)                                                                              |                                                                                                                                                                  |
|[scConform](https://github.com/ccb-hms/scConform)                                                                                |                                                                                                                                                                  |
|[SpatialData](https://github.com/ccb-hms/SpatialData)                                                                            |                                                                                                                                                                  |
|[sphinx-tutorial](https://github.com/ccb-hms/sphinx-tutorial)                                                                    |                                                                                                                                                                  |
|[stan_workshop_data](https://github.com/ccb-hms/stan_workshop_data)                                                              |                                                                                                                                                                  |


### Data & Analytics Platforms
|Repository                                                                             |Project                                                                                                                       |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
|[NHANES](https://github.com/ccb-hms/NHANES)                                            |[Epiconductor](https://epiconductor.org/)                                                                                     |
|[nhanes-exploration](https://github.com/ccb-hms/nhanes-exploration)                    |[Epiconductor](https://epiconductor.org/)                                                                                     |
|[phonto](https://github.com/ccb-hms/phonto)                                            |[Epiconductor](https://epiconductor.org/)                                                                                     |
|[edw_acs](https://github.com/ccb-hms/edw_acs)                                          |Exposome Data Warehouse                                                                                                       |
|[edw_tiger](https://github.com/ccb-hms/edw_tiger)                                      |Exposome Data Warehouse                                                                                                       |
|[computervision](https://github.com/ccb-hms/computervision)                            |[HSDM Research Data Repository](https://computationalbiomed.hms.harvard.edu/projects/project-details/hsdm-research-data-repository/)|
|[MedEd-AI](https://github.com/ccb-hms/MedEd-AI)                                        |MedEd AI                                                                                                                      |
|[docker-analytic-workbench](https://github.com/ccb-hms/docker-analytic-workbench)      |                                                                                                                              |
|[docker-r-command-line](https://github.com/ccb-hms/docker-r-command-line)              |                                                                                                                              |
|[docker-rstudio-server](https://github.com/ccb-hms/docker-rstudio-server)              |                                                                                                                              |
|[docker-ubuntu-interactive](https://github.com/ccb-hms/docker-ubuntu-interactive)      |                                                                                                                              |
|[esm](https://github.com/ccb-hms/esm)                                                  |                                                                                                                              |
|[HarvardInovalonUserGuide (Documentation)](https://github.com/ccb-hms/HarvardInovalonUserGuide (Documentation))|                                                                                                                              |
|[SqlServerS3Appliance](https://github.com/ccb-hms/SqlServerS3Appliance)                |                                                                                                                              |

### Knowledge Representation
|Repository                                                                             |Project                                                                                                                        |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
|[NHANES-metadata](https://github.com/ccb-hms/NHANES-metadata)                          |[Epiconductor](https://epiconductor.org/)                                                                                     |
|[GWASCatalogSearchDB](https://github.com/ccb-hms/GWASCatalogSearchDB)                  |[GWAS Search](https://computationalbiomed.hms.harvard.edu/projects/project-details/opengwas-phenotype-mapping/)               |
|[gwasCatSearch](https://github.com/ccb-hms/gwasCatSearch)                              |[GWAS Search](https://computationalbiomed.hms.harvard.edu/projects/project-details/opengwas-phenotype-mapping/)               |
|[opengwas-search](https://github.com/ccb-hms/opengwas-search)                          |[GWAS Search](https://computationalbiomed.hms.harvard.edu/projects/project-details/opengwas-phenotype-mapping/)               |
|[openGWASSearchDB](https://github.com/ccb-hms/openGWASSearchDB)                        |[GWAS Search](https://computationalbiomed.hms.harvard.edu/projects/project-details/opengwas-phenotype-mapping/)               |
|[HuBMAPy](https://github.com/ccb-hms/HuBMAPy)                                          |[HuBMAP](https://computationalbiomed.hms.harvard.edu/projects/project-details/programmatic-interface-to-hubmap-ontology/)     |
|[smores-ontology-reasoner](https://github.com/ccb-hms/smores-ontology-reasoner)        |[HuBMAP](https://computationalbiomed.hms.harvard.edu/projects/project-details/programmatic-interface-to-hubmap-ontology/)     |
|[ontology-mapper](https://github.com/ccb-hms/ontology-mapper)                          |[text2term](https://computationalbiomed.hms.harvard.edu/tools-and-technologies/tools-tech-details/text2term-ontology-mapping/)|
|[ontology-mapper-ui](https://github.com/ccb-hms/ontology-mapper-ui)                    |[text2term](https://computationalbiomed.hms.harvard.edu/tools-and-technologies/tools-tech-details/text2term-ontology-mapping/)|
|[ontology-utilities](https://github.com/ccb-hms/ontology-utilities)                    |                                                                                                                              |


### Education
|Repository                              |Project|
|---------------------------------------------------------------------------------------|-------|
|[hcp-bootcamp](https://github.com/ccb-hms/hcp-bootcamp)                                |      |
|[hmc-clinic-2022-23](https://github.com/ccb-hms/hmc-clinic-2022-23)                    |      |
|[hsdm-r-course](https://github.com/ccb-hms/hsdm-r-course)                              |      |
|[immunology-bootcamp-2023](https://github.com/ccb-hms/immunology-bootcamp-2023)        |      |
|[Intro-to-R-Semisynchonous](https://github.com/ccb-hms/Intro-to-R-Semisynchonous)      |      |
|[Intro-to-R-Synchonous](https://github.com/ccb-hms/Intro-to-R-Synchonous)              |      |
|[mmsci-bootcamp-2023](https://github.com/ccb-hms/mmsci-bootcamp-2023)                  |      |
|[osca-workbench](https://github.com/ccb-hms/osca-workbench)                            |      |
|[systems-immunology-workshops](https://github.com/ccb-hms/systems-immunology-workshops)|      |
|[workbench-python-workshop](https://github.com/ccb-hms/workbench-python-workshop)      |      |
