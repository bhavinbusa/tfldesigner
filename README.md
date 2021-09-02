# tfldesigner
Open-source tool to design tables, figures, and listings (TFL) and generate associated metadata to support clinical trial data analysis and reporting.

# Introduction and Problem Statement: 
The industry spends countless number of hours manually designing TFL shells and to write analysis datasets specification. And once they are made available, the programmer writes the SAS code to generate the analysis datasets and TFLs. And in most companies, the generation of analysis deliverables is very manual (sometimes with macros or re-using code). CDISC 360 proof of concept (POC) project demonstrated end-to-end automation of study specification, data processing and analysis using a metadata-driven approach.  As a result, CDISC is working on adding a conceptual layer to the analysis standards (e.g., CDISC Analysis Results Standards) and are developing a Safety User Guide. There is a need of a tool that can leverage available CDISC analysis results standards/templates and accelerate generation of the TFL shells and support metadata-driven automation in development of ADaM and TFLs. 

# Solution:
Build an open-source TFL designer that can ingest available standards/templates from the CDISC library to design study-specific analysis output display (TFL shell) and in parallel generate machine-readable metadata that will facilitate generation of analysis dataset as well as the output of interest (TFL). Industry wide collaboration is required to develop a tool that is widely accepted and used by the stakeholders. This project will help build up the community to work on a solution that works for all without disrupting the current workflows. 

