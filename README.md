# AI_and_Drug_Discovery_Course_2026

## Assignment Title
Assignment_2_QSAR_data_curation.ipynb

## Selected Target
TP53

## Number of Bioactivity Records
138 compounds (after data curation and preprocessing)

## Data Curation Workflow
Bioactivity data for the TP53 target was retrieved from the ChEMBL database using Google Colab. The dataset was filtered to include only IC50 values, and entries with missing data were removed.

Key features such as molecule ID, SMILES, and IC50 values were extracted. Compounds were classified into active, intermediate, and inactive groups. Invalid or missing SMILES entries were removed, and the final curated dataset was saved for QSAR modeling.
