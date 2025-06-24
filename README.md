# Dataset title

## Table of Contents

- [1. GENERAL INFORMATION](#1-general-information)
- [2. METHODOLOGICAL INFORMATION](#2-methodological-information)
  - [2.1 Research questions, methods and envisioned uses](#21-research-questions-methods-and-envisioned-uses)
  - [2.2 Methods for processing the data](#22-methods-for-processing-the-data)
  - [2.3 Instrument- or software-specific information](#23-instrument--or-software-specific-information)
- [3. FILE OVERVIEW](#3-file-overview)
  - [3.1 File List](#31-file-list)
  - [3.2 Relationship between files](#32-relationship-between-files)
  - [3.3 File formats and naming conventions](#33-file-formats-and-naming-conventions)
- [4. DATA-SPECIFIC INFORMATION](#4-data-specific-information)
  - [4.1 Data Category A](#41-data-category-a)
  - [4.2 Data Category B](#42-data-category-b)
  - [4.3 Data Category C](#43-data-category-c)
  - [4.4 Data Category D](#44-data-category-d)
- [5. SHARING/ACCESS INFORMATION](#5-sharingaccess-information)
  - [5.1 Licenses/restrictions placed on the data](#51-licensesrestrictions-placed-on-the-data)
  - [5.2 Links to other resources](#52-links-to-other-resources)
  - [5.3 Recommended citation for this dataset](#57-recommended-citation-for-this-dataset)


# 1. GENERAL INFORMATION

## 1.1 Title of Dataset
Urban Stream Restoration: building a more resilient urban environmental system - Case of Poznań, Poland.

## 1.2 Dataset description
The research project was carried out as part of the MSc Urbanism elective course *Applied Spatial Analytics for Sustainable Urban Development* (ARFW0501) at TU Delft. This course is based on the ReBioClim project, an initiative funded by the Interreg Central Europe Program. ReBioClim aims to revitalize small urban streams across European cities to promote biodiversity, address the impacts of climate change, and enhance urban quality of life. The project focuses on stream restoration efforts in four Central European cities: Dresden, Jablonec nad Nisou, Poznań, and Senica.The dataset used in this study is based on the case of **Poznań**. Additional details about the ReBioClim project can be accessed [here](https://www.interreg-central.eu/projects/rebioclim/)

In this course, we explored urban stream restoration in Poznań, Poland, using two primary methodological approaches: Multi-Criteria Decision Analysis (MCDA) and Typology Construction. For each method, we identified relevant objectives and formulated research questions tailored to the respective analytical framework. This dataset contains quantitative spatial data on biodiversity, quality of life, and climate adaptation metrics for Poznań, organised in a 500m hexagonal grid system. 

## 1.3 Author Information
A. Investigator 
- Name: Stepan Prikazchikov
- Institution: TU Delft Faculty of Architecture & the Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: s.a.prikazchikov@student.tudelft.nl

B. Investigator 
- Name: Roger Marin de Yzaguirre
- Institution: TU Delft Faculty of Architecture & the Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: r.marindeyzaguirre@student.tudelft.nl

C. Investigator 
- Name: Yaying Hao
- Institution: TU Delft Faculty of Architecture & the Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: y.hao-3@student.tudelft.nl

D. Investigator 
- Name: Jaee Naik
- Institution: TU Delft Faculty of Architecture & the Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: jnaik@tudelft.nl

E. Associated study personnel (Tutor)
- Name: Daniele Cannatella
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: d.cannatella@tudelft.nl

F. Associated study personnel (Tutor)
- Name: Claudiu Forgaci
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: c.forgaci@tudelft.nl

G. Associated study personnel (Tutor)
- Name: Yehan Wu
- Institution: Delft University of Technology, Faculty of Architecture & The Built Environment
- Address: Julianalaan 134, 2628 BZ Delft
- Email: Y.Wu-13@tudelft.nl

## 1.4 Dates of data collection
- Primary data processing: May 2025 to June 2025
- OSM Data Sources: Latest available as of May 2025
- NDVI satellite data, Flooding Data: May 2025 [Copernicus](https://dataspace.copernicus.eu/explore-data/data-collections/sentinel-data/sentinel-2) 
- Population Date: May 2024 [WorldPop Hub](https://hub.worldpop.org/)
- Landcover Data: May 2025 [ESA-Worldcover](https://esa-worldcover.org/en)

## 1.5 Geographic location of data collection
Poznań, Poland

## 1.6 Keywords
Urban Stream Restoration, Urban rivers, River integration, Multi-criteria analysis, GIS

## 1.7 Language
English

## 1.8 Information about funding sources that supported the collection of the data
-NA-

# 2. METHODOLOGICAL INFORMATION
## 2.1 Research questions, methods and envisioned uses
The report uses two primary methodological approaches: Multi-Criteria Decision Analysis (MCDA) and Typology Construction. 
For each method, relevant objectives were identified and research questions were formulated and tailored.

Method 1: MCDA- In the case of MCDA, the selection of criteria and the rationale behind their inclusion will be detailed in the Methods section.

Method 2: Typology Construction- In this method we introduce the objective of generating meaningful clusters that categorize spatial units adopted from MCDA based on shared characteristics. In the context of stream restoration in Poznań, a specific research question is formulated to align with this methodological approach. To address this question, a set of variables is selected, and the rationale behind the selection of these variables is grounded in both theoretical relevance and practical applicability to the local context.

We employed Multi-Criteria Decision Analysis (MCDA) as a structured framework to evaluate spatial units based on their potential to address three core objectives: **enriching biodiversity, promoting climate adaptation, and improving quality of life**. 

Each of these objectives corresponds to a specific research question that guides the analysis toward actionable insights for stream restoration. A critical step in applying MCDA lies in the careful selection and weighting of evaluation criteria. These weights reflect the relative importance of each criterion in relation to the research question at hand and directly influence the spatial prioritization outcomes. Therefore, understanding how we assign these weights—whether based on theoretical frameworks, empirical evidence, stakeholder input, or expert judgment—is essential for ensuring both methodological transparency and contextual relevance. 
This paper explores the logic behind such weight assignment, arguing that the formulation of the research question should guide both the selection of indicators and the emphasis placed on them.

### 2.1.1 Research questions (MCDA): 
Which areas are most in need of intervention through integrated interventions that enhance biodiversity, support climate adaptation, and improve neighborhood quality of life?

**Research Sub-Question:**
* Which areas have a low ecological value and are in need of restoration to enrich the biodiversity? (Enrich Biodiversity)  
- Which areas are most in need of interventions to promote climate adaptation? (Promote Climate Adaptation)  
+ Which areas are most in need of neighborhood-oriented interventions that improve the quality of life of local residents? (Improve Quality of Life)  

### 2.1.2 Research questions (Typology Construction): 
Which locations both need and are ready for restoration interventions to maximize impact and feasibility?

### 2.1.3 Envisioned uses of the dataset
The dataset will serve as a decision support tool for future restoration and planning interventions along the river in Poznań by identifying priority zones where stream restoration solutions can have the greatest impact.

**Envisioned Uses of the Dataset:**
- Integrated spatial planning   
- Supporting environmental monitoring and impact analysis over time  
- Assisting local governments in making data-driven decisions for environmental improvements  
- Informing the design of green infrastructure and climate adaptation strategies  
- Supporting community engagement through transparent, data-informed planning  
- Academic research
  
## 2.2 Methods for processing the data
**Deciding the Spatial Unit of Analysis: Why Hexagon Grid and What are the Parameters?**
For the spatial analysis, the study area was subdivided using a hexagonal grid, which served as the primary unit of analysis. The choice of hexagons was narrowed down by several methodological advantages. First, hexagonal cells maintain equal distance to all neighboring cells, which supports reduces directional bias in spatial calculations. Second, the use of hexagons helps to minimize edge effects that commonly arise in grid-based spatial analysis, thereby ensuring more consistent and accurate representation of spatial phenomena. 

The size of the hexagonal cells was determined through a balance between spatial resolution and computational feasibility. A diameter of 500 meters was selected, corresponding approximately to a 5–10 minute walking distance. This resolution also provides a reasonable number of spatial units across the city. 

**MCDA Methodology and Indicators-**
Multi-Criteria Decision Analysis (MCDA) is a subfield of operations research that systematically evaluates multiple, often conflicting, criteria in the decision-making process. The application of the MCDA methodology begins with the formulation of a primary goal. This overarching goal is then decomposed into specific objectives, each of which is translated into a research question. For each research question, a set of criteria is identified to assess various dimensions relevant to the objective. These criteria are subsequently assigned weights to reflect their relative importance in influencing the overall outcome.\

The evaluation culminates in the development of a synthetic map for each research question, which integrates the weighted criteria into a comprehensive spatial representation. These maps serve as analytical tools that encapsulate the combined perspectives of multiple stakeholders, thereby supporting informed and balanced decision-making.\

In the context of our study on urban stream restoration in Poznań, the principal objective is to enhance the resilience of the urban environmental system. In this study, resilience is conceptualized through three key dimensions: **Enhancing Biodiversity**, **Promoting Climate Adaptation** and **Improving Quality of Life**. Each of these dimensions is formulated as a distinct research question

**Typology Construction and Fields-** 
Typology Construction is a method used to classify areas or elements based on shared combinations of characteristics. In the context of urban stream restoration, our aim in applying this method is to incorporate variables from multiple domains, such as ecological, social, and morphological, into a clustering process that reveals distinct area types. By identifying the defining features of each cluster, we can better determine which types of restoration strategies are most suitable for each group.

Two key components must be defined for this method. The first is the spatial unit: we adopt the same unit used in the MCDA process, which is hexagonal grids with a diameter of 500 meters, applied along streams with a 300 meter buffer zone. The second is the set of relevant variables,which are selected from key indicators used in the MCDA analysis and categorized to effectively represent the characteristics of each domain.

Discussed variables: **Channel morphology, Sinuosity, Floodplain width, Open water surface, Land use cover, Impervious surfaces, Vegetation, Green space connectivity, Mobility, Slow mobility accessibility, Building morphology, Floor area ratio**

## 2.3 Instrument- or software-specific information
-  QGIS was used to map and analyze spatial datasets (version 3.34.12)
-  RStudio was employed to collate, visualize the report findings (4.5.0)
-  Copernicus satellite data for NDVI calculations

# 3. FILE OVERVIEW
Single versions of the dataset.

## 3.1 File List
_"synthetic_MCDA_map.gpkg"_:  
This file contains Normalized Data on Biodiversity, Climate Adaptation & Quality of Life Along the streams in Poznań
The file also contains Aggregated Data for each category.

## 3.2 Relationship between files:
The geopackage contains a single spatial layer with all variables as attributes.

## 3.3 File formats and naming conventions
### 3.3.1 File formats
.gpkg - Geopackage format containing spatial grid data with attribute table

### 3.3.2 Naming conventions
- files named lower case, spaces replaced with dashes (dash-case)
- Variable names use descriptive prefixes

# 4. DATA-SPECIFIC INFORMATION  
- Missing data code: NA
- Not Applicable: N/A

## 4.1 Enriching Biodiversity Metrics

**"fid"**
- Full name: Grid Cell Identifier
- Description: Unique identifier for each 500m hexagonal grid cell
- Type of variable: Integer
- Unit of measurement: ID number
  
### Variables in synthetic_MCDA_map.gpkg
Number of variables: 5

_Variable List:_

**"EB_vegetation_health_index_norm"** 
- Full name: Healthy Vegetation Density
- Description: The areas with the most active photosynthesis process have a better vegetation health condition for enriching biodiversity
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: NDVI --> Threshold > 0.2 --> Zonal Statistics --> Mean --> Normalization
- Source: Copernicus Sentinel 2

  **"EB_natural_landuse_density_norm"** 
- Full name: Natural Land Use Density
- Description: The natural land use along the streams provide legislative and administrative base for nature-based interventions and also indicates a more natural environment
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: Landuse Map--> Assigning All Green a Single Category > Join Attributes by field value--> Areas per grid assigned to each grid --> Normalization
- Source: OSM Data
  
   **"EB_species_richness_norm"** 
- Full name: Species Richness
- Description: The different types of natural land use indicate different degree of species richness which provides different condition for interventions aiming for enriching biodiversity, for example forests imply higher biodiversity and farmlands lower
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: Give biodiversity value --> add biodiversity values of overlapping shapes together --> Erase duplicate geometry --> use only higher biodiversity value --> Multiply max biodiversity value with the area --> Add Biodiversity values from same hex --> Normalization
- Source: OSM Data

   **"EB_industry_nuisance_norm"** 
- Full name: Nuisance from Industries
- Description: Industries in general cause nuisance (noise, pollution, odor, etc) which hinder biodiversity development
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: Landuse Map sorted only the industries --> Join Attributes by field value--> Amount of industries assigned per grid --> Normalization
- Source: OSM Data

   **"EB_road_nuisance_norm"** 
- Full name: Nuisance from Urban Barriers
- Description: Roads with a high maxspeed become dangerous urban barriers preventing animals from migrating and thus hindering the biodiversity
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: road data --> Threshold: maxspeed >= 40km/h --> Intersection --> Sum of length in each cell --> Normalization
- Source: OSM Data

4. Specialised formats or other abbreviations used: N/A

5. Total file size: 344 KB

## 4.2 Promote Climate Adaptation

**"fid"**
- Full name: Grid Cell Identifier
- Description: Unique identifier for each 500m hexagonal grid cell
- Type of variable: Integer
- Unit of measurement: ID number
  
### Variables in synthetic_MCDA_map.gpkg
Number of variables: 4

_Variable List:_

**"CA_flood_risk_norm"** 
- Full name: Risk of Flooding
- Description: There have been major floodings in Poznan during the last few years, and the areas with higher flooding risk are more in need of interventions that promote climate adaptations
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: flooding depth map --> subtract permenant waterbody --> Zonal Statistics --> Sum --> Normalization
- Source: EFAS

  **"CA_impermeability_norm"** 
- Full name: Density of Impermeable Surfaces
- Description: The areas with more amounts of impermeable surfaces are more vulnerable against flooding during future extreme rainfalls
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: Landcover --> Zonal Statistics --> Sum --> Normalization
- Source: ESA-Worldcover
  
   **"CA_heat_risk_norm"** 
- Full name: Heat Risk Index
- Description: The areas with more hot nights and more severe urban heat island effect (UHI) are more vulnerable towards future extreme climate, thus more in need of interventions promoting climate adaptation
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: 
- Source: 

   **"CA_river_sinuosity_norm"** 
- Full name: River Sinuosity
- Description: The higher sinuosity of a stream indicate that it is in a more natural form and helps to diverse flows and habitats, while the straighter streams need interventions that restore it into a more natural shape
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: 
- Source: OSM Data

4. Specialised formats or other abbreviations used: N/A

5. Total file size: 324 KB

## 4.3 Improve Quality of Life 

**"fid"**
- Full name: Grid Cell Identifier
- Description: Unique identifier for each 500m hexagonal grid cell
- Type of variable: Integer
- Unit of measurement: ID number

### Variables in synthetic_MCDA_map.gpkg
Number of variables: 6

_Variable List:_

**"LQ_resinumb_norm"** 
- Full name: Residents Number
- Description: The areas with larger numbers of residents see bigger possibility of an active urban life with community-oriented interventions carried out along the streams
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: 
- Source: WorldPop Hub

  **"LQ_urbandens_norm"** 
- Full name: Urbanized Land Use Density
- Description: The urbanized land use along the streams provide legislative and administrative base for community-oriented interventions
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: 
- Source: OSM Data
  
   **"LQ_peopattr_norm"** 
- Full name: People Attraction Density
- Description: If the area already contains some attractions for people, it has a good base to become a more active space in the future
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation:
- Source: OSM Data

   **"LQ_localcentr_norm"** 
- Full name: Local Centrality Index
- Description: This index is calculated through local integration analysis, which shows where the most vital local centers are and the areas with higher local centrality will be more suitable for community-oriented interventions
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: 
- Source: OSM Data

  **"LQ_pubtranaccess_norm"** 
- Full name: Public Transport Accessibility
- Description: The areas that are more accessible via public transport are more suitable for life-quality-improving interventions
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: 
- Source: OSM Data

   **"LQ_attrbetw_norm"** 
- Full name: Pedestrian Accessibility Index
- Description: The attraction betweenness analysis shows which roads are more frequently chosen leading to certain attractions (in this case streams), and the high value in this analysis indicates that the stream in those areas are more accessible for pedestrians, thus more suitable for community-oriented solutions
- Type of variable: Continuous (0-1 normalized)
- Unit of measurement: 0-1 (low to high)
- Calculation: 
- Source: OSM Data

4. Specialised formats or other abbreviations used: N/A

5. Total file size: 340 KB

## 4.4 Typology Analysis
### Additional Variables in synthetic_MCDA_map.gpkg
Number of derived variables: 1 

**"UHI_MAX_norm"** 
- Full name: Heat Risk 
- Description: Reflects exposure to urban heat islands and ecologica thermal stress
- Type of variable: Standardized
- Unit of measurement: -1.030 to 1.446 (low to high)
- Source: OSM Data

# 5. SHARING/ACCESS INFORMATION
## 5.1 Licenses/restrictions placed on the data:
CC BY-SA 4.0

## 5.2 Links to other resources:
To be updated upon publication

### 5.2.1 Links to publications that cite or use the data:
To be determined

### 5.2.2 Links to other publicly accessible locations of the data: 
N/A

### 5.2.3 Links/relationships to ancillary data sets: 
N/A

### 5.2.4 Links to publicly accessible scripts for analysis of the dataset:
- [Urban Stream Restoration: building a more resilient urban environmental system- Case of Poznań, Poland](files/synthetic_MCDA_map.gpkg)

### 5.2.5 Was data derived from another source?
Yes

## 5.3 Recommended citation for this dataset:
Naik, J., Hao, Y., Prikazchikov, S., & Yzaguirr, R. M. D. (2025). Urban stream restoration: Building a more resilient urban environmental system- case of Poznań, Poland. Delft University of Technology. 10.4121/6e37c82b-e9a6-4b97-8e2b-3c23bcff6fd8

This README.md file template was generated on 2022-04-19 by Claudiu Forgaci and Adele Therias according to the 4TU.ResearchData [Guidelines for creating a README file](https://data.4tu.nl/info/en/use/publish-cite/upload-your-data-in-our-data-repository) and the Cornell University template [Guide to writing "readme" style metadata](https://cornell.app.box.com/v/ReadmeTemplate) and is licensed under CC BY 4.0
