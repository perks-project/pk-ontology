# Procedural Knowledge Ontology (PKO)

Repository for the Procedural Knowledge Ontology (PKO) 

| Prefix    | IRI |
| -- | ------- |
| pko:  | [https://w3id.org/pko#](https://w3id.org/pko#)  |

## Ontology purpose and scope

Procedural Knowledge (PK) is knowing how to perform some tasks, as opposed to descriptive/declarative knowledge, which is knowing what in terms of facts and notions. 
In industry, PK refers in general to structured processes to be followed, and can be related to both production (e.g., procedure on the production line in a plant) and services (e.g., procedure for troubleshooting during customer support); to specific technical expertise (e.g., procedure to set up a specific machine) and general regulations and best practices (e.g., safety procedures, activities to minimise environmental impact).

The Procedural Knowledge Ontology (PKO) is defined to support the holistic governance of industrial procedural knowledge in its entire life cycle, from elicitation to management, from access to exploitation of explicit PK. An overview of the concepts covered by the ontology is represented in the following figure.

<p align="left"><img src="requirements/conceptual-model-v0.png" alt="Conceptual Model v0" width="800"></p>

## Content of the repository

The resources associated with the requirements specification are available in the [`requirements`](./requirements) folder. A draft version of the requirements is currently available in the folder.

The RDF files describing the ontology can be found in the ontology folder [pko.owl](.pko/pko.owl) file. The OWL file is associated with the corresponding [Chowlk](https://chowlk.linkeddata.es/) diagram.

The Widoco tool is used to automatise the ontology publication through the `run-onto.sh` script as described in the template repo https://github.com/cefriel/ontology-template.
