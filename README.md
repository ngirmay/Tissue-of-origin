Gene Expression Analysis Across Cancer Types
This report presents a series of visualizations that represent the analysis of gene expression data across various cancer types. The visualizations are intended to convey patterns, distributions, and relationships within the data, and to suggest possible future directions for this tissue of origin project.

Data Sourcing:

1. Source Paper - Li R, Liao B, Wang B, Dai C, Liang X, Tian G, Wu F. Identification of Tumor Tissue of Origin with RNA-Seq Data and Using Gradient Boosting Strategy. Biomed Res Int. 2021 Feb 17;2021:6653793. doi: 10.1155/2021/6653793. PMID: 33681364; PMCID: PMC7904362.

2. Data Source per Cancer Type - (https://dcc.icgc.org/releases/release_26/)
- under projects directory: gene expression files for cancer types used in paper cited above were downloaded locally
- example file: exp_seq.KIRP-US.tsv.gz

3. gene.txt file
- was generated using same 400 genes listed in paper


Main Takeaways:
Model Performance: High scores across most cancer types indicate good model performance. However, certain types such as READ show lower scores, suggesting room for improvement depending on cancer type. 
Balanced Metrics: The F1-score combines precision and recall, providing a balanced view of the model's performance.
*Overall goal was to replicate similar analysis and produce reproducible results*


Future Directions: 
Model Refinement: For cancer types with lower classification scores, additional features or alternative modeling techniques could be explored to improve performance.
Pathway Analysis: Integrating pathway information could give insights into the biological processes driving the observed expression patterns.
