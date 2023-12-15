# Supplementary Table S1

*Table of PURA binding sites from the FLAG-PURA IH-AB data set.* Given are the genomic position (seqnames, start, end, strand) together with the width of the binding site, the binding score, together with the number of crosslinks per replicate (clp_rep1, clp_rep2, clp_rep3, clp_rep4), whether this replicate supports the binding site sufficiently (cl1_overThresh, cl2_overThresh, cl3_overThresh, cl4_overThresh) and some information on the bound transcript (gene_id, gene_type, gene_name, type).

# Supplementary Table S2

*Table of PURA binding sites from the FLAG-PURA FL-AB data set.* Given are the genomic position (seqnames, start, end, strand) together with the width of the binding site, the binding score, together with the number of crosslinks per replicate (clp_rep1, clp_rep2, clp_rep3, clp_rep4), whether this replicate supports the binding site sufficiently (cl1_overThresh, cl2_overThresh, cl3_overThresh, cl4_overThresh) and some information on the bound transcript (gene_id, gene_type, gene_name, type).

# Supplementary Table S3

*Table of differential binding analysis from FLAG-PURA IH-AB vs endogenous PURA.* Given are the genomic position (seqnames, start, end, strand) together with the width of the binding site, the binding score, some information on the bound transcript (gene_id, gene_type, gene_name, type), together with the number of crosslinks per binding site of the gene for each replicate (counts.bs.1_endo, counts.bs2_endo, counts.bs.3_endo, counts.bs.4_endo, counts.bs.1_oe, counts.bs2_oe, counts.bs.3_oe, counts.bs.4_oe) and in the background (counts.bg.1_endo, counts.bg2_endo, counts.bg.3_endo, counts.bg.4_endo, counts.bg.1_oe, counts.bg2_oe, counts.bg.3_oe, counts.bg.4_oe). Statistics are given for the binding sites (bs.baseMean, bs.log2FoldChange, bs.lfcSE, bs.stat, bs.pvalue, bs.padj) and for the background distribution per gene (bg.baseMean, bg.log2FoldChange, bg.lfcSE, bg.stat, bg.pvalue, bg.padj).

# Supplementary Table S4

*Table of differential binding analysis from FLAG-PURA FL-AB vs endogenous PURA.* Given are the genomic position (seqnames, start, end, strand) together with the width of the binding site, the binding score, some information on the bound transcript (gene_id, gene_type, gene_name, type), together with the number of crosslinks per binding site of the gene for each replicate (counts.bs.1_endo, counts.bs2_endo, counts.bs.3_endo, counts.bs.4_endo, counts.bs.1_oe, counts.bs2_oe, counts.bs.3_oe, counts.bs.4_oe) and in the background (counts.bg.1_endo, counts.bg2_endo, counts.bg.3_endo, counts.bg.4_endo, counts.bg.1_oe, counts.bg2_oe, counts.bg.3_oe, counts.bg.4_oe). Statistics are given for the binding sites (bs.baseMean, bs.log2FoldChange, bs.lfcSE, bs.stat, bs.pvalue, bs.padj) and for the background distribution per gene (bg.baseMean, bg.log2FoldChange, bg.lfcSE, bg.stat, bg.pvalue, bg.padj).

# Supplementary Table S5

*Table of differential binding analysis from FLAG-PURA IH-AB replicate 1&2 vs replicate 3&4.* Given are the genomic position (seqnames, start, end, strand) together with the width of the binding site, the binding score, some information on the bound transcript (gene_id, gene_type, gene_name, type), together with the number of crosslinks per binding site of the gene for each replicate (counts.bs.1_endo, counts.bs2_endo, counts.bs.3_endo, counts.bs.4_endo, counts.bs.1_oe, counts.bs2_oe, counts.bs.3_oe, counts.bs.4_oe) and in the background (counts.bg.1_endo, counts.bg2_endo, counts.bg.3_endo, counts.bg.4_endo, counts.bg.1_oe, counts.bg2_oe, counts.bg.3_oe, counts.bg.4_oe). Statistics are given for the binding sites (bs.baseMean, bs.log2FoldChange, bs.lfcSE, bs.stat, bs.pvalue, bs.padj) and for the background distribution per gene (bg.baseMean, bg.log2FoldChange, bg.lfcSE, bg.stat, bg.pvalue, bg.padj).

# Supplementary Table S6

*Table of de novo motif prediction on all PURA binding sites by STREME.*


# Supplementary Table S7

*Table of de novo motif prediction on 3'UTR PURA binding sites by STREME.*


# Supplementary Table S8

*Table of de novo motif prediction on CDS PURA binding sites by STREME.*

# Supplementary Table S9

*Tables of all significantly enriched REACTOME* for the
genes of the 3,415 differentially expressed RNAs in PURA knockdown. Functional
enrichment analysis is performed in R using the “hypergeometric” mode (FDR < 0.1)
of the hypeR package (version 1.9.1) with all genes with at least one PURA crosslink
event as background. Given are the test statistics from hypeR (pval; fdr; “signature”,
number of target genes found in any term; “geneset”, number of all genes belonging
to term; “overlap”, number of signature genes in geneset, “background”, number of
background genes), the gene names of all hits per term (“hits") and the ratio of hits
per term (“overlap”/”geneset”). Enrichment analysis was performed once for RNAs
downregulated in PURA knockdown (n = 1752, FDR < 0.01, log2foldchange < 0) and
once for RNAs upregulated in PURA knockdown (n = 1663, FDR < 0.01,
log2foldchange > 0), marked in the column ”Regulation in PURA KD/CTRL” as “down”
and “up”, respectively.

# Supplementary Table S10

*Tables of all significantly enriched GeneOntology (GO) cellular compartment terms* for the
genes of the 3,415 differentially expressed RNAs in PURA knockdown. Functional
enrichment analysis is performed in R using the “hypergeometric” mode (FDR < 0.1)
of the hypeR package (version 1.9.1) with all genes with at least one PURA crosslink
event as background. Given are the test statistics from hypeR (pval; fdr; “signature”,
number of target genes found in any term; “geneset”, number of all genes belonging
to term; “overlap”, number of signature genes in geneset, “background”, number of
background genes), the gene names of all hits per term (“hits") and the ratio of hits
per term (“overlap”/”geneset”). Enrichment analysis was performed once for RNAs
downregulated in PURA knockdown (n = 1752, FDR < 0.01, log2foldchange < 0) and
once for RNAs upregulated in PURA knockdown (n = 1663, FDR < 0.01,
log2foldchange > 0), marked in the column ”Regulation in PURA KD/CTRL” as “down”
and “up”, respectively.
