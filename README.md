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
In this course, we explored urban stream restoration in Poznań, Poland, using two primary methodological approaches: Multi-Criteria Decision Analysis (MCDA) and Typology Construction. For each method, we identified relevant objectives and formulated research questions tailored to the respective analytical framework.
Additional details about the project can be accessed [here](https://...).

## 1.3 Author Information
A. Principal Investigators 
- Name: Stepan Prikazchikov, Roger Marin de Yzaguirre, Yaying Hao, Jaee Naik 
- Institution: TU Delft Faculty of Architecture & the Built Environment
- Address: Julianalaan 134, 2628 BZ Delft

## 1.4 Dates of data collection
- Survey : 2025-05-01

## 1.5 Geographic location of data collection
Delft, Netherlands

## 1.6 Keywords
Urban Stream Restoration, Urban rivers, River integration

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
Which areas which are most in need of intervention through integrated interventions that enhance biodiversity, support climate adaptation, and improve neighborhood quality of life?

### 2.1.2 Research questions (Typology Construction): 
Which locations both need and are ready for restoration interventions to maximize impact and feasibility?

### 2.1.3 Envisioned uses of the dataset
The dataset will serve as a decision support tool for future restoration and planning interventions along the river in Poznań by identifying priority zones where stream restoration solutions can have the greatest impact.

## 2.2 Methods for processing the data
**Deciding the Spatial Unit of Analysis: Why Hexagon Grid and What are the Parameters?**
For the spatial analysis, the study area was subdivided using a hexagonal grid, which served as the primary unit of analysis. The choice of hexagons was narrowed down by several methodological advantages. First, hexagonal cells maintain equal distance to all neighboring cells, which supports reduces directional bias in spatial calculations. Second, the use of hexagons helps to minimize edge effects that commonly arise in grid-based spatial analysis, thereby ensuring more consistent and accurate representation of spatial phenomena. 

The size of the hexagonal cells was determined through a balance between spatial resolution and computational feasibility. A diameter of 500 meters was selected, corresponding approximately to a 5–10 minute walking distance. This resolution also provides a reasonable number of spatial units across the city. 

**MCDA Methodology and Indicators-**
Multi-Criteria Decision Analysis (MCDA) is a subfield of operations research that systematically evaluates multiple, often conflicting, criteria in the decision-making process. The application of the MCDA methodology begins with the formulation of a primary goal. This overarching goal is then decomposed into specific objectives, each of which is translated into a research question. For each research question, a set of criteria is identified to assess various dimensions relevant to the objective. These criteria are subsequently assigned weights to reflect their relative importance in influencing the overall outcome.\

The evaluation culminates in the development of a synthetic map for each research question, which integrates the weighted criteria into a comprehensive spatial representation. These maps serve as analytical tools that encapsulate the combined perspectives of multiple stakeholders, thereby supporting informed and balanced decision-making.\

In the context of our study on urban stream restoration in Poznań, the principal objective is to enhance the resilience of the urban environmental system. In this study, resilience is conceptualized through three key dimensions: **Enhancing Biodiversity**, **Promoting Climate Adaptation** and **Improving Quality of Life**. Each of these dimensions is formulated as a distinct research question


## 2.3 Instrument- or software-specific information
QGIS was used to map and analyze spatial datasets
RStudio was employed to collate, visualize the report findings

# 3. FILE OVERVIEW
No

## 3.1 File List

### 3.1.1 Data category A
- "filename.extension": brief description of file

### 3.1.2 Data category B
- "filename.extension": brief description of file


## 3.2 Relationship between files:
The following tables (csv files) employ a foreign key to refer to the primary key (unique identifier) in one or more other table(s):

"filename.extension"
- abc used as foreign key to "otherfile.extension"

## 3.3 File formats and naming conventions
### 3.3.1 File formats
- extension - type of data

### 3.3.2 Naming conventions
- files named lower case, spaces replaced with dashes (dash-case)
- in tabular data, variable names snake case

# 4. DATA-SPECIFIC INFORMATION

- Missing data code: NA
- Not Applicable: N/A

## 4.1 Data Category A

### 4.1.1 filename.extension
1. Number of variables: 

2. Number of cases/rows: 

3. Variable List:

"variable_name"
- Full name: 
- Description: 
- Type of variable: 
- Unit of measurement:
- Number of missing values: 

4. Specialised formats or other abbreviations used: 

5. Total file size: 

## 4.2 Data Category B
...

## 4.3 Data Category C
...

## 4.4 Data Category D
...

# 5. SHARING/ACCESS INFORMATION
## 5.1 Licenses/restrictions placed on the data:
...

## 5.2 Links to other resources:

### 5.2.1 Links to publications that cite or use the data:
...

### 5.2.2 Links to other publicly accessible locations of the data: 
...

### 5.2.3 Links/relationships to ancillary data sets: 
...

### 5.2.4 Links to publicly accessible scripts for analysis of the dataset:
- [Link title](link url)

### 5.2.5 Was data derived from another source?
Yes/No

## 5.3 Recommended citation for this dataset:
...

This README.md file template was generated on 2022-04-19 by Claudiu Forgaci and Adele Therias according to the 4TU.ResearchData [Guidelines for creating a README file](https://data.4tu.nl/info/en/use/publish-cite/upload-your-data-in-our-data-repository) and the Cornell University template [Guide to writing "readme" style metadata](https://cornell.app.box.com/v/ReadmeTemplate) and is licensed under CC BY 4.0
