# Sexually concordant and dimorphic transcriptional responses to maternal trichloroethylene and/or N-acetyl cysteine exposure in Wistar rat placental tissue

## Citation Information
Elkin ER, Su AL, Dou JF, Colacino JA, Bridges D, Padmanabhan V, Harris SM, Boldenow E, Loch-Caruso R, Bakulski KM. 2023. Sexually-concordant and dimorphic transcriptional responses to maternal trichloroethylene and/or n-acetyl cysteine exposure in Wistar rat placental tissue. Toxicology. PMID: 36396003, PMCID: pending. DOI: 10.1016/j.tox.2022.153371

This Github repository contains the data management and analytic scripts to produce the following manuscript: [Sexually concordant and dimorphic transcriptional responses to maternal trichloroethylene and/or N-acetyl cysteine exposure in Wistar rat placental tissue](https://pubmed.ncbi.nlm.nih.gov/36396003/)

## Abstract
Numerous Superfund sites are contaminated with the volatile organic chemical trichloroethylene (TCE). In women, exposure to TCE in pregnancy is associated with reduced birth weight. Our previous study reported that TCE exposure in pregnant rats decreased fetal weight and elevated oxidative stress biomarkers in placentae, suggesting placental injury as a potential mechanism of TCE-induced adverse birth outcomes. In this study, we investigated if co-exposure with the antioxidant N-acetylcysteine (NAC) attenuates TCE exposure effects on RNA expression. Timed-pregnant Wistar rats were exposed orally to 480 mg TCE/kg/day on gestation days 6-16. Exposure of 200 mg NAC/kg/day alone or as a pre/co-exposure with TCE occurred on gestation days 5-16 to stimulate antioxidant genes prior to TCE exposure. Tissue was collected on gestation day 16. In male and female placentae, we evaluated TCE- and/or NAC-induced changes to gene expression and pathway enrichment analyses using false discovery rate (FDR) and fold-change criteria. In female placentae, exposure to TCE caused significant differential expression 129 genes while the TCE+NAC altered 125 genes, compared with controls (FDR< 0.05 + fold-change >1). In contrast, in male placentae TCE exposure differentially expressed 9 genes and TCE+NAC differentially expressed 35 genes, compared with controls (FDR< 0.05 + fold-change >1). NAC alone did not significantly alter gene expression in either sex. Differentially expressed genes observed with TCE exposure were enriched in mitochondrial biogenesis and oxidative phosphorylation pathways in females whereas immune system pathways and endoplasmic reticulum stress pathways were differentially expressed in both sexes (FDR<0.05). TCE treatment was differentially enriched for genes regulated by the transcription factors ATF6 (both sexes) and ATF4 (males only), indicating a cellular condition triggered by misfolded proteins during endoplasmic reticulum stress. This study demonstrates novel genes and pathways involved in TCE-induced placental injury and showed antioxidant co-treatment largely did not attenuate TCE exposure effects.

## Funding
This work was supported by the National Institute of Environmental Health Sciences, National Institutes of Health (Grant Nos. P42 ES017198, P30 ES017885, R01 ES025574, R01 ES025531, T32 ES007062 and R01 ES028802); National Institute of Diabetes and Digestive Kidney Diseases (Grant Nos. R01 DK107535 and T32 DK071212); National Institute of Aging (Grant Nos. R01 AG055406 and P30 AG053760). The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIEHS, NIDDK, NIA, or NIH.

## Data Availability
RNA-seq fastq and featureCount files are publicly available for download at SRA. Gene Expression Omnibus (GEO) accession number: [GSE168232](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE168232). 

## Script Files
*tce_rat_rmd_r_files* contains the result plots in this project

ATF6_targets.csv: containing description of target genes

Coldata_48.txt: containing demographic information of samples

genes_upset_plot.csv: data for upset plot

metadata.csv: containing metadata of samples

tce_rat_counts.rda: gene raw count data

top_heatmap_genes.csv: top genes in heatmap

xbp1.csv: gene description

tce_rat_rmd_r.rmd: data cleaning, differential gene expression analysis, enrichment test, and result plotting
