Interesting Papers

Paper Notes

#### Disregulation of expression correlates with rare-allele burden and fitness loss in maize (Kremling et al. 2018)
H: rare alleles contribute to extreme gene expression
Investigated whether rare-allele abundance is greatest in individuals with extreme gene expression

#### Transposable elements and gene expression during the evolution of amniotes (Zeng et al. 2018)
- Evaluate similarity of ortholog gene expression between tissues between species (no TEs in model)
- Conservation of gene expression using hierarchical clustering
- There are multiple TEs near genes, study picked one TE family (ex. SINE) and tested the association between that TE and gene expression, choose x # of genes with that insertion and compare their expression to genes with no TE (SINE) insertion
- For similarity of gene expression (with TEs in model), TEs split into groups: recently inserted, llw divergence TEs (referred to as species-specific TEs), more divergent (non-species specific TEs), genes with no TEs. The two TE groups further broken down into four TE classes: DNA transposon, EVR/LTR, LINE, or SINE
- Previously, tissues vs species clustering of ortholog gene expression had previously been reported using PCA based analysis and used to support the notion that conservation of developmental gene expression programs results in tissue specific gene expression clustering.
- Study found no tissue specific patterns of association of gene expression with TEs
- H: recent TE insertions associated with lower gene expression, largely met but with some exceptions such as human SINE were associated with increased gene expression
- Older TE insertions contribute to rewiring of transcriptional networks and would have had time to be adapted as enhancers and might be assoc. With gene expression

#### Local PCA shows how the effect of population structure differs along the genome (Li and Ralph 2019)
- Wright 1949 defined population structure to encompass “such matters as numbers, composition by age and sex, and state of subdivision” where “subdivision” refers to the restricted migration between subpopulations
- Phrase also used to refer to the fenetic patterns that result from this process, (ex. Mean relatedness between individuals from distinct populations)
- Blair 1943 → population structure: sunch factors as size of breeding populations, perodic fluctuation of pop size, sex ratio, activity range, and differential survivial of progeny (includes natural selection while Wright’s does not)
- Patterns in genome wide relatedness are summarized by PCA to the genotype matrix, as inspired by the pioneering work of Menozzi et al. 1978, can be related to the genealogical history of the samples, such as time to the most recent common ancestor and migration rate between populations, and sometimes produce maps of population structure that reflect the samples’ geographic origin distorted by rates of gene flow
- “Local” pca → refers to proximity along the genome
- Single values (such as Fst) may be too simplistic b/c we are using a single statistic to explain a complex process influenced by more than selection
- Github: https://github.com/petrelharp/local_pca


