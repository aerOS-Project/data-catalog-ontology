# aerOS Data Catalog Ontology

Online documentation: https://w3id.org/aerOS/data-catalog

## Ontology overview

![Data Catalog Ontology Figures](diagrams/data-catalog-figures.svg)

## Ontology usage example

![Data Catalog Ontology Examples](diagrams/data-catalog-examples.svg)

## Local Development

### WIDOCO Documentation

To generate the documentation, issue the following command:

```bash
./generate-docs.sh
```

### JSON-LD @context

To generate the @context from the ontology we rely on the [owl2jsonld](https://github.com/stain/owl2jsonld) tool. Download the [JAR](https://github.com/stain/owl2jsonld/releases/tag/0.2.1) from the owl2jsonld repository and run the following command:

```bash
➜ java -jar owl2jsonld-0.2.1-standalone.jar -v -i -o ontology/context.jsonld file:///<full-local-path-to-data-catalog-ontology-repository>/ontology/data-catalog.owl
```
