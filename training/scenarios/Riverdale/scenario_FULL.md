# Full scenario

## Phase 1 : Outbreak - A mysterious illness in Riverdale

&#x1F4CD; *February 28, 2025 - Riverdale General Hospital, Newlandia*

Doctors at Riverdale General Hospital report a cluster of patients presenting with flu-like symptoms and an unusual temporary purple discoloration of the skin. This illness, nicknamed "Purple Fever," does not match any known diseases.

Public health officials from Newlandia Center for Disease Control (NCDC) step in to investigate. Blood and nasopharyngeal swabs are collected from five hospitalized patients, but PCR panels for known respiratory viruses return negative results.

With no obvious pathogen detected, the clinical and epidemiological teams raise concerns that this could be a novel infectious agent. They notify the Ministry of Health, and discussions begin about environmental surveillance to track potential sources.

**Discussion Prompts**

- What type of contextual data should be captured when a pathogen is unknown? How should this be structured?
- Are there existing data specifications for similar pathogens that could be used as a starting point?
- From the information provided, what fields are essential for tracking this potential outbreak?
- How can we ensure interoperability of clinical and epidemiological data?

**Task**

After discussing the points above, decide what are the minimum required and recommended fields to capture data for this mysterious outbreak. Consider using existing resources as a guide.

Pick two fields and use EBI OLS to look up appropriate enums for this.


## Phase 2: Environmental Surveillance – A Lead in the Sewers

&#x1F4CD; *March 5, 2025 – Riverdale, Newlandia*

Following the hospital outbreak, epidemiologists suggest environmental monitoring as there has been speculation that other individuals in the community, not just those in the hospital, may be affected by Purple Fever.

A technician collects a wastewater sample (Sample ID: NEW-GR-0054) from the hospital sewage system and submits it for metagenomic sequencing at the Newlandia Genomics Institute (NGI).

At this stage, no specific pathogen is suspected, so broad sequencing is performed.

**Discussion Prompts**

- What are the advantages of environmental surveillance for outbreak response?
- What other contextual data fields are required to adequately monitor environmental samples?
- How can we ensure traceability, considering information that has yet to be known?
- How do we balance specificity vs. broad screening in sequencing?

**Task**

After discussing the points above, decide which additional fields may be required in environmental surveillance. Consider the 'Bioinformatics and QC metrics', 'Taxonomic information' and 'Lineage and Clade information' in existing specifications.


## Phase 3: The Breakthrough – Identification of **Griffithsi E**

&#x1F4CD; *March 12, 2025 – Newlandia Genomics Institute*

After analyzing the wastewater sample, bioinformaticians at NGI detect a novel RNA virus that shares 97% similarity with an unclassified viral genome. The pathogen is tentatively named Griffithsi E and is strongly correlated with areas experiencing Purple Fever outbreaks.

The Ministry of Health is immediately notified, and researchers pivot to:

1. Confirming its presence in more wastewater samples from different regions.
2. Developing a targeted PCR test for rapid detection.
3. Investigating possible animal reservoirs.

**Discussion Prompts**

How does data structure evolve as new findings emerge?

What new metadata fields become important once a pathogen is identified?

How can surveillance data inform outbreak response?
