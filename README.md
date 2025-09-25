# Gene Expression Analysis with DEGs, Significant DEGs, and Functional Enrichment Analysis

🧬 End-to-End Gene Expression Analysis

This repository provides a complete pipeline for gene expression analysis, covering everything from preprocessing to Differentially Expressed Genes (DEGs) identification, filtering significant DEGs, and performing functional enrichment analysis.

The workflow is designed for reproducibility and can be applied to both RNA-seq and microarray datasets.

🚀 Features

✅ Data preprocessing & normalization

✅ Identification of Differentially Expressed Genes (DEGs)

✅ Filtering Significant DEGs using thresholds (e.g., p-value, adj p-value, log2FC)

✅ Functional enrichment analysis (GO, KEGG, Reactome, etc.)

✅ Publication-ready plots and tables

📂 Workflow Overview

Data Input & Preprocessing

Load gene expression data (counts/microarray)

Normalize expression values

Differential Expression Analysis

Filter Significant DEGs

Adjusted p-value (FDR) threshold

Log2 fold-change cutoff

Functional Enrichment Analysis

Gene Ontology (GO) enrichment

KEGG pathway analysis

Reactome analysis

Visualization

Volcano plots

Heatmaps

Pathway enrichment plots



<img width="3600" height="2400" alt="enrichment_bubbleplot_all" src="https://github.com/user-attachments/assets/10376f35-bde9-428d-99d7-edfb9d56f77d" />



<img width="3000" height="1800" alt="enrichment_barplot_KEGG_2021_Human" src="https://github.com/user-attachments/assets/78b9f5c9-4dab-475f-9f9e-e260e576a879" />



<img width="3000" height="1800" alt="enrichment_barplot_GO_Cellular_Component_2021" src="https://github.com/user-attachments/assets/0d94683d-eb1a-4130-b8e8-203464dc9c83" />


<img width="3000" height="1800" alt="enrichment_barplot_Reactome_2022" src="https://github.com/user-attachments/assets/f7e9f271-cc2a-4377-9b4c-96c7fba4fbdb" />






📈 Output

Tables

DEGs.csv: All DEGs with statistics

Significant_DEGs.csv: Filtered list based on cutoffs

Enrichment_results.csv: Functional enrichment results

Plots

Volcano_plot.png

Heatmap.png

GO_KEGG_Reactome_plots.png


🤝 Contributing

Contributions are welcome! Please fork this repo, create a branch, and submit a pull request.

📜 License

This project is licensed under the MIT License.

Follow like, share, and subscribe https://www.youtube.com/@Bioinformatics_Made_Easy
