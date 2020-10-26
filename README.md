# Literature Review on Epigenetics

Hello, this repo aims at summarizing all the current knowledge about **Epigenetics**. If you are interested to contribute, please contact hongleir@uci.edu, we are looking forard your expertise. 

Table of Contents
=================

   * [Literature Review on Epigenetics](#literature-review-on-epigenetics)
      * [Introduction](#introduction)
      * [Epigeneitics](#epigeneitics)
         * [Histone modification](#histone-modification)
         * [DNA methylation](#dna-methylation)
         * [Nucleosome positioning](#nucleosome-positioning)
         * [Non-coding RNA](#non-coding-rna)
         * [3D chromatin structure](#3d-chromatin-structure)
      * [Molecular Mechanisms of Epigenetics](#molecular-mechanisms-of-epigenetics)
         * [Mechanisms of DNA Methylation](#mechanisms-of-dna-methylation)
         * [Mechanisms of Histone Modification](#mechanisms-of-histone-modification)
         * [Mechanisms of Nucleosome positioning](#mechanisms-of-nucleosome-positioning)
         * [Mechanisms of Non-coding RNA](#mechanisms-of-non-coding-rna)
         * [Mechanisms of 3D chromatin structure](#mechanisms-of-3d-chromatin-structure)
         * [Crosstalk between Genomics, Epigenetics and Environmental Cues](#crosstalk-between-genomics-epigenetics-and-environmental-cues)
      * [Genomic Landscape of Epigenetics in Somatic Cells](#genomic-landscape-of-epigenetics-in-somatic-cells)
         * [Landscape in Promoter](#landscape-in-promoter)
            * [DNA methylation](#dna-methylation-1)
            * [Histone modification](#histone-modification-1)
            * [Nucleosome positioning](#nucleosome-positioning-1)
            * [3D chromatin structure](#3d-chromatin-structure-1)
         * [Landscape in Enhancer](#landscape-in-enhancer)
         * [Landscape in Gene Body](#landscape-in-gene-body)
      * [Epigenetic Technology](#epigenetic-technology)
         * [Analyses of Gene-specific DNA Methylation](#analyses-of-gene-specific-dna-methylation)
         * [Methods for Assessing Genome-wide DNA Methylation](#methods-for-assessing-genome-wide-dna-methylation)
         * [Determination of Histone Modifications of Specific Genes](#determination-of-histone-modifications-of-specific-genes)
         * [Analyses of Genome-wide Histone Modifications](#analyses-of-genome-wide-histone-modifications)
         * [Techniques for Genome-wide Expression of Non-coding RNA](#techniques-for-genome-wide-expression-of-non-coding-rna)
         * [Techniques of Genome-wide Nucleosome Positioning](#techniques-of-genome-wide-nucleosome-positioning)
         * [Analyses of Genome-wide Nucleosome Positioning](#analyses-of-genome-wide-nucleosome-positioning)
         * [Techniques of Genome-wide 3D Chromatin Structure](#techniques-of-genome-wide-3d-chromatin-structure)
         * [Analyses of Genome-wide 3D Chromatin Structure](#analyses-of-genome-wide-3d-chromatin-structure)
         * [Computational Epigenetics](#computational-epigenetics)
      * [Functions of Epigenetics](#functions-of-epigenetics)
         * [Aging Epigenetics](#aging-epigenetics)
         * [Dynamics of Epigenetics in Aging](#dynamics-of-epigenetics-in-aging)
         * [Epigenetics, Stem Cells and Cellular Differentiation](#epigenetics-stem-cells-and-cellular-differentiation)
         * [Dynamics of Epigenetics in Development](#dynamics-of-epigenetics-in-development)
         * [Regeneration Epigenetics](#regeneration-epigenetics)
         * [Epigenetics of X-chromosome Inactivation](#epigenetics-of-x-chromosome-inactivation)
         * [Genomic Imprinting](#genomic-imprinting)
         * [Transgenerational Epigenetics](#transgenerational-epigenetics)
      * [Model Organisms of Epigenetics](#model-organisms-of-epigenetics)
         * [Epigenetics of Lower Organisms](#epigenetics-of-lower-organisms)
         * [Drosophila Epigenetics](#drosophila-epigenetics)
         * [Mouse Epigenetics](#mouse-epigenetics)
         * [Model of Epigenetic Inheritance in Mouse](#model-of-epigenetic-inheritance-in-mouse)
         * [Plant Epigenetics](#plant-epigenetics)
      * [Epigenetics and Human Disease](#epigenetics-and-human-disease)
         * [Cancer Epigenetics](#cancer-epigenetics)
         * [Epigenetics of Immune Disorders](#epigenetics-of-immune-disorders)
         * [Epigenetics of Brain Disorders](#epigenetics-of-brain-disorders)
         * [Epigenetics of Metabolic Diseases](#epigenetics-of-metabolic-diseases)
         * [Imprinting Defects in Humans](#imprinting-defects-in-humans)
      * [Single Cell Epigenetics](#single-cell-epigenetics)
      * [Sequencing Techniques of Single Cell Epigenetics](#sequencing-techniques-of-single-cell-epigenetics)
         * [DNA Methylation](#dna-methylation-2)
         * [Histone modification](#histone-modification-2)
         * [DNA methylation](#dna-methylation-3)
         * [Nucleosome positioning](#nucleosome-positioning-2)
         * [Non-coding RNA](#non-coding-rna-1)
         * [3D chromatin structure](#3d-chromatin-structure-2)
      * [Computational Methods of Single Cell Epigenetics](#computational-methods-of-single-cell-epigenetics)
         * [DNA Methylation](#dna-methylation-4)
         * [Histone modification](#histone-modification-3)
         * [DNA methylation](#dna-methylation-5)
         * [Nucleosome positioning](#nucleosome-positioning-3)
         * [Non-coding RNA](#non-coding-rna-2)
         * [3D chromatin structure](#3d-chromatin-structure-3)
      * [Multi-omics](#multi-omics)
         * [Bulk Techniques](#bulk-techniques)
         * [Single Cell Techniques](#single-cell-techniques)
         * [Analysis of Multi-omic Data](#analysis-of-multi-omic-data)
      * [Epigenetic Epidemiology](#epigenetic-epidemiology)
         * [The Effects of Diet on Epigenetic Processes](#the-effects-of-diet-on-epigenetic-processes)
         * [Environmental Agents and Epigenetic Effects](#environmental-agents-and-epigenetic-effects)
         * [Impact of Infective Agents on the Epigenome](#impact-of-infective-agents-on-the-epigenome)
         * [Population Pharmacoepigenomics](#population-pharmacoepigenomics)
      * [Metabolism and Epigenetics](#metabolism-and-epigenetics)
         * [Metabolic Effects on DNA Methylation](#metabolic-effects-on-dna-methylation)
         * [Metabolism and Chromatin Dynamics](#metabolism-and-chromatin-dynamics)
      * [Epigenetic Therapy](#epigenetic-therapy)
         * [DNA Demethylating Agents in Clinical Medicine](#dna-demethylating-agents-in-clinical-medicine)
         * [Clinical Applications of Histone Deacetylase Inhibitors](#clinical-applications-of-histone-deacetylase-inhibitors)
         * [Combination Epigenetic Therapy](#combination-epigenetic-therapy)
      * [Evolutionary Epigenetics](#evolutionary-epigenetics)
         * [Evolution of Epigenetic Mechanisms](#evolution-of-epigenetic-mechanisms)
         * [Adaptive Evolution and Epigenetics](#adaptive-evolution-and-epigenetics)
      * [The Future of Epigenetics](#the-future-of-epigenetics)
         * [New Directions for Epigenetic Research](#new-directions-for-epigenetic-research)
      * [Reference](#Reference)


## Introduction

## Epigenetics

The genetic message is differentially decoded in both time and space as a result of epigenetic constraints on the genome resulting either in gene activation or silencing[85]. The machinery behind this cell-specific differential gene expression mainly involves *Epigenetics*, which literally means *outside conventional genetics*, refers to the heritable epigenetic modifications and regulations that function without changing the DNA sequence [86, 87]. 

The major epigenetic signals include DNA methylation and demethylation, covalent post- translational reversible modifications of the histone proteins, such as acetylation, methylation, phosphorylation and ubiquitination, incorporation of histone variants and gene regulation by non-coding RNAs [88].

### Histone modification

Histone tails undergo a variety of covalent modifications including acetylation, methylation, phosphorylation, ubiquitination, and sumoylation, regulating key cellular process such as gene transcription, DNA replication, and DNA repair [113, 114].

### DNA methylation

DNA methylation was first discovered in calf thymus DNA by Hotchkiss, in 1948 [96]. It is a heritable epigenetic mark involving the covalent transfer of a methyl group to the C-5 position of the cytosine ring of DNA by DNA methyltransferases 1 (DNMTs) [91]. DNA methylation is well conserved among most plant, animal and fungal models[2]. In prokaryotes, DNA methylation takes place on both cytosine and adenine bases and constitutes a branch of the host restriction system to distinguish self and non-self DNA. However in multicellular eukaryotes this modification is limited to cytosine bases only and acts mainly as a repressive tag resulting in silent chromatin state and transcriptional repression [97, 98]. In mammals, DNA methylation occurs at cytosines in any context of the genome. In plants, cytosines are methylated in both symmetrical (CG or CHG) or asymmetrical (CHH, where H is A, T, or C) contexts [95]. However, more than 98% of DNA methylation occurs in a CpG dinucleotide context in somatic cells [3, 4], while as much as a quarter of all methylation appears in a non-CpG context in embryonic stem cells (ESCs) [95]. 

Most DNA methylation is essential for normal development, and it plays a very important role in a number of key processes including genomic imprinting, X-chromosome inactivation, and suppression of repetitive element transcription and transposition and, when dysregulated, contributes to diseases like cancer [91, 92, 93, 94]. It is considered to be one of the first steps in epigenetic regulation, acting as a fundamental mechanism in functional organization of the human genome. It is also an attractive and promising target in the development of new drugs for cancer chemotherapy as epigenetic alterations are, in principle, more readily reversible than genetic anomalies [88].

### Nucleosome positioning

### Non-coding RNA

### 3D chromatin structure


## Molecular Mechanisms of Epigenetics

### Mechanisms of DNA Methylation


#### Enzymes of DNA methylation

Methylation of DNA is a post synthetic process catalyzed by a family of dedicated enzymes known as DNA by DNMTs(DNA methyltransferases). DNMT1, DNMT3A and DNMT3B methylate the cytosine residue in the presence of cofactor SAM (S-Adenosyl methionine), which donates the –CH3 group and is converted to SAH (S-Adenosyl homocysteine) [86, 101]. 

It has been widely believed that DNMT1 acts mainly as a *maintenance* methyltransferase during DNA synthesis and that DNMT3A and DNMT3B act as *de novo* enzymes in development. However, mounting evidence indicates that DNMT1 may also be required for de novo methylation of genomic DNA19 and that DNMT3A and DNMT3B contribute to maintenance methylation during replication [109, 110].

- DNMT1

**DNMT1** preferentially methylates hemi-methylated DNA in vitro and is localized to replication foci during S phase.

Mouse models with both alleles of Dnmt1 deleted are embryonic lethal at approximately day E9 [104, 105].

- DNMT3A, DNMT3B

DNMT3A and DNMT3B have preference for unmethylated CpG dinucleotides and perform *de novo* methylation during development. Mice lacking DNMT3A die at about 4 weeks of age, whereas DNMT3B knockout induces embryonic lethality at E14.5 to E18.5 [104, 106].

- DNMT3L

DNMT3L assists the DNMT3A/3B by increasing their ability to bind to the
methyl group donor, S-adenosyl-Lmethionine (SAM), and stimulating their
activity *in vivo*, although DNMT3L has no catalytic activity itself [107].

Dnmt3L homozygous-null mice are viable, whereas heterozygous embryos derived from homozygous Dnmt3L-null oocytes die around E9 and display impaired maternal methylation imprints and biallelic expression of imprinted genes normally expressed only from the allele of paternal origin  [108].

### Mechanisms of Histone Modification

### Mechanisms of Nucleosome positioning

### Mechanisms of Non-coding RNA

### Mechanisms of 3D chromatin structure

### Crosstalk between Genomics, Epigenetics and Environmental Cues

#### Links between DNA Methylation & Histone Modifications
During mammalian development and cancer, DNA methylation and
specific histone modifications appear to reciprocally influence each other in deposition: histone methylation may direct DNA methylation patterns  (Fig. 1), and DNA methylation may serve as a template for the establishment of certain histone modifications (Fig. 2) after DNA replication [113].

![Figure 1](https://github.com/Read-Lab-UCI/Epigenetics/blob/main/Figures/Fig1.png)

Figure 1. How the histone code may direct DNA methylation during development and carcinogenesis. (A) During normal development, the transcriptionally activating mark H3K4 me3 (x) blocks or repels DNMTs, whereas the repressive marks H3K9me or H3K27me (y) permit or recruit
DNMTs, possibly by direct protein-protein interactions (e.g., EZH2-DNMTs). During carcinogenesis, disruption of the histone code in the form of (B) loss of H3K4me3 (x), (C) substitution of H3K4me3 with H3K9me or H3K27me (y), randomization of marks, aberrant acquisition of a new mark (z), or (D) loss of all histone marks permits or actively induces DNMT recruitment. x = H3K4me3; y = H3K9me or H3K27me; z = other histone mark; bent arrow = transcription start site; lollipops = histone marks; black circles = DNA methylation.

![Figure 2](https://github.com/Read-Lab-UCI/Epigenetics/blob/main/Figures/Fig2.png)

Figure 2. How the histone code may rely on the DNA methylation machinery for direction. Upon binding to CpG-rich regions, DNMTs may directly recruit HMTs to these domains. During DNA replication, UHRF1 preferentially binds hemimethylated DNA and interacts with/ recruits DNMT1 and G9A. PCNA may also have a role in the recruitment process. Methyl-CpG– binding proteins (MBDs) specifically interact with methylated DNA and may form complexes with HMTs such as SETDB1 to direct histone methylation to regions of DNA methylation.

## Gene Regulation of Epigenetics

### DNA Methylation

DNA methylation obstructs transcriptional activity via two general schemes. First, methylated cytosine bases can hinder the interaction of transcriptional factors and RNA polymerase II with their cognate DNA recognition sequences. Second, methyl-CpG-binding proteins, such as MBD (methyl-CpG-binding domain) proteins, associate with methylated DNA and result in heterochromatin formation by recruiting HDACs (histone deacetylases) [98, 102].

Methylated DNA participates in the formation of chromatin through interactions with various other epigenetic modifications such as the histone code, polycomb complexes, nucleosome positioning, non-coding RNA, and ATP-dependent chromatin remodeling proteins [111].

### Histone Modification

### Nucleosome positioning

### Non-coding RNA

### 3D chromatin structure

## Genomic Landscape of Epigenetics in Mamilian Somatic Cells

The epigenetic landscape can vary across genomic regions (spatial heterogeneity), vary within and across cell cycle(temporal heterogeneity), and across cells (cell-to-cell heterogeneity). It grown increasingly complicated, encompassing DNA methylation, the histone code, non-coding RNA, and nucleosome positioning, along with DNA sequence [89]. 

### Overall Landscape

#### DNA methylation

Mammalian genomes are globally CpG­ depleted and, of the roughly 28 million CpGs in the human genome, 60–80% are generally methylated. Less than 10% of CpGs occur in CG­ dense regions that are termed **CpG islands**; These are prevalent at transcription start sites(TSS) of housekeeping and developmental regulator genes, where they are largely resistant to DNA methylation, i.e. unmethylated [7].

### Epigenetics in Promoter

#### DNAm in Promoter

Most CpGs in mammalian genomes remain methylated during development, but CpG islands found at promoters of many housekeeping or developmentally regulated genes are constitutively **hypomethylated**, i.e. unmethylated. CpG island promoters are not usually repressed by DNA methylation and are instead silenced by **H3K27me3**(H3 lysine 27 methylation), which may also protect them from spurious DNA methylation [40, 41]. 

#### Histone modification in Promoter

#### Nucleosome positioning in Promoter

#### 3D chromatin structure in Promoter


### Epigenetics in CpG island

CpG islands(CGIs), which are known to recruit Trithorax (TrxG) and Polycomb group proteins.


### Epigenetics in Enhancer

### Epigenetics in Gene Body



## Maintenance of Epigenetics

### Maintenance of DNA methylation


## Epigenetic Technology

### Analyses of Gene-specific DNA Methylation

### Methods for Assessing Genome-wide DNA Methylation

### Determination of Histone Modifications of Specific Genes

### Analyses of Genome-wide Histone Modifications

### Techniques for Genome-wide Expression of Non-coding RNA

### Techniques of Genome-wide Nucleosome Positioning

### Analyses of Genome-wide Nucleosome Positioning

### Techniques of Genome-wide 3D Chromatin Structure

### Analyses of Genome-wide 3D Chromatin Structure

### Computational Epigenetics

## Functions of Epigenetics

### Aging Epigenetics

### Dynamics of Epigenetics in Aging

### Epigenetics, Stem Cells and Cellular Differentiation

### Dynamics of Epigenetics in Development

The genomic methylation blueprint is created during two developmental periods—in germ cells and pre-implantation embryos—generating cells with broad developmental potential [99, 100]. Three conserved enzymes, DNA methyltransferase 1 (DNMT1), DNMT3A and DNMT3B, are responsible for its deposition and maintenance and are essential for normal development [5,6].This system of establishing de novo methylation pattern where new methyl marks are added to previously unmethylated cytosines is mainly chaperoned by the de novo methyltransferases DNMT3A and DNMT3B. Maintenance methylation by DNMT1 then ensures that hemi-methylated daughter strands in somatic differentiated cells get methylated to faithfully propagate the proper DNA methylation patterns across successive cell generations [100]. DNA methylation is typically removed during zygote formation and then re-established in the embryo at approximately the time of implantation [103]. 

### Regeneration Epigenetics

### Epigenetics of X-chromosome Inactivation

### Genomic Imprinting

### Transgenerational Epigenetics


## Model Organisms of Epigenetics

### Epigenetics of Lower Organisms

### Drosophila Epigenetics

### Mouse Epigenetics

### Model of Epigenetic Inheritance in Mouse

### Plant Epigenetics

#### Plant DNA methylation

In plants, cytosines are methylated in both symmetrical (CG or CHG) or asymmetrical (CHH, where H is A, T, or C) contexts [95].


## Epigenetics and Human Disease

### Cancer Epigenetics

#### DNA methylation in Cancer

Epigenetic hallmarks of cancer include global DNA hypomethylation and locus-specific hypermethylation of CpG islands (CGIs) [111] Hypomethylation arises mainly from loss of methylation at normally heavily methylated repeat elements, including satellites (e.g., SAT2) and retrotransposons (e.g., LINEs), leading to genomic instability and oncogene activation.  Locus-specific hypermethylation usually occurs at promoter CGIs of tumor suppressor genes, resulting in heritable transcriptional silencing [89, 112].

### Epigenetics of Immune Disorders

### Epigenetics of Brain Disorders

### Epigenetics of Metabolic Diseases

### Imprinting Defects in Humans



## Single Cell Epigenetics

## Sequencing Techniques of Single Cell Epigenetics

### DNA Methylation

### Histone modification

### DNA methylation

### Nucleosome positioning

### Non-coding RNA

### 3D chromatin structure

## Computational Methods of Single Cell Epigenetics

### DNA Methylation

### Histone modification

### DNA methylation

### Nucleosome positioning

### Non-coding RNA

### 3D chromatin structure



## Multi-omics

### Bulk Techniques

### Single Cell Techniques

### Analysis of Multi-omic Data


## Epigenetic Epidemiology

### The Effects of Diet on Epigenetic Processes

### Environmental Agents and Epigenetic Effects

### Impact of Infective Agents on the Epigenome

### Population Pharmacoepigenomics


## Metabolism and Epigenetics

### Metabolic Effects on DNA Methylation

### Metabolism and Chromatin Dynamics



## Epigenetic Therapy

### DNA Demethylating Agents in Clinical Medicine

### Clinical Applications of Histone Deacetylase Inhibitors

### Combination Epigenetic Therapy



## Evolutionary Epigenetics

### Evolution of Epigenetic Mechanisms

### Adaptive Evolution and Epigenetics



## The Future of Epigenetics

### New Directions for Epigenetic Research

## Reference

[1]. Smith, Z. D., & Meissner, A. (2013). DNA methylation: roles in mammalian development. *Nature Reviews Genetics*, *14*(3), 204-220.

[2]. Feng, S., Jacobsen, S. E., & Reik, W. (2010). Epigenetic reprogramming in plant and animal development. *Science*, *330*(6004), 622-627.

[3]. Ziller, M. J., Müller, F., Liao, J., Zhang, Y., Gu, H., Bock, C., … & Gnirke, A. (2011). Genomic distribution and inter-sample variation of non-CpG methylation across human cell types. *PLoS Genet*, *7*(12), e1002389.

[4]. Ramsahoye, B. H., Biniszkiewicz, D., Lyko, F., Clark, V., Bird, A. P., & Jaenisch, R. (2000). Non-CpG methylation is prevalent in embryonic stem cells and may be mediated by DNA methyltransferase 3a. *Proceedings of the National Academy of Sciences*, *97*(10), 5237-5242.

[5]. Okano, M., Bell, D. W., Haber, D. A., & Li, E. (1999). DNA methyltransferases Dnmt3a and Dnmt3b are essential for de novo methylation and mammalian development. *Cell*, *99*(3), 247-257.

[6]. Li, E., Bestor, T. H., & Jaenisch, R. (1992). Targeted mutation of the DNA methyltransferase gene results in embryonic lethality. *Cell*, *69*(6), 915-926.

[7]. Deaton, A. M., & Bird, A. (2011). CpG islands and the regulation of transcription. *Genes & development*, *25*(10), 1010-1022.

[8]. Kishikawa, S., Murata, T., Ugai, H., Yamazaki, T., & Yokoyama, K. K. (2003, September). Control elements of Dnmt1 gene are regulated in cell-cycle dependent manner. In *Nucleic acids symposium series* (Vol. 3, No. 1, pp. 307-308). Oxford University Press.

[9]. Chuang, L. S. H., Ian, H. I., Koh, T. W., Ng, H. H., Xu, G., & Li, B. F. (1997). Human DNA-(cytosine-5) methyltransferase-PCNA complex as a target for p21WAF1. *Science*, *277*(5334), 1996-2000.

[10]. Sharif, J., Muto, M., Takebayashi, S. I., Suetake, I., Iwamatsu, A., Endo, T. A., … & Tajima, S. (2007). The SRA protein Np95 mediates epigenetic inheritance by recruiting Dnmt1 to methylated DNA. *Nature*, *450*(7171), 908-912.

[11]. Bostick, M., Kim, J. K., Estève, P. O., Clark, A., Pradhan, S., & Jacobsen, S. E. (2007). UHRF1 plays a role in maintaining DNA methylation in mammalian cells. *Science*, *317*(5845), 1760-1764.

[12]. Arita, K., Ariyoshi, M., Tochio, H., Nakamura, Y., & Shirakawa, M. (2008). Recognition of hemi-methylated DNA by the SRA protein UHRF1 by a base-flipping mechanism. *Nature*, *455*(7214), 818-821.

[13]. Avvakumov, G. V., Walker, J. R., Xue, S., Li, Y., Duan, S., Bronner, C., … & Dhe-Paganon, S. (2008). Structural basis for recognition of hemi-methylated DNA by the SRA domain of human UHRF1. *Nature*, *455*(7214), 822-825.

[14]. Moldovan, G. L., Pfander, B., & Jentsch, S. (2007). PCNA, the maestro of the replication fork. *Cell*, *129*(4), 665-679.

[15]. Du, Z., Song, J., Wang, Y., Zhao, Y., Guda, K., Yang, S., … & Sedwick, D. (2010). DNMT1 stability is regulated by proteins coordinating deubiquitination and acetylation-driven ubiquitination. *Science signaling*, *3*(146), ra80-ra80.

[16]. Estève, P. O., Chin, H. G., Benner, J., Feehery, G. R., Samaranayake, M., Horwitz, G. A., … & Pradhan, S. (2009). Regulation of DNMT1 stability through SET7-mediated lysine methylation in mammalian cells. *Proceedings of the National Academy of Sciences*, *106*(13), 5076-5081.

[17]. Wang, J., Hevi, S., Kurash, J. K., Lei, H., Gay, F., Bajko, J., … & Gaudet, F. (2009). The lysine demethylase LSD1 (KDM1) is required for maintenance of global DNA methylation. *Nature genetics*, *41*(1), 125-129.

[18]. Fuks, F., Burgers, W. A., Brehm, A., Hughes-Davies, L., & Kouzarides, T. (2000). DNA methyltransferase Dnmt1 associates with histone deacetylase activity. *Nature genetics*, *24*(1), 88-91.

[19]. Rothbart, S. B., Krajewski, K., Nady, N., Tempel, W., Xue, S., Badeaux, A. I., … & Arrowsmith, C. H. (2012). Association of UHRF1 with methylated H3K9 directs the maintenance of DNA methylation. *Nature structural & molecular biology*, *19*(11), 1155.

[20]. Meissner, A., Mikkelsen, T. S., Gu, H., Wernig, M., Hanna, J., Sivachenko, A., … & Gnirke, A. (2008). Genome-scale DNA methylation maps of pluripotent and differentiated cells. *Nature*, *454*(7205), 766-770.

[21]. Lorincz, M. C., Schübeler, D., Hutchinson, S. R., Dickerson, D. R., & Groudine, M. (2002). DNA methylation density influences the stability of an epigenetic imprint and Dnmt3a*b-independent de novo methylation. *Molecular and cellular biology*, *22*(21), 7572-7580.

[22]. Tahiliani, M., Koh, K. P., Shen, Y., Pastor, W. A., Bandukwala, H., Brudno, Y., … & Rao, A. (2009). Conversion of 5-methylcytosine to 5-hydroxymethylcytosine in mammalian DNA by MLL partner TET1. *Science*, *324*(5929), 930-935.

[23]. Ito, S., D’Alessio, A. C., Taranova, O. V., Hong, K., Sowers, L. C., & Zhang, Y. (2010). Role of Tet proteins in 5mC to 5hmC conversion, ES-cell self-renewal and inner cell mass specification. *Nature*, *466*(7310), 1129-1133.

[24]. Williams, K., Christensen, J., Pedersen, M. T., Johansen, J. V., Cloos, P. A., Rappsilber, J., & Helin, K. (2011). TET1 and hydroxymethylcytosine in transcription and DNA methylation fidelity. *Nature*, *473*(7347), 343-348.

[25]. Wu, H., D’Alessio, A. C., Ito, S., Xia, K., Wang, Z., Cui, K., … & Zhang, Y. (2011). Dual functions of Tet1 in transcriptional regulation in mouse embryonic stem cells. *Nature*, *473*(7347), 389-393.

[26]. Stadler, M. B., Murr, R., Burger, L., Ivanek, R., Lienert, F., Schöler, A., … & Tiwari, V. K. (2011). DNA-binding factors shape the mouse methylome at distal regulatory regions. *Nature*, *480*(7378), 490-495.

[27]. Cortellino, S., Xu, J., Sannai, M., Moore, R., Caretti, E., Cigliano, A., … & Abramowitz, L. K. (2011). Thymine DNA glycosylase is essential for active DNA demethylation by linked deamination-base excision repair. *Cell*, *146*(1), 67-79.

[28]. Cortázar, D., Kunz, C., Selfridge, J., Lettieri, T., Saito, Y., MacDougall, E., … & Steinacher, R. (2011). Embryonic lethal phenotype reveals a function of TDG in maintaining epigenetic stability. *Nature*, *470*(7334), 419-423.

[29]. Illingworth, R. S., Gruenewald-Schneider, U., Webb, S., Kerr, A. R., James, K. D., Turner, D. J., … & Bird, A. P. (2010). Orphan CpG islands identify numerous conserved promoters in the mammalian genome. *PLoS Genet*, *6*(9), e1001134.

[30]. Macleod, D., Charlton, J., Mullins, J., & Bird, A. P. (1994). Sp1 sites in the mouse aprt gene promoter are required to prevent methylation of the CpG island. *Genes & development*, *8*(19), 2282-2292.

[31]. Brandeis, M., Frank, D., Keshet, I., Siegfried, Z., Mendelsohn, M., Temper, V., … & Cedar, H. (1994). Spl elements protect a CpG island from de novo methylation. *Nature*, *371*(6496), 435-438.

[32]. Lienert, F., Wirbelauer, C., Som, I., Dean, A., Mohn, F., & Schübeler, D. (2011). Identification of genetic elements that autonomously determine DNA methylation states. *Nature genetics*, *43*(11), 1091-1097.

[33]. Thomson, J. P., Skene, P. J., Selfridge, J., Clouaire, T., Guy, J., Webb, S., … & Turner, D. J. (2010). CpG islands influence chromatin structure via the CpG-binding protein Cfp1. *Nature*, *464*(7291), 1082-1086.

[34]. Clouaire, T., Webb, S., Skene, P., Illingworth, R., Kerr, A., Andrews, R., … & Bird, A. (2012). Cfp1 integrates both CpG content and gene activity for accurate H3K4me3 deposition in embryonic stem cells. *Genes & development*, *26*(15), 1714-1728.

[35]. Erfurth, F. E., Popovic, R., Grembecka, J., Cierpicki, T., Theisler, C., Xia, Z. B., … & Zeleznik-Le, N. J. (2008). MLL protects CpG clusters from methylation within the Hoxa9 gene, maintaining transcript expression. *Proceedings of the National Academy of Sciences*, *105*(21), 7517-7522.

[36]. Otani, J., Nankumo, T., Arita, K., Inamoto, S., Ariyoshi, M., & Shirakawa, M. (2009). Structural basis for recognition of H3K4 methylation status by the DNA methyltransferase 3A ATRX–DNMT3–DNMT3L domain. *EMBO reports*, *10*(11), 1235-1241.

[37]. Ooi, S. K., Qiu, C., Bernstein, E., Li, K., Jia, D., Yang, Z., … & Cheng, X. (2007). DNMT3L connects unmethylated lysine 4 of histone H3 to de novo methylation of DNA. *Nature*, *448*(7154), 714-717.

[38]. Conerly, M. L., Teves, S. S., Diolaiti, D., Ulrich, M., Eisenman, R. N., & Henikoff, S. (2010). Changes in H2A. Z occupancy and DNA methylation during B-cell lymphomagenesis. *Genome research*, *20*(10), 1383-1390.

[39]. Yang, X., Noushmehr, H., Han, H., Andreu-Vieyra, C., Liang, G., & Jones, P. A. (2012). Gene reactivation by 5-Aza-2′-deoxycytidine–induced demethylation requires SRCAP–mediated H2A. Z insertion to establish nucleosome depleted regions. *PLoS Genet*, *8*(3), e1002604.

[40]. Brinkman, A. B., Gu, H., Bartels, S. J., Zhang, Y., Matarese, F., Simmer, F., … & Stunnenberg, H. G. (2012). Sequential ChIP-bisulfite sequencing enables direct genome-scale investigation of chromatin and DNA methylation cross-talk. *Genome research*, *22*(6), 1128-1138.

[41]. Bartke, T., Vermeulen, M., Xhemalce, B., Robson, S. C., Mann, M., & Kouzarides, T. (2010). Nucleosome-interacting proteins regulated by DNA and histone methylation. *Cell*, *143*(3), 470-484.

[42]. Jones, P. A. (2012). Functions of DNA methylation: islands, start sites, gene bodies and beyond. *Nature Reviews Genetics*, *13*(7), 484-492.

[43]. Ginno, P. A., Lott, P. L., Christensen, H. C., Korf, I., & Chédin, F. (2012). R-loop formation is a distinctive characteristic of unmethylated human CpG island promoters. *Molecular cell*, *45*(6), 814-825.

[44]. Schoorlemmer, J., Van Puijenbroek, A., van Den Eijnden, M. M. E. D., Jonk, L., Pals, C., & Kruijer, W. (1994). Characterization of a negative retinoic acid response element in the murine Oct4 promoter. *Molecular and cellular biology*, *14*(2), 1122-1136.

[45]. Dennis, K., Fan, T., Geiman, T., Yan, Q., & Muegge, K. (2001). Lsh, a member of the SNF2 family, is required for genome-wide methylation. *Genes & development*, *15*(22), 2940-2944.

[46]. Zhu, H., Geiman, T. M., Xi, S., Jiang, Q., Schmidtmann, A., Chen, T., … & Muegge, K. (2006). Lsh is involved in de novo methylation of DNA. *The EMBO journal*, *25*(2), 335-345.

[47]. Myant, K., & Stancheva, I. (2008). LSH cooperates with DNA methyltransferases to repress transcription. *Molecular and cellular biology*, *28*(1), 215-226.

[48]. Myant, K., Termanis, A., Sundaram, A. Y., Boe, T., Li, C., Merusi, C., … & Stancheva, I. (2011). LSH and G9a*GLP complex are required for developmentally programmed DNA methylation. *Genome research*, *21*(1), 83-94.

[49]. Epsztejn-Litman, S., Feldman, N., Abu-Remaileh, M., Shufaro, Y., Gerson, A., Ueda, J., … & Bergman, Y. (2008). De novo DNA methylation promoted by G9a prevents reprogramming of embryonically silenced genes. *Nature structural & molecular biology*, *15*(11), 1176-1183.

[50]. Dong, K. B., Maksakova, I. A., Mohn, F., Leung, D., Appanah, R., Lee, S., … & Tachibana, M. (2008). DNA methylation in ES cells requires the lysine methyltransferase G9a but not its catalytic activity. *The EMBO journal*, *27*(20), 2691-2701.

[51]. Ayyanathan, K., Lechner, M. S., Bell, P., Maul, G. G., Schultz, D. C., Yamada, Y., … & Rauscher, F. J. (2003). Regulated recruitment of HP1 to a euchromatic gene induces mitotically heritable, epigenetic gene silencing: a mammalian cell culture model of gene variegation. *Genes & development*, *17*(15), 1855-1869.

[52]. Lehnertz, B., Ueda, Y., Derijck, A. A., Braunschweig, U., Perez-Burgos, L., Kubicek, S., … & Peters, A. H. (2003). Suv39h-mediated histone H3 lysine 9 methylation directs DNA methylation to major satellite repeats at pericentric heterochromatin. *Current Biology*, *13*(14), 1192-1200.

[53]. Chen, T., Tsujimoto, N., & Li, E. (2004). The PWWP domain of Dnmt3a and Dnmt3b is required for directing DNA methylation to the major satellite repeats at pericentric heterochromatin. *Molecular and cellular biology*, *24*(20), 9048-9058.

[54]. Gopalakrishnan, S., Sullivan, B. A., Trazzi, S., Della Valle, G., & Robertson, K. D. (2009). DNMT3B interacts with constitutive centromere protein CENP-C to modulate DNA methylation and the histone code at centromeric regions. *Human molecular genetics*, *18*(17), 3178-3193.

[55]. Okada, T., Ohzeki, J. I., Nakano, M., Yoda, K., Brinkley, W. R., Larionov, V., & Masumoto, H. (2007). CENP-B controls centromere formation depending on the chromatin context. *Cell*, *131*(7), 1287-1300.

[56]. Waterston, R. H., Lindblad-Toh, K., Birney, E., Rogers, J., Abril, J. F., Agarwal, P., … & Antonarakis, S. E. (2002). Initial sequencing and comparative analysis of the mouse genome. *Nature*, *420*(6915), 520-562.

[57].  Liang, G., Chan, M. F., Tomigahara, Y., Tsai, Y. C., Gonzales, F. A., Li, E., … & Jones, P. A. (2002). Cooperativity between DNA methyltransferases in the maintenance methylation of repetitive elements. *Molecular and cellular biology*, *22*(2), 480-491.

[58]. Karimi, M. M., Goyal, P., Maksakova, I. A., Bilenky, M., Leung, D., Tang, J. X., … & Lorincz, M. C. (2011). DNA methylation and SETDB1*H3K9me3 regulate predominantly distinct sets of genes, retroelements, and chimeric transcripts in mESCs. *Cell stem cell*, *8*(6), 676-687.

[59]. Leung, D. C., Dong, K. B., Maksakova, I. A., Goyal, P., Appanah, R., Lee, S., … & Rossi, F. (2011). Lysine methyltransferase G9a is required for de novo DNA methylation and the establishment, but not the maintenance, of proviral silencing. *Proceedings of the National Academy of Sciences*, *108*(14), 5718-5723.

[60]. Ooi, S. K., Wolf, D., Hartung, O., Agarwal, S., Daley, G. Q., Goff, S. P., & Bestor, T. H. (2010). Dynamic instability of genomic methylation patterns in pluripotent stem cells. *Epigenetics & chromatin*, *3*(1), 17.

[61]. Muotri, A. R., Marchetto, M. C., Coufal, N. G., Oefner, R., Yeo, G., Nakashima, K., & Gage, F. H. (2010). L1 retrotransposition in neurons is modulated by MeCP2. *Nature*, *468*(7322), 443-446.

[62]. Jones, P. L., Veenstra, G. C. J., Wade, P. A., Vermaak, D., Kass, S. U., Landsberger, N., … & Wolffe, A. P. (1998). Methylated DNA and MeCP2 recruit histone deacetylase to repress transcription. *Nature genetics*, *19*(2), 187-191.

[63]. Nan, X., Ng, H. H., Johnson, C. A., Laherty, C. D., Turner, B. M., Eisenman, R. N., & Bird, A. (1998). Transcriptional repression by the methyl-CpG-binding protein MeCP2 involves a histone deacetylase complex. *Nature*, *393*(6683), 386-389.

[64]. Jähner, D., Stuhlmann, H., Stewart, C. L., Harbers, K., Löhler, J., Simon, I., & Jaenisch, R. (1982). De novo methylation and expression of retroviral genomes during mouse embryogenesis. *Nature*, *298*(5875), 623-628.

[65]. Stewart, C. L., Stuhlmann, H., Jähner, D., & Jaenisch, R. (1982). De novo methylation, expression, and infectivity of retroviral genomes introduced into embryonal carcinoma cells. *Proceedings of the National Academy of Sciences*, *79*(13), 4098-4102.

[66]. Rottach, A., Frauer, C., Pichler, G., Bonapace, I. M., Spada, F., & Leonhardt, H. (2010). The multi-domain protein Np95 connects DNA methylation and histone modification. *Nucleic acids research*, *38*(6), 1796-1804.

[67]. van de Lagemaat, L. N., Flenley, M., Lynch, M. D., Garrick, D., Tomlinson, S. R., Kranc, K. R., & Vernimmen, D. (2018). CpG binding protein (CFP1) occupies open chromatin regions of active genes, including enhancers and non-CpG islands. *Epigenetics & chromatin*, *11*(1), 59.

[68]. Adam, S., Anteneh, H., Hornisch, M., Wagner, V., Lu, J., Radde, N. E., … & Jeltsch, A. (2020). DNA sequence-dependent activity and base flipping mechanisms of DNMT1 regulate genome-wide DNA methylation. *Nature communications*, *11*(1), 1-15.

[69]. Pradhan, S., Bacolla, A., Wells, R. D., & Roberts, R. J. (1999). Recombinant human DNA (cytosine-5) methyltransferase I. Expression, purification, and comparison of de novo and maintenance methylation. *Journal of Biological Chemistry*, *274*(46), 33002-33010.

[70]. Fatemi, M., Hermann, A., Pradhan, S., & Jeltsch, A. (2001). The activity of the murine DNA methyltransferase Dnmt1 is controlled by interaction of the catalytic domain with the N-terminal part of the enzyme leading to an allosteric activation of the enzyme after binding to methylated DNA. *Journal of molecular biology*, *309*(5), 1189-1199.

[71]. Hermann, A., Goyal, R., & Jeltsch, A. (2004). The Dnmt1 DNA-(cytosine-C5)-methyltransferase methylates DNA processively with high preference for hemimethylated target sites. *Journal of Biological Chemistry*, *279*(46), 48350-48359.

[72]. Song, J., Teplova, M., Ishibe-Murakami, S., & Patel, D. J. (2012). Structure-based mechanistic insights into DNMT1-mediated maintenance DNA methylation. *Science*, *335*(6069), 709-712.

[73]. Bashtrykov, P., Jankevicius, G., Smarandache, A., Jurkowska, R. Z., Ragozin, S., & Jeltsch, A. (2012). Specificity of Dnmt1 for methylation of hemimethylated CpG sites resides in its catalytic domain. *Chemistry & biology*, *19*(5), 572-578.

[74]. Lin, I. G., Han, L., Taghva, A., O’Brien, L. E., & Hsieh, C. L. (2002). Murine de novo methyltransferase Dnmt3a demonstrates strand asymmetry and site preference in the methylation of DNA in vitro. *Molecular and cellular biology*, *22*(3), 704-723.

[75]. Handa, V., & Jeltsch, A. (2005). Profound flanking sequence preference of Dnmt3a and Dnmt3b mammalian DNA methyltransferases shape the human epigenome. *Journal of molecular biology*, *348*(5), 1103-1112.

[76]. Wienholz, B. L., Kareta, M. S., Moarefi, A. H., Gordon, C. A., Ginno, P. A., & Chédin, F. (2010). DNMT3L modulates significant and distinct flanking sequence preference for DNA methylation by DNMT3A and DNMT3B in vivo. *PLoS Genet*, *6*(9), e1001106.

[77]. Jurkowska, R. Z., Siddique, A. N., Jurkowski, T. P., & Jeltsch, A. (2011). Approaches to enzyme and substrate design of the murine Dnmt3a DNA methyltransferase. *Chembiochem*, *12*(10), 1589-1594.

[78]. Emperle, M., Rajavelu, A., Kunert, S., Arimondo, P. B., Reinhardt, R., Jurkowska, R. Z., & Jeltsch, A. (2018). The DNMT3A R882H mutant displays altered flanking sequence preferences. *Nucleic acids research*, *46*(6), 3130-3139.

[79]. Emperle, M., Adam, S., Kunert, S., Dukatz, M., Baude, A., Plass, C., … & Jeltsch, A. (2019). Mutations of R882 change flanking sequence preferences of the DNA methyltransferase DNMT3A and cellular methylation patterns. *Nucleic acids research*, *47*(21), 11355-11367.

[80]. Gao, L., Emperle, M., Guo, Y., Grimm, S. A., Ren, W., Adam, S., … & Dukatz, M. (2020). Comprehensive structure-function characterization of DNMT3B and DNMT3A reveals distinctive de novo DNA methylation mechanisms. *bioRxiv*.

[81]. Vilkaitis, G., Suetake, I., Klimašauskas, S., & Tajima, S. (2005). Processive methylation of hemimethylated CpG sites by mouse Dnmt1 DNA methyltransferase. *Journal of Biological Chemistry*, *280*(1), 64-72.

[82]. Goyal, R., Reinhardt, R., & Jeltsch, A. (2006). Accuracy of DNA methylation pattern preservation by the Dnmt1 methyltransferase. *Nucleic acids research*, *34*(4), 1182-1188.

[83]. Song, J., Rechkoblit, O., Bestor, T. H., & Patel, D. J. (2011). Structure of DNMT1-DNA complex reveals a role for autoinhibition in maintenance DNA methylation. *Science*, *331*(6020), 1036-1040.

[84]. Ye, F., Kong, X., Zhang, H., Liu, Y., Shao, Z., Jin, J., … & Liu, Y. C. (2018). Biochemical studies and molecular dynamic simulations reveal the molecular basis of conformational changes in DNA methyltransferase-1. *ACS chemical biology*, *13*(3), 772-781.

[85]. Jaenisch, R., & Bird, A. (2003). Epigenetic regulation of gene expression: how the genome integrates intrinsic and environmental signals. Nature genetics, 33(3), 245-254.

[86]. Patra, S. K., Deb, M., & Patra, A. (2011). Molecular marks for epigenetic identification of developmental and cancer stem cells. Clinical epigenetics, 2(1), 27-53.

[87]. Campbell, P. M., & Szyf, M. (2003). Human DNA methyltransferase gene DNMT1 is regulated by the APC pathway. Carcinogenesis, 24(1), 17-24.

[88]. Jurkowska, R. Z., Jurkowski, T. P., & Jeltsch, A. (2011). Structure and function of mammalian DNA methyltransferases. Chembiochem, 12(2), 206-222.

[89]. Jin, B., Li, Y., & Robertson, K. D. (2011). DNA methylation: superior or subordinate in the epigenetic hierarchy?. Genes & cancer, 2(6), 607-617.

[90]. Svedruzic, Z. M. (2008). Mammalian cytosine DNA methyltransferase Dnmt1: enzymatic mechanism, novel mechanism-based inhibitors, and RNA-directed DNA methylation. Current medicinal chemistry, 15(1), 92-106.

[91]. Robertson, K. D. (2005). DNA methylation and human disease. Nature Reviews Genetics, 6(8), 597-610.

[92]. Gopalakrishnan, S., Van Emburgh, B. O., & Robertson, K. D. (2008). DNA methylation in development and human disease. Mutation Research/Fundamental and Molecular Mechanisms of Mutagenesis, 647(1-2), 30-38.

[93]. Jin, B., Yao, B., Li, J. L., Fields, C. R., Delmas, A. L., Liu, C., & Robertson, K. D. (2009). DNMT1 and DNMT3B modulate distinct polycomb-mediated histone modifications in colon cancer. Cancer research, 69(18), 7412-7421.

[94]. Jin, B., Tao, Q., Peng, J., Soo, H. M., Wu, W., Ying, J., ... & Robertson, K. D. (2008). DNA methyltransferase 3B (DNMT3B) mutations in ICF syndrome lead to altered epigenetic modifications and aberrant expression of genes regulating development, neurogenesis and immune function. Human molecular genetics, 17(5), 690-709.

[95]. Lister, R., Pelizzola, M., Dowen, R. H., Hawkins, R. D., Hon, G., Tonti-Filippini, J., ... & Edsall, L. (2009). Human DNA methylomes at base resolution show widespread epigenomic differences. nature, 462(7271), 315-322.

[96]. Hotchkiss, R. D. (1948). The quantitative separation of purines, pyrimidines, and nucleosides by paper chromatography. Journal of Biological Chemistry, 175(1), 315-332.

[97]. Jeltsch, A. (2002). Beyond Watson and Crick: DNA methylation and molecular enzymology of DNA methyltransferases. Chembiochem, 3(4), 274-293.

[98]. Klose, R. J., & Bird, A. P. (2006). Genomic DNA methylation: the mark and its mediators. Trends in biochemical sciences, 31(2), 89-97.

[99]. Jones, P. A., & Liang, G. (2009). Rethinking how DNA methylation patterns are maintained. Nature Reviews Genetics, 10(11), 805-811.

[100]. Denis, H., Ndlovu, M. N., & Fuks, F. (2011). Regulation of mammalian DNA methyltransferases: a route to new mechanisms. EMBO reports, 12(7), 647-656.

[101]. Lan, J., Hua, S., He, X., & Zhang, Y. (2010). DNA methyltransferases and methyl-binding proteins of mammals. Acta Biochim Biophys Sin, 42(4), 243-252.

[102]. Buryanov, Y. I., & Shevchuk, T. V. (2005). DNA methyltransferases and structural-functional specificity of eukaryotic DNA modification. Biochemistry (Moscow), 70(7), 730-742.

[103]. Zhu, J. K. (2009). Active DNA demethylation mediated by DNA glycosylases. Annual review of genetics, 43, 143-166.

[104]. Li, E. (2002). Chromatin modification and epigenetic reprogramming in mammalian development. Nature Reviews Genetics, 3(9), 662-673.

[105]. Li, E., Bestor, T. H., & Jaenisch, R. (1992). Targeted mutation of the DNA methyltransferase gene results in embryonic lethality. Cell, 69(6), 915-926.

[106]. Okano, M., Bell, D. W., Haber, D. A., & Li, E. (1999). DNA methyltransferases Dnmt3a and Dnmt3b are essential for de novo methylation and mammalian development. Cell, 99(3), 247-257.

[107]. Kareta, M. S., Botello, Z. M., Ennis, J. J., Chou, C., & Chédin, F. (2006). Reconstitution and mechanism of the stimulation of de novo methylation by human DNMT3L. Journal of Biological Chemistry, 281(36), 25893-25902.

[108]. Bourc'his, D., Xu, G. L., Lin, C. S., Bollman, B., & Bestor, T. H. (2001). Dnmt3L and the establishment of maternal genomic imprints. Science, 294(5551), 2536-2539.

[109]. Egger, G., Jeong, S., Escobar, S. G., Cortez, C. C., Li, T. W., Saito, Y., ... & Liang, G. (2006). Identification of DNMT1 (DNA methyltransferase 1) hypomorphs in somatic knockouts suggests an essential role for DNMT1 in cell survival. Proceedings of the National Academy of Sciences, 103(38), 14080-14085.

[110]. Riggs, A. D., & Xiong, Z. (2004). Methylation and epigenetic fidelity. Proceedings of the National Academy of Sciences, 101(1), 4-5.

[111]. Suzuki, M. M., & Bird, A. (2008). DNA methylation landscapes: provocative insights from epigenomics. Nature Reviews Genetics, 9(6), 465-476.

[112]. Feinberg, A. P., Ohlsson, R., & Henikoff, S. (2006). The epigenetic progenitor origin of human cancer. Nature reviews genetics, 7(1), 21-33.

[113]. Cedar, H., & Bergman, Y. (2009). Linking DNA methylation and histone modification: patterns and paradigms. Nature Reviews Genetics, 10(5), 295-304.

[114]. Chi, P., Allis, C. D., & Wang, G. G. (2010). Covalent histone modifications—miswritten, misinterpreted and mis-erased in human cancers. Nature reviews cancer, 10(7), 457-469.

















