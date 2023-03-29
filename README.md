# Practica_Big_Data_grupo-3
School of tech, big data and cloud

## Repository estructure

In this repository there are 3 directory paths:

### GlueJobs
All the programmatic jobs of this project are develop for GlueJobs. Therefore, all the files are jupyter notebooks ready to import in GlueStudio.
There are 2 kind of jobs:
  - #### Analytics
      Used for the exploratory analysis in each stage of the data lake. This files are actually helpfull to find errors and the correct solutions for them, in order to choose
      the right decision in the etl proccess for that stage. 
        One for the raw stage
        Another one for the curated stage
  - #### ETL
    Used for the transformation needed in order to achieve a good dataset for the next step in the data lake stages. This files have the programmatic transformations and steps
    to reach out the final datamodel, required by the client. All the files are jupyter notebooks ready to import in GlueStudio.

### Datasets
It is not possible to connect Athena to powerBi cause of a lack of permisions. Therefore, we need to export the datasets ready to explote in the refined stage, and the athena views
with the kpi's requested by the client, in order to use it in powerBi. This directory have all the datasets required for this task.