#### An atlas of genetic associations in UK Biobank (Canela-Xandri et al. 2018)
- Atlas of genetic associations for 118 non-binary and 660 binaray traits of 400k UK Biobank, 9m gentic variants
- GeneATLAS, http://geneatlas.roslin.ed.ac.uk
- Number of GWAS hits increases linearly with the sample size with no sign of saturation
- Estimated allelic effects of GWAS hits obtained from decreasing sample sizes were generally larger, which is in agreement with a ‘winner’s curse’ effect
- 13% of associations were within the HLA region
- Mapped to 38k independent loci, 3m hits total after Bonferroni correction
- Significant correlation between the number of hits and the SNP heritability of the traits, suggesting that the number of loci affecting a trait might be proportional to the heritability of the trait
- Database includes significant and non-significant associations, providing an unbiased view of phenotype-genotype associations across a large number of traits within a single cohort
- Database also includes ~200k independent genotype phenoty[e associations, genetic and environmental correlations, and estimates of SNP heritability

#### 10 Years of GWAS Discovery: Biology, Function, and Translation (Visscher et al. 2017)
- GWAS rely and exploit linkage disequilibrium, the correlation structure that exists among DNA variants in the current genome as a result of historical evolutionary forces, particularly finite population size, mutation, recombination rate, and natural selection
Statistical power to detect associations between DNA variants and a trait depends on the experimental sample size, distribution of effect sizes of unknown causal genetic variants that are segregating in the population, frequency of those variants, and the LD between observed genotyped DNA variants and the unknown causal variants
Therefore, the potential of a GWAS to succeed for a particular trait or disease depends on 
(1) how many loci affecting the trait segregate in the population, 
(2) the joint distribution of effect size and allele frequency at those loci (sometimes called genetic architecture), 
(3) the experimental sample size, 
(4) the panel of genome-wide variants that are used in the GWAS, and 
(5) how heterogeneous the trait or disease being studied is. The last relates to both the biology of the trait and the ability to diagnose or measure it with precision.

#### A global overview of pleiotropy and genetic architecture in complex traits (Watanabe et al. 2019)
Catalog of 4155 GWAS summary statistics (3,555 sets of summary statistics from 294 studies + new GWAS on 600 traits from the UK Biobank)
Traits classified into 27 domains; ~3k unique traits; avg sample size 56250
Online database: https://atlas.ctglab.nl
Q: What is the extent of pleiotropy  in the human genome? Finite number of segregating sites within human genome, suggets pleiotropy, could establish direction of causalitly between traits and shared genetic mechanisms
61% of genome covered in GWAS hits, 93.3% were loci associated with more than 1 trait, 90% were multidomain loci
Most pleiotropic locus: 441 trait associated loci from 213 traits across 23 traait domains
Looked at characteristics of trait-associated variants in terms of effect size, MAF, functional consequences on genes and regulatory functions using the ‘lead’ snps
Most pleiotropic gene sets were involved in regulation of transcription
Majority of trait associated gene sets are trait specific
Widely aacknolowledged that 90% of GWAS findings fall into noncoding regions (intergenic, intronic)

#### Expression quantitative trait loci: present and future (Nica and Dermitzakis 2013)
- eQTL is a locus that explains a fraction of the genetic variable of a gene expression phenotype
- Standard eQTL analyses involve a direct association test between markers of genetic variation with gene expression levels typically measured in 10-100 individuals
- Association can be performed proximally or distally to a gene
- Regulatory variants have been characterized as either cis or trans acting, reflecting the predicted nature of interactions and location in relation to the pyhsical distance from the gene they (eQTL) regulate 
- Cis eQTLs = within 1 Mb either siide of a gene’s TSS
- Trans eQTL at least 5 Mb downstream or upstream of the TSS or on a different chromosome, harder to detect b/c looking at the whole-genome for potential regulatory effects
- Most regulatory control takes place locally in the vicinity of genes
- changes in cis and trans gene regulation (Wittkopp et al. 2004)
- Cis-regulatory changes affect: transcription initiation, transcription rate, and/or transcript stability in an allele-specific manner
- Trans-regulatory changes affect: modify the activity ot expression og factors that interact with cis-regulatory sequences
- Both contribute to the divergent gene expression, but their respective contributions remain unknown

#### Transposable element influences on gene expression in plants (Hirsch and Springer 2017)
- Three ways that transposons can influence gene expression
1) TE insertions within introns or untranslated regions of genes are often tolerated and have minimal impact on expression level or splicing (or they can produce aberrant/novel transcripts)
2) TEs can provide novel alternative promoters, which can lead to new expression patterns or original coding potential of an alternate transcript
3) TE insertions near genes can influence regulation of gene expression through a variety of mechanisms (ex. May provide novel cis-acting regulatory sites behanving as enhancers or insert within existing enchancers to influence transcript production. 
- TEs can change chromatin modifications near genes which can influecnce gene expression levels
- Recombination low at TE regions
- Genes habe set of chromatin modifications such as histone acetylation and methylaation of histone H3 at lysine 4 (H3K4me) that are associated with active transcription
- TEs enriched for chromatin modifications such as CHG (where H is any nucleotide other than G) DNA methylation, H3K9me2, and H3K27me1, which are associated with transcriptional silencing


- TEs classified by (Wicker et al. 2007)
1) class I elements: retrotransposons,most common in plant genomes and often contain long terminal repeats (LTRs) and transpose by an RNA intermediate using a copy and paste mechanism
    - Classified into five orders, each of which can be subdivided into multiple superfamilies used on their features and structure
