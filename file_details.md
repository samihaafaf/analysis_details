### Data Used

- GSE156869 - ACM (3 samples), non-ACM (5 samples)
- GSE141910 - Brain Dead, referred as the BD samples  (30 samples taken from 162 samples)

### File Descriptions

| File Name                               |                         Description                          |
| :-------------------------------------- | :----------------------------------------------------------: |
| data_clusters.png                       | shows the clustering trends of the ACM (3 samples), <br />non-ACM (5 samples) and the 30 brain dead (referred as BD) samples, based on number of reads mapped to each gene in the human genome. |
| PCA_plot                                | shows the PCA plots for ACM, non-ACM (stated as none) and brain dead samples. This shows that for some linear combinations of our variables (i.e the genes) our data can be split into different clusters. This visualisation shows that the ACM and non-ACM data are more similar to eachother, than the brain dead samples, thus these two groups separate in the PCA plot. |
| ACM_BD_avg_gene_expression_plot.png     | average gene expression (in log2 counts per million (cpm)) for all genes for BD and ACM samples |
| ACM_non-ACM_avg_gene_expressions.png    | average gene expression (in log2 counts per million (cpm)) for all genes for BD and non-ACM samples |
| volcano_plot.png                        | the logFC (log fold change) expressions for genes for ACM vs BD samples. Positive fold change means the genes are more expressed in ACM, negative fold change means genes more expressed in BD samples. |
| ACMvsBD_diffEx_genes.html               | List of differentially genes between ACM and BD samples (having p-value = 0.01, and minimun logFC = 2) |
| top_20_upregulated_genes_inBD.html      | list of top 20 upregulated genes in BD samples compared to ACM. |
| top_20_upregulated_genes_in_ACM.html    | list of top 20 upregulated genes in ACM samples compared to BD. |
| heatmap_ACM_vs_BD.png                   | heatmap of all the differentially expressed genes in the ACM vs BD samples |
| KEGG_competitive_pathways_all21.png     | BUBBLE GRAPH FOR - KEGG Pathway enrichment for ACM and BD samples using a competitive approach. ACM only has upregulated genes for the 'KEGG_MEDICUS_REFERENCE_MAGI_PTEN_SIGNALING_PATHWAY' pathway. |
| KEGG_pathway_competitive_ACM_all21.html | INTERACTIVE TABLE FOR - KEGG Pathway enrichment for ACM and BD samples using a competitive approach. ACM only has upregulated genes for the 'KEGG_MEDICUS_REFERENCE_MAGI_PTEN_SIGNALING_PATHWAY' pathway. Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| KEGG_all23_enrichedPath.png             | BUBBLE GRAPH FOR - all 23 KEGG enriched pathway for ACM and BD samples using a self-contained approach. (NES means - normalised enrichment score) |
| KEGG_pathways_for_ACM_BD.html           | INTERACTIVE TABLE FOR - all 23 KEGG enriched pathway for ACM and BD samples using a self-contained approach. Positive NES means enriched in ACM, negative NES means enriched in BD. |
| GOCC_top20_enrichedPath.png             | BUBBLE GRAPH FOR - top 20 GO:CC enriched pathway for ACM and BD samples using a self-contained approach. (NES means - normalised enrichment score) |
| GOCC_pathways_for_ACM_BD.html           | INTERACTIVE TABLE FOR - all GO:CC enriched pathways for ACM and BD samples using a self-contained approach. Positive NES means enriched in ACM, negative NES means enriched in BD. |
| GOCC_competitive_pathways_top25.png     | BUBBLE GRAPH FOR - top 25  enriched pathway for ACM and BD samples using a competitive GSEA approach. |
| GOCC_pathway_competitive_ACM.html       | INTERACTIVE TABLE FOR - all GO:CC enriched pathway for ACM and BD samples using a competitive GSEA approach. Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples. |
| GOBP_top20_enrichedPath.png             | BUBBLE GRAPH FOR - top 20 GO:BP enriched pathway for ACM and BD samples using a self-contained approach. (NES means - normalised enrichment score) |
| GOBP_pathways_for_ACM_BD.html           | INTERACTIVE TABLE FOR - all GO:BP enriched pathways for ACM and BD samples using a self-contained approach. Positive NES means enriched in ACM, negative NES means enriched in BD |
| GOBP_competitive_pathways_all11.png     | BUBBLE GRAPH FOR - all enriched pathway for ACM and BD samples using a competitive GSEA approach |
| GOBP_pathway_competitive_ACM.html       | INTERACTIVE TABLE FOR - all GO:BP enriched pathway for ACM and BD samples using a competitive GSEA approach. Direction 'Up' means upregulated in ACM and direction 'Down' means upregulated in BD samples |

