# UE 803: Data Science Project 2024

## Overview

The goal of this project is to collect and analyze biographies from Wikipedia for two categories of individuals: sculptors and computer scientists. This data science project involves extracting Wikipedia biographies and associated knowledge graph facts, performing statistical analysis and visualizations, and training clustering models to automatically segment the data. Additionally, we compare the performance of two linguistic processing libraries, Stanza and Spacy, on named entity recognition tasks using the collected biographies and verify the results against the knowledge graph data.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
  - [Data Collection](#data-collection)
  - [Data Analysis](#data-analysis)
  - [Clustering](#clustering)
    -[Model Training](#model-training)
    -[Model Evaluation](#model-evaluation)
  - [Linguistic Processing Comparison](#linguistic-processing-comparison)
    - [Named Entity Recognition (NER)](#named-entity-recognition-ner)
    - [Named Entity Recognition: Analysis by Entity Type](#named-entity-recognition-analysis-by-entity-type)
    - [NER Verification Against Knowledge Graph](#named-entity-recognition-verification-against-knowledge-graph)
- [Contributing](#contributing)
- [License](#license)
     

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn
- stanza
- spacy
- numpy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Hawawou/UE-803.git
   cd UE-803
   
## Data Collection
We collected biographies from Wikipedia and extracted associated knowledge graph facts for sculptors and computer scientists. 
## Data Analysis
   Using the collected data, we performed detailed analyses to uncover patterns and differences between the two categories of text. Various visualizations such 
   histograms,boxplots,wordclouds ,RDF properties,Tokens,sentences and Facts were created to illustrate these findings, helping to provide insights into the characteristics and 
   distinctions of sculptors and computer scientists.

## Clustering

**Model Training:**Training various clustering algorithms such as K-Means on the prepared data.

**Model Evaluation:**Testing the trained models to evaluate their performance using metrics like silhouette score,We also visualized the clusters to understand their composition and characteristics.

## Linguistic Comparison
**Named Entity Recognition (NER)**:Compare the performance of Stanza and Spacy on NER tasks.

**Named Entity Recognition Analysis by Entity Type**:Analyze the results between Stanza and Spacy on the types of entities recognized.

**NER Verification Against Knowledge Graph**:Compare the named entities recognized by Stanza and Spacy with the entities in the knowledge graph.  
## Contributing
   If you would like to contribute, please fork the repository and use a feature branch.Pull requests are welcome.
## License
  This project is licensed under the GNU General Public License v3.0 License. See the LICENSE file for details.
