# 🚀 Exploring the BioPax-Based Ontology with SPARQL Queries 🎶

## Overview
This repository contains a Jupyter Notebook for exploring a **BioPax-based ontology** using **SPARQL queries**. Whether you're interested in finding interactions between **SL_GENE** and **TSG_GENE**, discovering cross-references to external databases, or just diving into some fun ontology querying, this is a good starting point.

### What's Inside:
- A Jupyter Notebook with pre-defined SPARQL queries
- Examples based on BioPax ontology for exploring gene interactions, evidence, biological processes, and more
- Guidance on how to run these queries interactively and customize them for your own exploration

## 🔥 Getting Started

### Requirements:
To run this notebook, you'll need:

- **Python 3.11**  some of the Python libraries I've started to use have convinced me I need to embrace 3.11.  One of the more interesting libraries is trafilatura, which works well with foreign languages.

- The following libraries:
  ```bash
  pip install -r requirements.txt
  ```

### Loading the Ontology
The ontology is hosted on [GitHub](ontology\ontology.ttl). You can load the `.ttl` (Turtle) file directly into the notebook or use a local copy.

### How to Use This Repository:
1. Clone the repository:
   ```bash
   git clone https://github.com/donbr/gene-interactions-ontology.git
   cd gene-interactions-ontology
   ```

2. Open the Jupyter Notebook...

3. Run the SPARQL queries from the notebook to start exploring the ontology!
