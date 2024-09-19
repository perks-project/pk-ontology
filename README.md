# Template repository for an ontology

Repository for My Ontology.

| Prefix    | IRI |
| -- | ------- |
| my-prefix:  | [https://knowledge.c-innovationhub.com/my-ontology#](https://knowledge.c-innovationhub.com/my-ontology#)  |

## How to

Create a repository starting from this template repository. Rename the folders and the repository accordingly to the identifier of the ontology. The new repository name should be used to replace `my-ontology` in all the places.

1. The RDF files describing the controlled vocabularies can be defined manually or by modifying the [my-ontology.owl](.my-ontology/my-ontology.owl) file.

2. Download the Widoco tool as discussed below and put the JAR in the `tools` folder to automatise its execution through the `run-onto.sh` script. A Java installation is required.

### `widoco`: RDF to HTML
Download release JAR from [here](https://github.com/dgarijo/Widoco/releases) and rename it as `widoco.jar`. Documentation for the CLI tool is available [here](https://github.com/dgarijo/Widoco#how-to-use-widoco). The `run-onto.sh` script was tested with version `1.4.21`.

3. Execute the `sh run-onto.sh my-ontology x.y.z` script providing as argument the correct version number.

4. Edit the documentation in the [sections](.my-ontology/sections) folder

5. Git commit and push

6. Enable GitHub Pages to host the ontology

7. Configure a webserver by using the provided [.htaccess](.my-ontology/.htaccess) file.


