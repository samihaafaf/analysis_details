### Data Used

- GSE156869 - ACM (3 samples)
- GSE141910 - Brain Dead, referred as the BD samples  (142 samples taken from 162 samples)

### File Descriptions

| File Name                     |                         Description                          |
| :---------------------------- | :----------------------------------------------------------: |
|                               |                              .                               |
| avg_gene_ex.html              | an interactive plot which shows the average gene expression in the ACM and BD samples. Hover over the points to view the gene name and average expression values. |
| acm-vs-bd-df-gene-by-sig.html | List of differentially genes between ACM and BD samples (having p-value = 0.01, and minimun logFC = 1.5) |
| heatmap_of_subsamples.png     | heatmap of all the differentially expressed genes in ACM (3 samples) vs BD ( 12 samples). Plotting all 142 BD samples in heatmap is difficult for visualization, thus 12 arbitrary samples are taken for plotting. |
| table1.png                    | list of top 20 downregulated genes in ACM samples compared to BD. |
| table2.png                    | list of top 20 upregulated genes in ACM samples compared to BD. |
| pca-plot.png                  | shows the PCA plot for ACM, non-ACM (stated as control) and brain dead samples. This shows that for some linear combinations of our variables (i.e the genes) our data can be split into different clusters. This visualisation shows that the ACM and non-ACM data are more similar to eachother, than the brain dead samples, thus these two groups separate in the PCA plot. |
| module_sizes.png              | A plot showing the proportion of the total differentially expressed genes that account for ACM and BD. |
| volcano-plot.png              | the logFC (log fold change) expressions for genes for ACM vs BD samples. Positive fold change means the genes are more expressed in ACM, negative fold change means genes more expressed in BD samples. |
| GO_BP_pathways.html           | Enriched BP pathways using clusterProfiler (uses ranked gene list)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| GO_CC_pathways.html           | Enriched CC pathways using clusterProfiler (uses ranked gene list)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| GO_MF_pathways.html           | Enriched MF pathways using clusterProfiler (uses ranked gene list)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| KEGG_pathways.html            | Enriched KEGG pathways using clusterProfiler (uses ranked gene list)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| GO_CC_camera.html             | Enriched CC pathways using CAMERA (uses expression matrix)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| GO_MF_camera.html             | Enriched MF pathways using CAMERA (uses expression matrix)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| GO_BP_camera.html             | Enriched BP pathways using CAMERA (uses expression matrix)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| KEGG_camera.html              | Enriched KEGG pathways using CAMERA (uses expression matrix)<br />Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| upreg_ACM_paths.html          | The bubble chart shows enriched pathways in ACM samples for various common pathway collections. The y-axis shows significance of the enrichment, higher points are more significant. (Hover over each point to see pathway names) |
| upreg_BD_paths.html           | The bubble chart shows enriched pathways in BD samples for various common pathway collections. The y-axis shows significance of the enrichment, higher points are more significant. (Hover over each point to see pathway names) |