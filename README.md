# MosaicBase
[MosaicBase](http://49.4.21.8:8000) is a comprehensive knowledgebase for postzygotic mosaic variants from noncancer disease-related and healthy human individuals

## 1. Introduction

Postzygotic mosaic mutations refer to DNA changes arising after the formation of the fertilized egg, therefore only a fraction of somatic and/or germ cells in the human body would carry the mutation. If a mosaic mutation affects germ cells, it will have a chance to be transmitted to the offspring. MosaicBase is a database of mosaic mutations in non-cancer diseases and asymptomatic individuals. Through manual reviews of massive amounts of literature published in the past decades, we collect reliable mosaic mutations that are detected in non-cancer individuals and validated by multiple experimental methods. Mutations are classified according to its genomic position and mutation type. Detailed information about individuals and publications are also integrated into the database. This database aims to provide comprehensive information to researchers and physicians for a better understanding of the distribution and transmission of mosaic mutations in non-cancer genomes and facilitating genetic counseling.

## 2. Search

MosaicBase provides a friendly search engine for users to fetch useful data. You can search the database using disease name, range of genomic coordinate (in the format of 1:123456-234566, genome assembly: GRCh37/hg19), gene symbol, or Entrez Gene ID. The search engine is comparable with space-delimited multiple search terms.

<img src="https://user-images.githubusercontent.com/17311837/157302439-d740ae1b-bd38-4618-a2de-bf04e114e769.png" alt="Search Bar" width=100%> 

Further, an advanced ontology-based searching method is also provided. All the diseases collected in the database are classified into categories according to the disease ontology. So, you can choose the disease you are interested in through the disease ontology category. Then, click on the disease term, a detailed description for this disease and all the related mosaic mutations we have collected are shown in the right panel.

<img src="https://user-images.githubusercontent.com/17311837/157302474-cb8ad0a1-0627-42e6-99a7-d3962ce6242a.png" alt="Advanced Search" width=100%> 

## 3. Data presentation

### 3.1. Search result page

<img src="https://user-images.githubusercontent.com/17311837/157302524-22e14b1d-0599-43fc-b06e-8bb00da2c032.png" alt="Search Result" width=100%> 

This figure shows an example of the search result. The total number of mosaic mutations matching your searching criteria is shown on the top of the page, following the detailed information for each mutation. Many of the terms shown are linked to a detailed information page. The variant id links to the variant page. The Entrez Gene ID and Gene name link to the gene page. The mutation and location term link to genome browser. The disease term links to disease page. User can also export the search result to an excel table.

### 3.2. Variant Page

Detailed information is provided in the variant page, which are classified into four tabs.

3.2.1. Overview

Overview tab provides information on the specific variant including the position and changes on genome, RNA and protein, related disease, the detection method that found this mosaic mutation, as well as 18 different risk scores from CADD, Eigen, SIFT, DeFine, PhyloP, etc. Links to internal summary tables and external databases are also provided.

<img src="https://user-images.githubusercontent.com/17311837/157302599-22f97913-905b-41c7-a9b0-3a63b6710143.png" width=100%> 

3.2.2. Gene information

Gene information page mainly provides information of the related gene. This information is parsed from NCBI Gene. 

<img src="https://user-images.githubusercontent.com/17311837/157302669-08090e76-fabd-4a1d-8e31-30c88ddb0505.png" alt="Gene Info Tab" width=100%> 

3.2.3. Individual Information

This tab provides information on individuals having this mosaic mutation. And other useful information for this individual are also provided. Phenotypes are classified into three categories range from 1 to 3, denoting asymptomatic, milder phenotype that do not fulfill all the diagnostic criteria of the specific disorder, and phenotype that meets all the diagnostic criteria of the specific disease, respectively, according to the phenotype described in the published paper. 

<img src="https://user-images.githubusercontent.com/17311837/157302716-74752691-c848-4cb7-83e4-3254579df4ff.png" alt="Individual Info Tab" width=100%> 

3.2.4. Publication information

This tab provides useful information about the publication. 

<img src="https://user-images.githubusercontent.com/17311837/157302809-eaef1a73-f9cf-45fb-91f0-be6f8065c446.png" alt="Publication Info Tab" width=100%> 

### 3.3. Gene Page

The gene page provides the detailed information of the located gene.

<img src="https://user-images.githubusercontent.com/17311837/157302743-55dc1d4c-ea59-463e-bd12-f72c9dbd044d.png" alt="Publication Info Tab" width=100%> 


### 3.4. Disease Page

Similar to the gene page, disease page shows all the mosaic mutations related to this disease in our database.

<img src="https://user-images.githubusercontent.com/17311837/157302854-8e3703dd-4bbc-479f-814a-da91a2ade839.png" alt="Disease Page" width=100%> 

### 3.5. Individual Page

This page provides information on individuals. It also displays the information if more than one mosaic mutation were identified in this individual.

<img src="https://user-images.githubusercontent.com/17311837/157302892-1f7ef6a8-5937-4dea-a550-ae8ee50835b5.png" alt="Individual Page" width=100%> 

## 4. Genome Browser

Biodalliance Genome Browser provides a fast, interactive genome visualization for users. Mosaic mutations are shown in one track, along with other genetic and epigenetic tracks. Search by both of coordinates and gene symbols are enabled. More usage can be referred to http://www.biodalliance.org/started.html.

<img src="https://user-images.githubusercontent.com/17311837/157302186-e673e254-cc35-4aeb-9723-95db2092eed8.png" alt="Individual Page" width=100%> 

## 5. Submission System

If you have reliable knowledge on mosaic mutations that are not included in this database, you are welcomed to submit that to us. We will appreciate for your submission and examine the submitted information as soon as possible. 

## 6. Cite MosaicBase
Yang X., Yang C., Zheng X., Xiong L., Tao Y., Wang M., Ye A.Y., Wu Q., Dou Y., Luo J., Wei L., and Huang A.Y. 2020. MosaicBase: A Knowledgebase of Postzygotic Mosaic Variants in Noncancer Disease-related and Healthy Human Individuals. Genomics Proteomics Bioinformatics. Sep 8:S1672-0229(20)30098-X. PMID: [32911083](https://pubmed.ncbi.nlm.nih.gov/32911083/)
doi: [https://doi.org/10.1016/j.gpb.2020.05.002](https://doi.org/10.1016/j.gpb.2020.05.002)

## 7. Team:

Xiaoxu Yang

Changhong Yang

Xianing Zheng

August Yue Huang

Liping Wei (PI)

## 8. Contact Us:
[mosaicbase@mail.cbi.pku.edu.cn](mailto:mosaicbase@mail.cbi.pku.edu.cn)

