# Mechanistic Interpretability - Large Language Models (MILLM)

This repository contains data and application code to prepare, process and output a PhD experiment in mechanistic intepretability.

This repository is tailored to a specific set of inputs and ground-truth mappings (taken from the ontology matching task here: https://oaei.ontologymatching.org/2024/conference/index.html), but it can be amended to include any sources. The raw code is included here and there are no licence restrictions.


---

## 🚀 Explanation

1: Java executable millm-owlapi-1 is executed via the command line and takes a folder name which is the location of the raw ontology.owl files. The Java process takes each owl ontology, parses it using the OWLAPI library and extracts class relationships and properties, and generates a CSV file representing the structure and semantics of the ontology classes. The parameter 'level' can be supplied as either 's' or 'v' which guides the output to be a summary (s) or verbose (v). The default is 's' for a summary representation. The IntelliJ Java maven project code is included in the repository (/millm-owlapi-1).

2: Python script ....py is executed via the command line and takes a folder name which is the location of the groung truth mappings

3: Python script ....py is executed via the command line and 


---

## 🛠️ Usage

### Requirements

1: This experiment has been run successfully on Mac OS running Sequioa 15.3.2

2: Python 3.12.7

3: Java 

Any other configuration may work, but cannot be supported in advance.

### Steps

1: Clone this repository
