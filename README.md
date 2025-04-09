# Mechanistic Interpretability - Large Language Models (MILLM)

This repository contains data and application code to prepare, process and output a PhD experiment in mechanistic intepretability.

This repository is tailored to a specific set of inputs and ground-truth mappings (taken from the ontology matching task here: https://oaei.ontologymatching.org/2024/conference/index.html), but it can be amended to include any sources. The raw code is included here and there are no licence restrictions.


---

## 🚀 Explanation

1: Java executable millm-owlapi-2 is executed via the command line and takes a folder name which is the location of the raw ontology.owl files. The Java process takes each owl ontology, parses it using the OWLAPI library and extracts class relationships and properties, and generates a CSV file representing the structure and semantics of the ontology classes. The parameter 'level' can be supplied as either 'summary' or 'verbose' which guides the output to be more verbose or not. The default is 'summary'.

2: Python script ....py is executed via the command line and takes a folder name which is the location of the groung truth mappings

3: Python script ....py is executed via the command line and 


---

## 🛠️ Usage

### Requirements

1: Python / Java

### Steps

1: Clone this repository
