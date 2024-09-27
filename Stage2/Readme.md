## Visualization, Differential Gene Expression Analysis and Functional Enrichment Analysis of Glioblastoma dataset (Stage 2 Task)

The analysis is performed on a count dataset of glioblastoma transcriptomic samples(https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/Cancer2024/glioblastoma.csv). This dataset consists of 5 samples from patients with Recurrent Tumor and 5 from patients with Primary Tumor.

## Contents
- **[Visualizations](./Visualizations/)**: Visualizations of the gene expression data, including heatmaps and other relevant figures.
- **[GBM_dataset](./GBM_dataset/)**: Dataset used for analysis.
- **[Report](./Report.md)**: Detailed report of the analysis.
- **[Code](./Code/)**: Code for the entire analysis, starting from data preprocessing to functional enrichment Analysis
  

## Analysis tools :
R studio 4.4.0

ShinyGO http://bioinformatics.sdstate.edu/go/


## Project Workflow :

1. Generating 3 heatmaps [1] for genes only ,[2] for samples only ,[3] for both genes and samples.

2. Generating 2 heatmaps of the entire dataset using diverging and sequential color palettes.
 
3. Subsetting significantly upregulated and downregulated genes based on p-value and foldchange cutoffs.
   
4. Functional enrichment analysis using ShinyGO: http://bioinformatics.sdstate.edu/go/

5. Generation of a lollipop plot showing the top 5 enriched pathways in the dataset

6. Interpreting the top 3 enriched pathways in biological processes.


## Contributors
|Name|Slack ID|Linkedin|
| ----------- |----------- |----------- |
|Ayooluwa Joseph|@Jay1079| <a href="https://www.linkedin.com/in/ayooluwa-joseph/" target="_blank">	LinkedIn Profile</a> |
|Edikan Umoh|@usiwomaumoh| <a href="https://www.linkedin.com/in/edikan-umoh/" target="_blank">	LinkedIn Profile</a>|
|Lewis Karani|@Karani|<a href="https://www.linkedin.com/in/lewis-karani/" target="_blank">	LinkedIn Profile</a>|
|Nishat Tamanna|@Nishat| <a href="https://www.linkedin.com/in/nishat-tamanna-45863117a/" target="_blank">	LinkedIn Profile</a>|
|Shalaka More|@shalaka| <a href="https://www.linkedin.com/in/shalaka-more-03277913b/" target="_blank">	LinkedIn Profile</a>  |
|Sreeja Mondal|@sreeja| <a href="https://linkedin.com/in/sreejamondal263/" target="_blank">	LinkedIn Profile</a> |





