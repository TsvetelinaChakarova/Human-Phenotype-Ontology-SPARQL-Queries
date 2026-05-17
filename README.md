### Human-Phenotype-Ontology-SPARQL-Queries

This repository represents the university course project for "Knowledge Bases" course.

## Introduction

The project explores and queries the Human Phenotype Ontology v2025-05-06 - a standardized ontology describing human phenotypes in the context of diseases, used in medical research and bioinformatics to support diagnosis and disease analysis. The ontology contains 903004 RDF triples and is linked to external databases such as OMIM, Orphanet, and MONDO.

## Key Features
- Exploration of HPO's class hierarchies - Phenotypic abnormality, Mode of inheritance, Clinical course, Frequency, Clinical modifier
- Analysis of structural, relational and annotation properties
- 14 SPARQL queries demonstrating a wide range of techniques, including keyword search (single, AND, OR, combined logic), relevance scoring and match categorization via BIND/IF, set operations (union, intersection, difference) using FILTER EXISTS / FILTER NOT EXISTS, inference-aware querying (with and without reasoning enabled), searching by definition text and comments

## Ontology Source
[Human Phenotype Ontology](https://hpo.jax.org/data/ontology)

- ## Technologies
 ```
SPARQL
GraphDB
OWL
```
