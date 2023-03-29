# Practica_Big_Data_grupo-3
School of tech, big data and cloud

## Repository estructure

In this repository there are 3 directory paths:

### GlueJobs
All the programmatic jobs of this project are developed for GlueJobs. Therefore, all the files are Jupyter notebooks ready to import in GlueStudio. There are 2 kinds of jobs:

  #### Analytics
   Used for the exploratory analysis in each stage of the data lake. These files are actually helpful to find errors and the correct solutions for them in order to          choose the right decision in the ETL process for that stage. One for the raw stage and another one for the curated stage.
  #### ETL
   Used for the transformation needed to achieve a good dataset for the next step in the data lake stages. These files have the programmatic transformations and steps to    reach the final data model required by the client. All the files are Jupyter notebooks ready to import in GlueStudio.
  #### Datasets
   It is not possible to connect Athena to Power BI due to a lack of permissions. Therefore, we need to export the datasets ready to exploit in the refining stage and      the Athena views with the KPIs requested by the client to use them in Power BI. This directory has all the datasets required for this task.
