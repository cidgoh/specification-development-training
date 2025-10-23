# Session 2 – Standardising Your Dataset
*From Dirty Data to Ontology-Aligned Schema*

## Purpose:
This session introduces participants to the practical process of cleaning messy contextual data and mapping it to ontology terms for use in data standards such as the PHA4GE SARS-CoV-2 specification.
Participants will work hands-on with a small dataset containing inconsistent field entries, learn to harmonize terminology, and align cleaned values with ontology identifiers using public look-up tools.

## Learning Objectives

By the end of this exercise, participants will be able to:

- Identify inconsistencies and ambiguities in real-world data.
- Harmonise and clean categorical field values for interoperability.
- Use ontology lookup services (EBI OLS, OntoBee) to source appropriate ontology terms.
- Apply curated ontology-aligned terms to a data schema.

## Folder Contents
| File                                        | Description                                                                                    |
| ------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **PHA4GECon_Standardise your dataset.xlsx** | Main exercise file containing the *dirty dataset*, *cleaning* and *curation* worksheets.       |
| **README.md**                               | This file. Overview and instructions for facilitators and participants.                        |

## Exercise Overview
### Part 1 – Prepare Terms for Curation

- Download the `Standardise your dataset.xlsx` from the repository.
- Open the *Original Data* tab in the Excel file.
- You will see a sumber of inconsistencies in the dataset. It is good practise to pull out all the unique values (this has been done for you)
- Got to *Part 1* tab and identify duplicates, typos, inconsistent capitalisation, and unclear values.
- Harmonise and record a clean, single label for each unique concept.

💡 See “Tips” box in instructions for guidance on grouping and conceptual thinking.

### Part 2 – Look Up Ontology Matches

- Use the EBI Ontology Lookup Service (OLS) to find ontology terms matching your cleaned labels.
- Record:
    - Ontology name (e.g. ENVO, OBI, UBERON)
    - Ontology ID (e.g. ENVO:00002272)
    - Definition (optional)

If no match exists, note “New term request needed.”

### Example Output
| Harmonized Label            | ID            | Definition     | Example Use        |
| --------------------------  | ------------- | ------------------ | ------------------ |
| Not Applicable | GENEPIO:0001619 | A categorical choice recorded when a measurable datum does not apply to a given context. | null value menu |


## Attribution

Adapted from FSCI 2022 – Introduction to Data Curation Using Ontologies by CIDGOH (CC-BY 4.0) Rhiannon Cameron. Modified for the PHA4GECon 2025 Workshop by the PHA4GE and CIDGOH teams.