2) Class II elements: DNA transposons have terminal inverted repeats (TIRs) and utilize a DNA intermediate for movement that employs a “cut and paste” mechanism, lower levels in plant genomes than retros
- Include Helitron elements that lack TIRs
- Class I and II elements require both autonomous and non-autonomous elements
- Autonomous TEs encode all the necessary factors to facilitate transposition of an element itself or for other members of the same family
- Non-autonomous elements require an autonomous element of the same family to provide the necessary factors for transposition
- ~18% of the Arabidopsis genome has TEs (~20 Mbp), 85% of the maize genome has homology to TEs (2000 Mbp)
- Soybean, majority of TEs occur in the middle of chromosomes, gene rich arms have little TEs, in maize has high levels of TEs throughout the entire chromosome, chromosome arms still 50% TEs sequences
- A large portion (86%) of maize genes have TEs located within 1 kb, while only 36% of Arabidopsis genes include a TE within 1 kb [15]. In Arabidopsis, fewer than 100 genes contain large TE insertions within introns [16]. 
- In contrast there are several thousand rice genes with large TE insertions within introns [16] and over 10% of maize genes contain at least one TE insertion over 1 kb within an intron
- Methylation patterns in plants
- Plant genes have low CHG and CHH methylation within the coding regions
- Many expressed genes contain moderate levels of CG methylation over coding genes
- Limited evidence for functional role of this methylation
- Some genes with TEs have altered transcript levels, but most do not show different gene expression, changes in chromatin state for TEs located within genes may influence gene expression 
TEs can influence gene expression patterns by disrupting cis-regulatory seqeunces, altering chromatin marks of the cis-regulatory elements, or providing novel regulatory information in addition to cis-regulatory elements to drive expression
TEs are one possible source of novel cis-regulatory information that could influence the expression of nearby genes (outside of SNPs)
TEs themselves also require activation by their own cis-regulatory elements
The Genomic Ecosystem of Transposable Elements in Maize (C. et al. )
Class I retrotransposons (major contributor in plant DNA) orders:
LTR: long terminal repeats
LINE: long interspersed nuclear elements
SINE: short interspersed nuclear elements
All transcribed to mRNA by host polymerases, some translated to produce reverse transcriptase and other enzymes
All use TE encoded enzymes for reverse transcription of a cDNA copy that can be integrated at a new position in the host genome
Class II retrotransposons
TIR elements: physically excised from one position on the chromosome and move by TE-encoded transposase proteins that recognize terminal inverted repeats (TIRs)
Helitrons: transpose by a rolling circle mechanism that generates a new copy after a single strand nick by and element encoded protein and subsequent strand invasion and repair
For most TE’s: generates a target site duplication (TSD) in the host DNA at the integration site, and the identification of a TSD bordering a TE can confirm transposition

#### Regulatory activities of transposable elements: from conflicts to benefits (Chuong et al. 2017)
TEs contribute a substantial fraction of the binding sites across the genome (5-40%, average ~20%) → 16, 20
LTR elemnts tend to contribute more than other TE types → 15, 22,42, probably because LTRs are more likely to possess and tetain their ancestral cis-regulatory activities
For a given TF the majority of TE-dervied binding sites are contributed by a relatively small number of specific TE families that are highly enriched for TF binding events relative to what would be expected based on the density of these TE families in the genome → 18, 20,43,44
Tend to be lineage specific (i.e. different between mice and humans), compared 26 pairs of orthologous TFs across mice and humans, >98% of >130,000 TE derived peaks ID’d in each species were species specific

#### HOME: a histogram based machine learning approach for effective identification of differentially methylated regions (Srivastava et al. 2019)
- Sodium bisulfite treatment of DNA converts cytostintes , but not methylcytosines, into uracils, and during PCR amplification of the PCR amplification of the bisulfite treated DNA the uracils are replaced by thymines
- DNA Methylation: Superior or Subordinate in the Epigenetic Hierarchy? (Jin et al. 2011)
- DNA methylation is a heritable mark involving the covalent transfer of a methyl group to the C-5 position of the cytosine ring of DNA by DNA methyltransferases (DNMTs)
- Cytosines are methylated in both symmetrical (CG or CHG) or asymmetrical (CHH, where H is A, T, or C)
- DNA methylation occurs at cytosines in any context in the genome
- More than 98% of DNA methylation occurs in a CpG dinucleotide context in somatic cells, ~25% all methylation appears in a non-CpG context in embryonic stem cells (ESCs)
- In mammals, most CG dinucleotides are methylated on cytosine residues, whereas CG dinucleotides within promoters tend to be protected from methylation
- Hypomethylation arises mainly from loss of methylation at normally heavily methylated repeat elements, including satellites (SAT2) and retrotransposons (LINEs), leading to genomic instability and oncogene activation
- Locus specific hypermethylation usually occurs at promoter CGIs of tumor suppressor genes, resulting in heritable transcriptional silencing

