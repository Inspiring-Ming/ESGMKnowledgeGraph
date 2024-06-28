# ESGMKG: ESG Metrics Knowledge Graph

[![DOI](https://www.mdpi.com/2771364)](https://www.mdpi.com/2771364)

## Overview

ESGMKG is a comprehensive database of ESG (Environmental, Social, and Governance) metrics, available in multiple semantic web formats. This repository includes the source code and data necessary to build the ESGMKG using Stardog.

### Files
The ESGMKG database is available in the following formats:
- **ESGMKG.json**: Contains the JSON version of the ESGMKG database.
- **ESGMKG.rdfxml**: Contains the RDF/XML version of the ESGMKG database.
- **ESGMKG.ttl**: Contains the Turtle (TTL) version of the ESGMKG database.


### Compressed Packages
The zip file included in this repository contains the entire source code for building the ESGMKG on Stardog. Note that the testing version represents an earlier iteration, while ESGMKG is the final version.
- **ESGMKG.zip**: The entire project package.
- **ESGMKG_Testing.zip**: A testing package for the project.

### SPARQL Query Files
These files are used for querying the ESGMKG database:
- **Q1ApplicableFramework.sparql**
- **Q2FrameworkAndCategory.sparql**
- **Q3CategoryAndMetric.sparql**
- **Q4Q6Q8Q10MetricAndCalculatingModel.sparql**
- **Q5MetricAndModel.sparql**
- **Q7Q9InputIndicatorAndModel.sparql**
- **Q11Datasource.sparql**

### Directories
- **QuerySolutionJson/**: This folder contains the JSON version of the query solutions. Query solutions are provided in JSON format based on the results of each query run against the ESGMKG.
- **Result/**: This folder contains the visualization results of the queries. The visualization results are based on 11 competency questions designed to evaluate the ESGMKG's capabilities.
- **SPARQL_Queries/**: This folder is intended to store the .sparql files used for querying the ESGMKG database.

### Documentation
- **README.md**: This file provides an introduction and overview of the repository.

This structure ensures that all necessary files for the ESGMKnowledgeGraph project are well-organized and easily accessible for users.


## How to Use

1. **Download the Repository:**
   Download the zip file containing the source code and data.

2. **Build ESGMKG on Stardog:**
   Follow the instructions in the provided documentation to build the ESGMKG using Stardog.

3. **Run Queries:**
   Use the provided query solutions in JSON format to test the ESGMKG.

## Citation

If you use ESGMKG in your research, please cite our paper:
[ESGMKG: Title of the Paper](https://www.mdpi.com/2771364)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact [https://www.linkedin.com/in/mingqin-yu-610a3419b/?originalSubdomain=au] at [mingqin.yu@unsw.edu.au].

