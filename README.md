# MethylPattern
MethylPattern is a software package for BS-seq analysis on GenePattern which is one of workflow systems for bioinformatics.

1) BSpipe.Index creates indices for mapping bisulfite reads
2) BSpipe.Mapping maps bisulfite reads to a reference
3) BSpipe.WindowMethylation quantifies the methylation level for sliding windows
4) BSpipe.FeatureMethylation quantifies the methylation level for features such as genes and repeats
5) BSpipe.Correlation measures Pearson or Spearman scores for sites or windwos 
6) BSpipe.Clustering performs the hierarchical, k-means, or PAM clustering for sites or windows
7) BSpipe.PCA performs PCA analysis among sammples
8) BSpipe.DifferentialMethylation identifies differentially methylated sites or windows
9) BSpipe.Annotation annotates differentially methylated sites or windows with UCSC known genes, refseq genes, CpG islands, repeats, SNPs, and so on.
10) BSpipe.DAVID performs enrichment tests on the DAVID web site
11) BSpipe.GSEA performes gene set enrichment analysis
12) BSpipe.UCSCBrowser generates the fiels needed for visualization on the UCSC genome browse.
13) BSpipe.BSQC assesses the quality of bisulfite sequencing
14) BSpipe.CallMethylation calls methylation form mapping results
15) BSpipe.MergeMapping merges mapping files for replicates
16) BSpipe.MethylationDifference calculates methylation differenece between two samples
17) BSpipe.JoinMethylation merges methylation files into a file
18) BSpipe.Boxplot visualizes the methylation level for sites or windows in boxes
19) BSpipe.BSmooth identifies differentially methylated sites or windows accounting for biological variability
20) BSpipe.QDMR identifies differentially methylated regions by entropy
21) BSpipe.CpG_MPs identifies CpG methylation patterns of genomic regions
22) BSpipe.Batch runs a batch job from mapping to annotation
23) BSpipe.CreateArgFile creates an argument file for a batch job
24) BSpipe.CreateSampleConf creates a configuration file for samples
25) BSseq.BSpipe.BatchForSite runs a batch job for sites from mapping to annotation
26) BSseq.BSpipe.BatchForWindow runs a batch job for windows from mapping to annotation
27) BSseq.BSpipe.DifferentialMethylation runs a batch job for differential methylation
28) BSseq.BSpipe.MethylationProfile runs a batch job for a joined table for correlation, PCA and clustering


# Install
Download a release, and then install a zip file on GenePattern.

