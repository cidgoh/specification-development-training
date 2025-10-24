# Session 3 – Implementation
*Operationalising your schema in useful tooling*

## Purpose:
This session introduces the concepts of opeationalising your specification in tooling, encouraging meaningful use and community uptake. It demonstrates how a well-defined schema can be used to curate, v alidate and export standardised contextual data, while collecting user feedback for continuous improvement.

An example of a tool that uses PHA4GE standards is the [DataHarmonizer](https://github.com/cidgoh/pathogen-genomics-package). The DataHarmonizer is a spreadsheet based web application that includes validation templates for SARS-CoV-2 and Monkeypox sample contextual data, as well as draft Influenza and Wastewater specifications. Existing specification packages can be easily accessed and downloaded at the pathogen-genomics-package repository https://github.com/cidgoh/pathogen-genomics-package. For those interested in operationalsing their own templates in the DataHarmonizer can visit https://github.com/cidgoh/DataHarmonizer/

## Learning objectives
In this final sessions we put a schema into practice within the DataaHaronizer. By the end of this exercise, participants will be able to:

- Understand how schema definitions are expressed as fields and validation rules.
- Use and curate data in the DataHarmonizer
- Develop the materials required for testing.
- Recognize the importance of feedback in iterative standard improvement. 

## Folder Structure
|File|Details|
|------|------------|
|**PHA4GECon_Data-curation-in-DH.pdf**|Data curation exercise using the DatatHarmonizer
|**PHA4GECon DH Getting Started - Installation.mp4**|Video for installing the DataHarmonizer|
|**Testing and Validation**|*Subfolder* including an example testing package for the PHA4GE wastewater specification|
|**SOPs**|*Subfolder* including example SOPs from the PHA4GE wastewater specification|

## Exercise Overview
To practice entering and validating standardized contextual data using the PHA4GE SARS-CoV-2 template in DataHarmonizer, and to explore how validation rules and ontology picklists support data quality.

1. Download the existing DataHarmonizer package at https://github.com/cidgoh/DataHarmonizer/
2. From the template menu select PHA4GE
3. Start curating!

**Tip:** Watch the ![video](https://github.com/cidgoh/specification-development-training/blob/main/training/workshop/PHA4GECon-2025/3_implementation/PHA4GECon%20DH%20Getting%20Started%20-%20Installation%20(1).mp4) on setting up the DataHarmonizer

### Scenario
*The BCCDC Public Health Laboratory obtained a nasopharyngeal swab for diagnostic testing (sample ID Bc-12345-ab) on March 1 2023 from a symptomatic, 44 year old female that had been hospitalized in the ICU. The individual had been exhibiting a cough, fever, muscle weakness, as well as other symptoms of Acute Respiratory Distress Syndrome.
The individual recently travelled to the United States on holiday and returned on Feb 19 2023. The sample was flagged for sequencing as part of the lab’s International travel surveillance program. The sample was sequenced on March 7 2023 using an Illumina MiSeq instrument. The raw data was processed using ncov-tools 2.3.1 as part of their bioinformatics protocol (https://github.com/jts/ncov2019-artic-nf/blob/master/README.md) and dehosted using BWA (version 0.7.17). The consensus sequence was generated using iVar 2.3.1. The sequence was uploaded to GISAID and assigned the accession number EPI_ISL_436489. Drs Tejinder Singh, Fei Hu and Joe Blogs helped to generate the sequence.*

### Populate the template
- Use dropdowns and tooltips in each section to fill out the appropriate fields.
- To focus on the required and recommended fields go to `Settings` -> `Required and recommended columns`

**Tip**: Read the field definitions carefully. Hover over a field name in the DH to understand what information belongs there.


### Validate your record
- Click Validate in the toolbar and then check any error messages in the Validation Panel.
- Errors will be highlighted, and you can navigate through the errors by selecting `Next error`
- Correct any missing required fields or format errors.
- Once you have corrected the errors, select validate again.
