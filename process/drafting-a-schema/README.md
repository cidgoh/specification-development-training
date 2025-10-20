# Drafting a Schema

**Goal:**  
Translate the insights gathered during the *Needs Assessment* stage into a structured, ontology-based schema that defines fields, picklists, and their relationships.  
This stage produces three key outputs:
1. A **field and term reference guide** describing the schema components.  
2. An **ontology-aligned schema file** (e.g., `.xlsx`, `.csv`, or `.yaml`).  
3. A **LinkML model** for use in validation and interoperability tooling.

---

## Overview

Across public health and research, data is often collected in diverse formats, reflecting different study designs and operational systems.  
A well-designed schema harmonizes these differences by defining shared field structures and controlled terms that promote **consistency**, **interoperability**, and **machine-readability**.

Ontologies provide the foundation for this process. They define concepts (classes) and relationships in a formal, computable way.  
Using trusted community resources such as the **OBO Foundry** ensures that the specification aligns with established standards and can integrate with other systems.

---

## Key Activities

1. **Translate needs into fields**  
   - Review the key data elements identified in the Needs Assessment.  
   - Define fields with clear labels, plain-language definitions, and data types.  
   - Identify whether each field is *required*, *recommended*, or *optional*.

2. **Integrate ontologies**  
   - Use [EBI Ontology Lookup Service (OLS)](https://www.ebi.ac.uk/ols/index) to source existing ontology terms for field names and picklist values.  
   - Record the **label**, **definition**, and **Internationalized Resource Identifier (IRI)** for each mapped term.  
   - Group related fields into **modules** (e.g., Sample Collection, Sequencing, Quality Control) to support extensibility.  
   - If no suitable term exists, note this for later submission via the ontology term request process.

3. **Draft a structured schema file**  
   - Capture fields, definitions, and term mappings in a structured format (e.g., Excel or CSV).  
   - Include columns for:  
     `field_name`, `definition`, `data_type`, `required_status`, `ontology_label`, `ontology
---

## Good Practice

- Use **unique, unambiguous labels** for fields and values.  
- Provide **Aristotelian-style definitions**: “An A is a B that C.”  
- Prefer existing ontology classes; create new ones only if necessary.  
- Group fields into **thematic modules** to enable adaptation across domains.  
- Capture **provenance and versioning** for each schema iteration.  

---

**Next Stage → Implementation**   
Use the drafted schema to develop tooling integrations (e.g., DataHarmonizer, LinkML validation, and export scripts) and plan adoption workflows.