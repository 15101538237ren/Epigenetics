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

In 1942, Waddington coined the term *epigenetics*, which he defined as changes in phenotype without changes in genotype, to explain aspects of development for which there was little mechanistic understanding [138, 139]. 

The major epigenetic signals include DNA methylation and demethylation, covalent post-translational reversible modifications of the histone proteins, such as acetylation, methylation, phosphorylation and ubiquitination, incorporation of histone variants and gene regulation by non-coding RNAs [88]. 

Epigenetic mechanisms work in addition to the DNA template to stabilize gene expression programmes and thereby canalize cell-type identities [140]. The genetic message is differentially decoded in both time and space as a result of epigenetic constraints on the genome resulting either in gene activation or silencing[85]. 

### Foundation of epigenetics

Pioneering work carried out between 1869 and 1928 by Miescher, Flemming, Kossel and Heitz defined nucleic acids, chromatin and histone proteins, which led to the cytological distinction between **euchromatin** and **heterochromatin** [141] (Fig.3a). This was followed by ground-breaking studies by Muller [142] (in Drosophila melanogaster) and McClintock [143] (in maize) on position-effect variegation (PEV) and transposable elements, providing early hints of non-Mendelian inheritance. Descriptions of the phenomena of X-chromosome inactivation [144] and imprinting [145, 146] subsequently led to the general concept that identical genetic material can be maintained in different **on** versus **off** states in the same nucleus, but its underlying mechanisms were poorly understood. 

![Figure 3](https://github.com/Read-Lab-UCI/Epigenetics/blob/main/Figures/Fig3.png)

<sub>Figure 3. **Euchromatin and heterochromatin**. a | Cytologically visible ground states of active (euchromatic) and repressed (heterochromatic) chromatin. Schematic representation of two interphase nuclei from female mouse somatic cells: the left nucleus displays broad and decondensed staining of unique DNA sequences and the right nucleus shows the characteristic heterochromatic foci (black dots) that are visualized by DAPI (4′,6-diamidino-2-phenylindole) staining of AT-rich repeat sequences. In addition, the densely staining Barr body (an inactive X chromosome (Xi)) at the nuclear periphery is indicated. In the early years, cytologists used various chromatin dyes and DNA-binding fluorochromes to discriminate euchromatic (decondensed and light staining) from heterochromatic (compact and dense staining) regions in eukaryotic chromatin. b | Enzymatic definition of chromatin states that stimulate gene activity (histone acetylation by p55 (also known as Gcn5)) or repress gene activity (histone methy- lation by Su(var)3–9 homologue 1 (SUV39H1)). In 1996, the nuclear histone acetyltransferase (HAT) p55 from Tetrahymena thermophila was described as a transcriptional co-activator that acetylates the histone H3 amino-terminal tail. The acetylated (Ac) lysine on H3 (H3K14ac) provides a docking site for bromodomain (Bromo)-containing accessory proteins that bind to and further stimulate nucleosome accessibility and transcriptional activity. Histone acetylation can be reversed by opposing histone deacetylases (HDACs), which often cause transcriptional repression. In 2000, the human histone lysine methyltransferase (KMT) SUV39H1 was described as an orthologue of a Drosophila melanogaster Su(var) position-effect variegation factor that methylates the histone H3 N-terminal tail. The trimethy- lated H3K9 (H3K9me3) provides a docking site for the chromodomain (Chromo)-containing hetero- chromatin protein 1 (HP1), which then impairs nucleosome accessibility and induces gene repression. The reversibility of histone lysine methylation was not known at that time. (Figure from Ref.[140])</sub>

### Histone modification

#### The finding history of histone modification and related enzymes

In the mid-1960s, pioneering work of Allfrey [159] on histone modifications, in particular histone acetylation, led to the hypothesis that acetylation is closely linked to gene activity [160]. Many studies followed, including studies by Grunstein and others on histone-tail mutations in *Saccharomyces cerevisiae* that perturb gene silencing at telomeres and mating-type loci; this seminal work provided early functional evidence, including the first characterization of silent information regulator proteins [161, 162]. Development of modification- or site-specific antibodies (for example, histone 4 lysine 16 acetylation (H4K16ac)) by Turner and others documented non-random patterns of histone acetylation, such as hypoacetylation of the inactive X chromosome in female mammals [163] or the silent mating type genes in yeast [164], as well as hyperacetylation of the twofold upregulated X chromosome in D. melanogaster males [165] or expressed [166] β-globin genes in chicken red blood cells .These major discoveries made a compelling argument that histone modifications, in addition to DNA methylation, carry information that can distinguish euchromatin from heterochromatin. Powerful genetic screens in flies [167, 168, 169], yeast [170, 171] and plants [168, 172] had identified other key factors for chromatin- dependent gene regulation, such as heterochromatin protein 1 (HP1), Suppressor of variegation 3–9 (Su(var)3–9), Enhancer of zeste (E(z)), Polycomb, Trithorax, cryptic loci regulator 4 (Clr4) and DECREASED DNA METHYLATION 1 (DDM1). 

##### In Euchromatin

In 1996, Allis and colleagues purified and cloned the first histone acetyltransferase(**HAT**) - p55 from *T. thermophila* (Fig.3b) [173]. Strikingly, this ciliate HAT (p55) was an orthologue of the previously described transcriptional coactivator Gcn5 from budding yeast, providing a direct link between histone acetylation and gene activation. Other HATs were identified, including TAF1(TATA-box binding protein associated factor TFIID subunit 1, also known as TAF(II)250) [174], PCAF(p300/CBP-associated factor) [175] and CBP/p300 (CREB-binding protein and p300)[176, 177], thus confirming and extending this paradigm to mammalian cells [178].

Approximately one month after the publication of the p55–Gcn5 HAT results [173], Schreiber and colleagues [179] reported the purification and cloning of the first histone deacetylase (**HDAC**), and it was found to be an orthologue of the budding yeast transcriptional co-repressor Rpd3 (Fig.3b), which indicated that histone deacetylation is linked to transcriptional repression. In 2000, Guarente and colleagues [180] demonstrated that a critical protein required for gene silencing in yeast, Sir2, was a NAD-requiring HDAC (Fig.4). Subsequently, seven Sir2-like enzymes were identified in mammalian cells, which are now known as the Sirtuin protein family. The Sir2-related HDACs triggered much research interest for their functions in metabolism and ageing, which are still under intense investigation today [181].

In 1999, Zhou and colleagues [182] documented the bromodomain from **PCAF** as an acetyl-lysine binding module for docking onto acetylated histones. This was the first histone-modification-binding domain to be described, suggesting a novel mechanism (*trans*-effects) for the binding of bromodomain-containing factors to acetylated targets in chromatin. To date, a multitude of chromatin-binding modules have been described, many in atomic resolution with their cognate modified-histone ligands [178, 183]. 

##### In Heterochromatin

The discovery of the first histone lysine methyltransferase (**KMT**)  containing an evolutionarily conserved SET domain, identified by Reuter [184], and mammalian orthologues cloned and characterized by Jenuwein [185]. The SET domain is present in Su(var)3–9 (Suppressor of variegation 3–9, a histone H3 lysine 9 (H3K9) methylating enzyme), E(z) (Enhancer of zeste, a histone H3 lysine 27 (H3K27) methylating enzyme) and Trithorax (a histone H3 lysine 4 (H3K4) methylating enzyme) proteins, all of which had been implicated in epigenetic regulation without evidence of enzymatic activity.

##### Histone Arginine Methylation

Histone arginine methylation has been associated with gene regulation, as the co-activator CARM1 (coactivator-associated arginine methyltransferase 1)[186] or the PRMT1(protein arginine N-methyltransferase 1) [187] can mediate hormone-dependent transcriptional stimulation via H3R17 [188] or H4R3 methylation [187].

![Figure 4](https://github.com/Read-Lab-UCI/Epigenetics/blob/main/Figures/Fig4.png)

<sub>Figure 4. **Timeline of major discoveries and advances in epigenetic research between 1996 and 2016**. (Figure from Ref.[140])</sub>

#### Introduction of histone modification 

Histone tails undergo a variety of covalent modifications including acetylation, methylation, phosphorylation, ubiquitination, and sumoylation, regulating key cellular process such as gene transcription, DNA replication, and DNA repair [113, 114].

### DNA methylation

#### The finding history of DNA methylation
**DNA methylation** was first discovered in calf thymus DNA by Hotchkiss, in 1948 [96], and a role for DNA methylation, in particular for 5-methylcytosine (5mC), in gene regulation was proposed in the mid-1970s by Holliday and Pugh [147], among others. By 1980, the functional connection between DNA methylation and gene repression was established [148], as was the existence of CpG islands [149]. The first 'epigenetic drug', 5-azacytidine (also known as 2′-deoxy-5-azacytidine and later called decitabine), which blocks DNA methylation, was used to alter gene expression and phenotypes in fibroblast cell lines [150]. Soon thereafter, Feinberg and Vogelstein [151] reported global DNA hypomethylation in cancer and, a decade later, local DNA hypermethylation of tumour suppressor genes was described — findings that were collectively reviewed [152]. These insights gave a compelling reason to pursue the ‘enzymology’ of DNA methylation. The successful purification and cloning of the mouse DNA (cytosine-5)-methyltransferase 1 (DNMT1) enzyme [153, 154] and the generation and analysis of Dnmt1-mutant mice [105] proved important advances towards this goal. During the same time frame, the first DNA-methyl-binding protein, MeCP2 (methyl-CpG-binding protein 2), was identified [155]. DNA methylation and 5mC (considered the ‘fifth base’) had been firmly established as a crucial epigenetic mechanism in many, but not all, organisms.

#### Introduction of DNA methylation

**DNA methylation** is a heritable epigenetic mark involving the covalent transfer of a methyl group to the C-5 position of the cytosine ring of DNA by DNA methyltransferases 1 (DNMTs) [91]. DNA methylation is well conserved among most plant, animal and fungal models[2]. In prokaryotes, DNA methylation takes place on both cytosine and adenine bases and constitutes a branch of the host restriction system to distinguish self and non-self DNA. However in multicellular eukaryotes this modification is limited to cytosine bases only and acts mainly as a repressive tag resulting in silent chromatin state and transcriptional repression [97, 98]. In mammals, DNA methylation occurs at cytosines in any context of the genome. In plants, cytosines are methylated in both symmetrical (CG or CHG) or asymmetrical (CHH, where H is A, T, or C) contexts [95]. However, more than 98% of DNA methylation occurs in a CpG dinucleotide context in somatic cells [3, 4], while as much as a quarter of all methylation appears in a non-CpG context in embryonic stem cells (ESCs) [95]. 

Most DNA methylation is essential for normal development, and it plays a very important role in a number of key processes including genomic imprinting, X-chromosome inactivation, and suppression of repetitive element transcription and transposition and, when dysregulated, contributes to diseases like cancer [91, 92, 93, 94]. It is considered to be one of the first steps in epigenetic regulation, acting as a fundamental mechanism in functional organization of the human genome. It is also an attractive and promising target in the development of new drugs for cancer chemotherapy as epigenetic alterations are, in principle, more readily reversible than genetic anomalies [88].

### Nucleosome positioning

Studies by many groups led to the widely accepted model of nucleosomal organization of chromatin [156], which was first articulated in a provocative theory — the chromatin subunit model — put forward in 1974 [157] and visualized by the landmark X-ray crystal structure of the histone octamer–DNA particle in 1997 [158]. As was shown, the basic unit of the chromatin fibre is the nucleosome core particle, which is composed of two copies each of four histone proteins (a histone octamer) that package 147 bp of DNA.

### Non-coding RNA

### 3D chromatin structure



### Fundamental questions in Epigenetics

- What are the roles of the epigenetic marks?
- How are they coordinated in normal development and disrupted in disease?


## Molecular Mechanisms of Epigenetics

### Mechanisms of DNA Methylation


#### Enzymes of DNA methylation

Methylation of DNA is a post synthetic process catalyzed by a family of dedicated enzymes known as DNA by DNMTs(DNA methyltransferases). DNMT1, DNMT3A and DNMT3B methylate the cytosine residue in the presence of cofactor SAM (S-Adenosyl methionine), which donates the –CH3 group and is converted to SAH (S-Adenosyl homocysteine) [86, 101]. 

It has been widely believed that DNMT1 acts mainly as a *maintenance* methyltransferase during DNA synthesis and that DNMT3A and DNMT3B act as *de novo* enzymes in development. However, mounting evidence indicates that DNMT1 may also be required for de novo methylation of genomic DNA19 and that DNMT3A and DNMT3B contribute to maintenance methylation during replication [109, 110].

- DNMT1

**DNMT1** preferentially methylates hemi-methylated DNA *in vitro* and is localized to replication foci during S phase.

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
specific histone modifications appear to reciprocally influence each other in deposition: histone methylation may direct DNA methylation patterns  (Fig.1), and DNA methylation may serve as a template for the establishment of certain histone modifications (Fig.2) after DNA replication [113].

![Figure 1](https://github.com/Read-Lab-UCI/Epigenetics/blob/main/Figures/Fig1.png)

<sub>Figure 1. **How the histone code may direct DNA methylation during development and carcinogenesis**. (A) During normal development, the transcriptionally activating mark H3K4 me3 (x) blocks or repels DNMTs, whereas the repressive marks H3K9me or H3K27me (y) permit or recruit
DNMTs, possibly by direct protein-protein interactions (e.g., EZH2-DNMTs). During carcinogenesis, disruption of the histone code in the form of (B) loss of H3K4me3 (x), (C) substitution of H3K4me3 with H3K9me or H3K27me (y), randomization of marks, aberrant acquisition of a new mark (z), or (D) loss of all histone marks permits or actively induces DNMT recruitment. x = H3K4me3; y = H3K9me or H3K27me; z = other histone mark; bent arrow = transcription start site; lollipops = histone marks; black circles = DNA methylation. (Figure from Ref.[89])</sub>

There is also evidence that DNA methylation directs **H3K9me2/3**, although this remains controversial. Hypomorphic mutation of **DNMT1** gene causes a global reduction of **H3K9me2/3** levels in a cancer cell line; re-expression of DNMT1 rescues this phenotype [128, 129]. Dnmt1 and Dnmt3b double knockout in colon cancer cells induces changes in H3K9 methylation levels at heterochromatin and specific tumor suppressor loci [130]. Triple knockout (TKO) of Dnmt1/Dnmt3a/Dnmt3b in ESCs results in complete loss of DNA methylation at several repetitive sequences and imprinted genes [131]; however, TKO ES cells retain occupancy of H3K9 methylation and HP-1 in pericentromeric regions [131]. The link between DNA methylation and H3K9 methylation is via interaction of the enzymes mediating these marks.  DNMT1, for example, directly binds G9A both *in vivo* and *in vitro*, and these two proteins colocalize in H3K9 methylation at replication foci during DNA replication. Depletion of DNMT1 not only impairs DNA methylation but also retards G9A loading and H3K9 methylation on chromatin and rDNA repeats [128]. Similarly, heterochromatic colocalization of SUV39H1 and DNMT1 exists exclusively before cell division.

![Figure 2](https://github.com/Read-Lab-UCI/Epigenetics/blob/main/Figures/Fig2.png)

<sub>Figure 2. **How the histone code may rely on the DNA methylation machinery for direction**. Upon binding to CpG-rich regions, DNMTs may directly recruit HMTs to these domains. During DNA replication, UHRF1 preferentially binds hemimethylated DNA and interacts with/ recruits DNMT1 and G9A. **PCNA** may also have a role in the recruitment process. Methyl-CpG– binding proteins (**MBDs**) specifically interact with methylated DNA and may form complexes with HMTs such as SETDB1 to direct histone methylation to regions of DNA methylation.(Figure from Ref.[89])</sub>

Yet an additional link between DNA methylation and the histone code exists via the methyl-CpG–binding proteins (**MBDs**), which interact specifically with methylated DNA and mediate transcriptional repression (Fig.2). During replication of DNA methylation-rich regions of the genome, **CAF1** forms a complex with **MBD1** and the histone lysine methyltransferase **SETDB1**, thereby coupling histone methylation with DNA methylation [125]. **MBD1** deletion suggest that H3K9 methylation mediated by **SETDB1** is dependent on **MBD1**, which recruits **SETDB1** to **CAF1** at active replication forks [132].

The two global mechanisms of gene regulation, DNA methylation and histone deacetylation, are also linked via the methyl-CpG– binding protein **MeCP2**. **MeCP2** binds tightly to chromosomes in a DNA methylation–dependent manner. It contains a transcriptional-repression domain (TRD) that functions at a distance *in vitro* and *in vivo*, and **MeCP2** associates with a corepressor complex containing histone deacetylases [133].


- ##### In Heterochromatin

**H3K9me3**, **H3K27me3** and **H4K20me3** has been suggested to be a prerequisite for subsequent DNA methylation, which appears to be attributable to physical associations between the components of these histone methylation systems and one or more DNMTs (Fig.1). In the context of H3K9 and H3K27, the relevant histone lysine methyltransferases, **SUV39H1/2** and **EZH2**, respectively, interact directly with **DNMT1, DNMT3A, and DNMT3B** [115, 116].  Pericentromeric localization of DNMT3B depends on **SUV39H1/2**-mediated H3K9 dimethylation or trimethylation [115]. **SUV39H1/2** double-null murine embryonic stem cells display reduced DNA methylation levels at major satellite repeats but not at minor satellites or endogenous C-type retroviral elements [116]. Endogenous DNMT1 and DNMT3A also associate with H3K9 methyltransferase SUV39H1 activity as well, mediated by the conserved PHD-like motif in the case of DNMT3A [117].

The binding of **HP1** to constitutive heterochromatin depends on the enzymatic activity of **SUV39H1/2**, which catalyze **H3K9me3** [122], while **HP1** binding to euchromatin depends on dimethylation of H3K9 mediated by **G9A** [118]. Methylated H3K9 serves as a binding platform for **HP1** to associate with the DNA methylation machinery. HP1 binds directly to the PHD-like motif of DNMT3A *in vitro* [117]. The direct physical link identified between the DNMTs and the H3K9me-HP1 system therefore ensures that H3K9 methylation directly influences DNA methylation patterns [115, 117].

**HP1**(heterochromatin protein 1) proteins modulate gene transcription in both euchromatin and heterochromatin. **HP1** binds to methylated H3K9 through its N-terminal chromo-domain. HP1 proteins also recruit a variety of other factors including histone deacetylases, transcriptional repressors, and chromatin remodeling enzymes to the methylated region to further enhance and/or stabilize repressive domains [91, 124].

- ##### In Promoter Silencing

**EZH2**, one of the core components of polycomb repressive complex 2 (PRC2), catalyzes **H3K27me3**, which acts subsequently to recruit the PRC1 complex and mediate transcription silencing. EZH2 physically interacts with the DNMTs and facilitates their binding to certain EZH2 target promoters [116]. Overexpression of EZH2 increases CpG methylation, while RNA interference knockdown of EZH2 reduces H3K27 methylation and DNA methylation at known EZH2 target genes [116].

The G9A/GLP heteromeric complex induces both H3K9 and DNA methylation on G9A target loci, and these two epigenetic marks cooperatively suppress transcription of their target genes. Tachibana et al. showed that promoter regions of G9A/GLP target genes are DNA hypomethylated in G9a or Glp knockout ESCs [118].

Histone arginine methylation has also been linked to DNA methylation and gene silencing [119]. Symmetric dimethylation of histone H4 arginine 3
(H4R3me2s), catalyzed by PRMT5, serves as a direct binding target for
DNMT3A, which may then induce methylation of adjacent CpG dinucleotides at PRMT5 target genes [119].

Direct interactions between HP1 and DNMT1 mediate silencing of euchromatic genes [123]. Silencing of the survivin gene coincides with recruitment of G9A and HP1 in DNMT1 wild-type but not DNMT1-null cells [123]. Binding of GAL4-HP1 to a reporter construct is sufficient to induce repression and DNA methylation in DNMT1 wild-type but not DNMT1-null cells [123].

In addition to the direct recruitment of DNMTs, histone methyltransferases and demethylases may also influence the stability of DNMT proteins [120]. **SET7**, a known histone methyltransferase for H3K4, colocalizes with DNMT1 and methylates DNMT1 at the K142 position to regulate its stability and degradation. Overexpression of **SET7** leads to decreased DNMT1 levels, and siRNA-mediated knockdown of **SET7** stabilizes DNMT1 [120]. Lysine-specific demethylase 1 (**LSD1**) has been shown to demethylate histone H3K4 and H3K9. **LSD1** also demethylates DNMT1 methylated at K142 to antagonize the effect of **SET7** [121].

#### Links between DNA Methylation & Nucleosome Positioning

Chromatin, rather than naked DNA, is the substrate for all processes that affect genes and chromosomes. Nucleosomes form the fundamental repeating unit of eukaryotic chromatin, serving as the basic module for DNA packaging that regulates the accessibility of DNA to interacting proteins and alters transcriptional states [189]. 

Studies have revealed that nucleosomal DNA is an important substrate for the DNMTs [190, 191]. Genome-wide nucleosome positioning analysis in human cells showed that **DNA methylation is enriched in nucleosome-bound DNA rather than linker DNA**, indicating that nucleosome-bound DNA is a preferred substrate for DNA methylation [191]. Jeong et al reported that **DNMT3A** and **DNMT3B** are strongly anchored to nucleosomes, whereas **DNMT1** interacts primarily with linker DNA [190]. Deletion experiments demonstrated that the N-terminal region of DNMT3A and DNMT3B, which contains PWWP and PHD-like motifs, plays an essential role in their strong nucleosomal binding [190]. **DNMT3A** was recently shown to specifically bind the **H3K36me3** mark through its **PWWP** domain, which is important for the subnuclear localization of DNMT3A and suggested that nucleosomal binding of DNMT3A and DNMT3B might, at least in part, be mediated by its interaction with **H3K36me3** [192]. Surprisingly, some well-known chromatin-modifying proteins, such as PCNA, HP1, MBD2, EZH2, HDAC1, and UHRF1, are not required for DNMT3A and DNMT3B to bind to nucleosomes [190]. **SINE and LINE repetitive elements and CGIs in nucleosomes represent the main binding sites of DNMT3A and DNMT3B**, suggesting that additional cues, other than hemimethylated DNA, from the chromatin are needed for inheritance of DNA methylation.

**Nucleosome positioning also has a striking effect on DNA methylation.**  As a linker histone, H1 reduction leads to decreases in nucleosome repeat length, which is a primary determinant of nucleosome spacing [193]. Interestingly, depletion of histone H1 induces DNA hypomethylation of specific CGIs such as the imprinting control regions of the H19-Igf2 and Gtl2-Dlk1 loci [193].

Nucleosome positioning displays a sequence preference characterized by particular dinucleotides, tending to occur periodically throughout the nucleosome with 10-bp periodicity [198]. This sequence preference might arise from the near-circular wrapping of the nucleosomal DNA, which requires sharp bending every helical repeat (10 bp) [198, 199]. DNMTs enter the major groove to access and methylate the cytosine on the outside of the nucleosome (minor groove). As nucleosome-bound DNA shows a 10-bp periodicity in its CG, CHG, and CHH methylation, nucleosomes appear to dictate access to the DNA and therefore set the register of methylation for all DNA methyltransferases. 


**It is well known that the composition of the nucleosome core particle influences chromatin structure and nucleosome positioning.** Emerging evidence has revealed that replacement of the core histones with variants of histone H2A or H3 represents another potential means of gene regulation [194, 195, 196, 197]. The histone H2A variant **H2A.Z** is excluded from regions of methylated DNA, and **H2A.Z** enrichment varies inversely with transcription within gene bodies, a finding conserved from plants to animals, indicating that H2A.Z incorporation may contribute to transcriptional activation by protecting genes against DNA methylation [196]. 


Recent genome-wide studies have revealed that nucleosomes are significantly more enriched in exons compared to introns, consistent with other recent findings of enhanced exonic methylation of gene bodies [200].


## Gene Regulation of Epigenetics

### DNA Methylation

DNA methylation obstructs transcriptional activity via two general schemes. First, methylated cytosine bases can hinder the interaction of transcriptional factors and RNA polymerase II with their cognate DNA recognition sequences. Second, methyl-CpG-binding proteins, such as MBD (methyl-CpG-binding domain) proteins, associate with methylated DNA and result in heterochromatin formation by recruiting **HDACs** (histone deacetylases) [98, 102].

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

CHIP-seq of **CFP1** identified a notable concordance between unmethylated CGIs and **H3K4me3** in the mouse brain [134]. Levels of **H3K4me3** at CGIs are markedly reduced in **CFP1**-depleted cells, consistent with the finding that CFP1 associates with the H3K4 methyltransferase **SETD1**. 

**DNMT3L** recognizes histone H3 tails that are unmethylated at lysine 4 and may therefore induce *de novo* DNA methylation by recruitment and activation of DNMT3A2 [37], and this interaction was strongly inhibited
by methylation of H3K4 but was insensitive to modifications at other positions. **H3K4 methylation may protect certain loci from DNA methylation**.

In mammals, there are at least 10 known or predicted H3K4 methyltransferases, which are generally categorized into the **MLL** (mixed lineage leukemia) family, **SET1** family, and others [135]. Disruption of the **SET** domain of **MLL** reduced H3K4me1 levels and increased DNA methylation levels at specific loci (e.g., Hoxd4) but not globally in a mouse model [136]. However, forced overexpression of exogenous **MLL** in **MLL** knockout cells did not reduce global DNA methylation levels [137].

It is therefore possible that DNA methylation represents a default state of the genome unless H3K4me, or possibly other histone marks, is present to maintain specific regions (e.g., promoters) free of DNA methylation to permit proper gene regulation (Fig.2).

### Epigenetics in CpG island

DNA methylation–free CGIs recruit CFP1, and probably other CXXC domain– containing proteins as well, to stimulate methylation of H3K4. Densely methylated CGIs, on the other hand, attract methyl-CpG–binding proteins, which in turn recruit enzymes that reinforce repressive histone marks. CpG islands(CGIs), which are known to recruit Trithorax (TrxG) and Polycomb group proteins.


### Epigenetics in Enhancer

### Epigenetics in Gene Body

Bulk of evidence suggests that it is associated with gene activation, and it has been noted in a range of cell and tissue types, and in both plants and animals [203, 204, 205, 206, 207]. Zemach et al analyzed DNA methylation patterns in 17 eukaryotic genomes and showed that gene body methylation is conserved between plants and animals [197].

A few theories have been proposed to explain how intragenic methylation promotes gene expression. One suggests that intragenic methylation represses transcription of the antisense sequence, which may interfere with the expression of the sense gene [111, 208]. An alternative theory proposes that intragenic methylation increases transcriptional efficiency through the repression of **cryptic** promoters, which are normally silenced promoters found within genes [209]. Experimental evidence supported the repression of **cryptic** promoters hypothesis came from [210].

Experimentally imposed gene body methylation of an integrated transgene revealed that methylation impaired elongation of transcription *in vivo* [201].

![Figure 5](https://github.com/Read-Lab-UCI/Epigenetics/blob/main/Figures/Fig5.png)

<sub>Figure 5. **Intragenic DNA methylation is associated with highly expressed genes**. When unmethylated, RNA polymerase II may begin transcription at cryptic promoters. This activity may reduce the transcriptional efficiency of the gene product (Part A). Therefore, intragenic methylation at cryptic promoters may improve transcriptional efficiency (Part B). TSS, transcription start site; RNA pol II, RNA polymerase II.. (Figure from Ref.[211])</sub>

## Maintenance of Epigenetics

There is no obvious template, like the hemi-methylated CpGs in DNA methylation, for nucleosome reassembly after replication. **PCNA** (proliferating cell nuclear antigen), present at replication forks, plays a very important role both in DNA synthesis, as the polymerase processivity factor, and in the inheritance of epigenetic marks, which may act as a guide for other epigenetic modifications [125]. **PCNA** recruits a variety of epigenetic regulators such as the histone modifiers **HDACs** and SETD8, chromatin remodeler SMARCA5, and chromatin assembly factor 1 (**CAF1**) [125]. 

### The maintenance of DNA methylation

The maintenance of DNA methylation at the replication fork is likely ensured by the DNMT1-PCNA and/or DNMT1-UHRF1 interactions. While disruption of the DNMT1-PCNA interaction does little to alter genomic DNA methylation levels, disruption of the DNMT1-UHRF1 interaction results in massive genomic hypomethylation [126], suggesting that **UHRF1 is the key player coordinating with DNMT1 to maintain DNA methylation patterns after DNA replication**. 

**UHRF1** preferentially binds to hemimethylated DNA, interacts with **DNMT1**, and is required for **DNMT1** localization to replicating heterochromatic regions [10, 12]. In addition, **UHRF1** specifically interacts with peptides that are methylated at H3K9 *in vitro* [125, 127], and it resides in a complex with **HDACs** and **G9A** [10]. Therefore, in addition to binding hemimethylated DNA, **UHRF1** appears to interpret the local histone environment, thereby creating a feedback mechanism that involves the mutual reinforcement of histone and DNA methylation marks.

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

### Dynamics of Epigenetics in Aging

### Epigenetics, Stem Cells and Cellular Differentiation

### Dynamics of Epigenetics in Development

The genomic methylation blueprint is created during two developmental periods—in germ cells and pre-implantation embryos—generating cells with broad developmental potential [99, 100]. Three conserved enzymes, DNA methyltransferase 1 (DNMT1), DNMT3A and DNMT3B, are responsible for its deposition and maintenance and are essential for normal development [5,6].This system of establishing de novo methylation pattern where new methyl marks are added to previously unmethylated cytosines is mainly chaperoned by the de novo methyltransferases DNMT3A and DNMT3B. Maintenance methylation by DNMT1 then ensures that hemi-methylated daughter strands in somatic differentiated cells get methylated to faithfully propagate the proper DNA methylation patterns across successive cell generations [100]. DNA methylation is typically removed (DNA demethylation) during zygote formation, which is essential for cells to return to a pluripotent state, and then re-established in the embryo at approximately the time of implantation [103]. 

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

[9]. Chuang, L. S. H., Ian, H. I., Koh, T. W., Ng, H. H., Xu, G., & Li, B. F. (1997). Human DNA-(cytosine-5) methyltransferase-**PCNA** complex as a target for p21WAF1. *Science*, *277*(5334), 1996-2000.

[10]. Sharif, J., Muto, M., Takebayashi, S. I., Suetake, I., Iwamatsu, A., Endo, T. A., … & Tajima, S. (2007). The SRA protein Np95 mediates epigenetic inheritance by recruiting Dnmt1 to methylated DNA. *Nature*, *450*(7171), 908-912.

[11]. Bostick, M., Kim, J. K., Estève, P. O., Clark, A., Pradhan, S., & Jacobsen, S. E. (2007). UHRF1 plays a role in maintaining DNA methylation in mammalian cells. *Science*, *317*(5845), 1760-1764.

[12]. Arita, K., Ariyoshi, M., Tochio, H., Nakamura, Y., & Shirakawa, M. (2008). Recognition of hemi-methylated DNA by the SRA protein UHRF1 by a base-flipping mechanism. *Nature*, *455*(7214), 818-821.

[13]. Avvakumov, G. V., Walker, J. R., Xue, S., Li, Y., Duan, S., Bronner, C., … & Dhe-Paganon, S. (2008). Structural basis for recognition of hemi-methylated DNA by the SRA domain of human UHRF1. *Nature*, *455*(7214), 822-825.

[14]. Moldovan, G. L., Pfander, B., & Jentsch, S. (2007). **PCNA**, the maestro of the replication fork. *Cell*, *129*(4), 665-679.

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

[58]. Karimi, M. M., Goyal, P., Maksakova, I. A., Bilenky, M., Leung, D., Tang, J. X., … & Lorincz, M. C. (2011). DNA methylation and SETDB1***H3K9me3** regulate predominantly distinct sets of genes, retroelements, and chimeric transcripts in mESCs. *Cell stem cell*, *8*(6), 676-687.

[59]. Leung, D. C., Dong, K. B., Maksakova, I. A., Goyal, P., Appanah, R., Lee, S., … & Rossi, F. (2011). Lysine methyltransferase G9a is required for de novo DNA methylation and the establishment, but not the maintenance, of proviral silencing. *Proceedings of the National Academy of Sciences*, *108*(14), 5718-5723.

[60]. Ooi, S. K., Wolf, D., Hartung, O., Agarwal, S., Daley, G. Q., Goff, S. P., & Bestor, T. H. (2010). Dynamic instability of genomic methylation patterns in pluripotent stem cells. *Epigenetics & chromatin*, *3*(1), 17.

[61]. Muotri, A. R., Marchetto, M. C., Coufal, N. G., Oefner, R., Yeo, G., Nakashima, K., & Gage, F. H. (2010). L1 retrotransposition in neurons is modulated by **MeCP2**. *Nature*, *468*(7322), 443-446.

[62]. Jones, P. L., Veenstra, G. C. J., Wade, P. A., Vermaak, D., Kass, S. U., Landsberger, N., … & Wolffe, A. P. (1998). Methylated DNA and **MeCP2** recruit histone deacetylase to repress transcription. *Nature genetics*, *19*(2), 187-191.

[63]. Nan, X., Ng, H. H., Johnson, C. A., Laherty, C. D., Turner, B. M., Eisenman, R. N., & Bird, A. (1998). Transcriptional repression by the methyl-CpG-binding protein **MeCP2** involves a histone deacetylase complex. *Nature*, *393*(6683), 386-389.

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

[74]. Lin, I. G., Han, L., Taghva, A., O’Brien, L. E., & Hsieh, C. L. (2002). Murine de novo methyltransferase Dnmt3a demonstrates strand asymmetry and site preference in the methylation of DNA *in vitro*. *Molecular and cellular biology*, *22*(3), 704-723.

[75]. Handa, V., & Jeltsch, A. (2005). Profound flanking sequence preference of Dnmt3a and Dnmt3b mammalian DNA methyltransferases shape the human epigenome. *Journal of molecular biology*, *348*(5), 1103-1112.

[76]. Wienholz, B. L., Kareta, M. S., Moarefi, A. H., Gordon, C. A., Ginno, P. A., & Chédin, F. (2010). DNMT3L modulates significant and distinct flanking sequence preference for DNA methylation by DNMT3A and DNMT3B *in vivo*. *PLoS Genet*, *6*(9), e1001106.

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

[115]. Lehnertz, B., Ueda, Y., Derijck, A. A., Braunschweig, U., Perez-Burgos, L., Kubicek, S., ... & Peters, A. H. (2003). Suv39h-mediated histone H3 lysine 9 methylation directs DNA methylation to major satellite repeats at pericentric heterochromatin. Current Biology, 13(14), 1192-1200.

[116]. Viré, E., Brenner, C., Deplus, R., Blanchon, L., Fraga, M., Didelot, C., ... & Bollen, M. (2006). The Polycomb group protein EZH2 directly controls DNA methylation. Nature, 439(7078), 871-874.

[117]. Fuks, F., Hurd, P. J., Deplus, R., & Kouzarides, T. (2003). The DNA methyltransferases associate with HP1 and the SUV39H1 histone methyltransferase. Nucleic acids research, 31(9), 2305-2312.

[118]. Tachibana, M., Matsumura, Y., Fukuda, M., Kimura, H., & Shinkai, Y. (2008). G9a/GLP complexes independently mediate H3K9 and DNA methylation to silence transcription. The EMBO journal, 27(20), 2681-2690.

[119]. Zhao, Q., Rank, G., Tan, Y. T., Li, H., Moritz, R. L., Simpson, R. J., ... & Cunningham, J. M. (2009). PRMT5-mediated methylation of histone H4R3 recruits DNMT3A, coupling histone and DNA methylation in gene silencing. Nature structural & molecular biology, 16(3), 304.

[120]. Estève, P. O., Chin, H. G., Benner, J., Feehery, G. R., Samaranayake, M., Horwitz, G. A., ... & Pradhan, S. (2009). Regulation of DNMT1 stability through SET7-mediated lysine methylation in mammalian cells. Proceedings of the National Academy of Sciences, 106(13), 5076-5081.

[121]. Wang, J., Hevi, S., Kurash, J. K., Lei, H., Gay, F., Bajko, J., ... & Gaudet, F. (2009). The lysine demethylase LSD1 (KDM1) is required for maintenance of global DNA methylation. Nature genetics, 41(1), 125-129.

[122]. Cheutin, T., McNairn, A. J., Jenuwein, T., Gilbert, D. M., Singh, P. B., & Misteli, T. (2003). Maintenance of stable heterochromatin domains by dynamic HP1 binding. Science, 299(5607), 721-725.

[123]. Smallwood, A., Estève, P. O., Pradhan, S., & Carey, M. (2007). Functional cooperation between HP1 and DNMT1 mediates gene silencing. Genes & development, 21(10), 1169-1178.

[124]. Maison, Christèle, and Geneviève Almouzni. "HP1 and the dynamics of heterochromatin maintenance." Nature reviews Molecular cell biology 5.4 (2004): 296-305.

[125]. Probst, A. V., Dunleavy, E., & Almouzni, G. (2009). Epigenetic inheritance during the cell cycle. Nature reviews Molecular cell biology, 10(3), 192-206.

[126]. Hervouet, E., Lalier, L., Debien, E., Cheray, M., Geairon, A., Rogniaux, H., ... & Cartron, P. F. (2010). Disruption of Dnmt1/PCNA/UHRF1 interactions promotes tumorigenesis from human and mice glial cells. PloS one, 5(6), e11333.

[127]. Karagianni, P., Amazit, L., Qin, J., & Wong, J. (2008). ICBP90, a novel methyl K9 H3 binding protein linking protein ubiquitination with heterochromatin formation. Molecular and cellular biology, 28(2), 705-717.

[128]. Estève, P. O., Chin, H. G., Smallwood, A., Feehery, G. R., Gangisetty, O., Karpf, A. R., ... & Pradhan, S. (2006). Direct interaction between DNMT1 and G9a coordinates DNA and histone methylation during replication. Genes & development, 20(22), 3089-3103.

[129]. Ikegami, K., Ohgane, J., Tanaka, S., Yagi, S., & Shiota, K. (2009). Interplay between DNA methylation, histone modification and chromatin remodeling in stem cells and during development. International Journal of Developmental Biology, 53(2-3), 203-214.

[130]. Bachman, K. E., Park, B. H., Rhee, I., Rajagopalan, H., Herman, J. G., Baylin, S. B., ... & Vogelstein, B. (2003). Histone modifications and silencing prior to DNA methylation of a tumor suppressor gene. Cancer cell, 3(1), 89-95.

[131]. Tsumura, A., Hayakawa, T., Kumaki, Y., Takebayashi, S. I., Sakaue, M., Matsuoka, C., ... & Nakayama, J. I. (2006). Maintenance of self‐renewal ability of mouse embryonic stem cells in the absence of DNA methyltransferases Dnmt1, Dnmt3a and Dnmt3b. Genes to Cells, 11(7), 805-814.

[132]. Sarraf, S. A., & Stancheva, I. (2004). RETRACTED: Methyl-CpG Binding Protein MBD1 Couples Histone H3 Methylation at Lysine 9 by SETDB1 to DNA Replication and Chromatin Assembly.

[133]. Nan, X., Ng, H. H., Johnson, C. A., Laherty, C. D., Turner, B. M., Eisenman, R. N., & Bird, A. (1998). Transcriptional repression by the methyl-CpG-binding protein MeCP2 involves a histone deacetylase complex. Nature, 393(6683), 386-389.

[134]. Lee, J. H., & Skalnik, D. G. (2002). CpG-binding protein is a nuclear matrix-and euchromatin-associated protein localized to nuclear speckles containing human trithorax Identification of nuclear matrix targeting signals. Journal of Biological Chemistry, 277(44), 42259-42267.

[135]. Ruthenburg, A. J., Allis, C. D., & Wysocka, J. (2007). Methylation of lysine 4 on histone H3: intricacy of writing and reading a single epigenetic mark. Molecular cell, 25(1), 15-30.

[136]. Terranova, R., Agherbi, H., Boned, A., Meresse, S., & Djabali, M. (2006). Histone and DNA methylation defects at Hox genes in mice expressing a SET domain-truncated form of Mll. Proceedings of the National Academy of Sciences, 103(17), 6629-6634.

[137]. Milne, T. A., Briggs, S. D., Brock, H. W., Martin, M. E., Gibbs, D., Allis, C. D., & Hess, J. L. (2002). MLL targets SET domain methyltransferase activity to Hox gene promoters. Molecular cell, 10(5), 1107-1117.

[138]. Waddington, C. H. (2012). The epigenotype. International journal of epidemiology, 41(1), 10-13.

[139]. Waddington, C. H. (1942). Canalization of development and the inheritance of acquired characters. Nature, 150(3811), 563-565.

[140]. Allis, C. D., & Jenuwein, T. (2016). The molecular hallmarks of epigenetic control. Nature Reviews Genetics, 17(8), 487.

[141]. Heitz, E. (1928). Das heterochromatin der moose. Bornträger.

[142]. Muller, H. J., & Altenburg, E. (1930). The frequency of translocations produced by X-rays in Drosophila. Genetics, 15(4), 283.

[143]. McClintock, B. (1951, January). Chromosome organization and genic expression. In Cold Spring Harbor symposia on quantitative biology (Vol. 16, pp. 13-47). Cold Spring Harbor Laboratory Press.

[144]. Mf, L. (1961). Gene action in the X chromosome of the mouse. Nature, 190, 372-373.

[145]. Surani, M. A. H., Barton, S. C., & Norris, M. L. (1984). Development of reconstituted mouse eggs suggests imprinting of the genome during gametogenesis. Nature, 308(5959), 548-550.

[146]. McGrath, J., & Solter, D. (1984). Completion of mouse embryogenesis requires both the maternal and paternal genomes. Cell, 37(1), 179-183.

[147]. Holliday, R., & Pugh, J. E. (1975). DNA modification mechanisms and gene activity during development. Science, 187(4173), 226-232.

[148]. Razin, A., & Riggs, A. D. (1980). DNA methylation and gene function. Science, 210(4470), 604-610.

[149]. Bird, A., Taggart, M., Frommer, M., Miller, O. J., & Macleod, D. (1985). A fraction of the mouse genome that is derived from islands of nonmethylated, CpG-rich DNA. Cell, 40(1), 91-99.

[150]. Taylor, S. M., & Jones, P. A. (1979). Multiple new phenotypes induced in 10T12 and 3T3 cells treated with 5-azacytidine. Cell, 17(4), 771-779.

[151]. Feinberg, A. P., & Vogelstein, B. (1983). Hypomethylation distinguishes genes of some human cancers from their normal counterparts. Nature, 301(5895), 89-92.

[152]. Feinberg, A. P., & Tycko, B. (2004). The history of cancer epigenetics. Nature Reviews Cancer, 4(2), 143-153.

[153]. Gruenbaum, Y., Cedar, H., & Razin, A. (1982). Substrate and sequence specificity of a eukaryotic DNA methylase. Nature, 295(5850), 620-622.

[154]. Bestor, T. H., & Ingram, V. M. (1983). Two DNA methyltransferases from murine erythroleukemia cells: purification, sequence specificity, and mode of interaction with DNA. Proceedings of the National Academy of Sciences, 80(18), 5559-5563.

[155]. Meehan, R. R., Lewis, J. D., McKay, S., Kleiner, E. L., & Bird, A. P. (1989). Identification of a mammalian protein that binds specifically to DNA containing methylated CpGs. Cell, 58(3), 499-507.

[156]. Olins, D. E., & Olins, A. L. (2003). Chromatin history: our view from the bridge. Nature reviews Molecular cell biology, 4(10), 809-814.

[157]. Kornberg, R. D. (1974). Chromatin structure: a repeating unit of histones and DNA. Science, 184(4139), 868-871.

[158]. Luger, K., Mäder, A. W., Richmond, R. K., Sargent, D. F., & Richmond, T. J. (1997). Crystal structure of the nucleosome core particle at 2.8 Å resolution. Nature, 389(6648), 251-260.

[159]. Allfrey, V. G., Faulkner, R., & Mirsky, A. E. (1964). Acetylation and methylation of histones and their possible role in the regulation of RNA synthesis. Proceedings of the National Academy of Sciences of the United States of America, 51(5), 786.

[160]. Verdin, E., & Ott, M. (2015). 50 years of protein acetylation: from gene regulation to epigenetics, metabolism and beyond. Nature reviews Molecular cell biology, 16(4), 258-264.

[161]. Kayne, P. S., Kim, U. J., Han, M., Mullen, J. R., Yoshizaki, F., & Grunstein, M. (1988). Extremely conserved histone H4 N terminus is dispensable for growth but essential for repressing the silent mating loci in yeast. Cell, 55(1), 27-39.

[162]. Megee, P. C., Morgan, B. A., Mittman, B. A., & Smith, M. M. (1990). Genetic analysis of histone H4: essential role of lysines subject to reversible acetylation. Science, 247(4944), 841-845.

[163]. Jeppesen, P., & Turner, B. M. (1993). The inactive X chromosome in female mammals is distinguished by a lack of histone H4 acetylation, a cytogenetic marker for gene expression. Cell, 74(2), 281-289.

[164]. Braunstein, M., Sobel, R. E., Allis, C. D., Turner, B. M., & Broach, J. R. (1996). Efficient transcriptional silencing in Saccharomyces cerevisiae requires a heterochromatin histone acetylation pattern. Molecular and Cellular Biology, 16(8), 4349-4356.

[165]. Bone, J. R., Lavender, J., Richman, R., Palmer, M. J., Turner, B. M., & Kuroda, M. I. (1994). Acetylated histone H4 on the male X chromosome is associated with dosage compensation in Drosophila. Genes & development, 8(1), 96-104.

[166]. Hebbes, T. R., Clayton, A. L., Thorne, A. W., & Crane‐Robinson, C. (1994). Core histone hyperacetylation co‐maps with generalized DNase I sensitivity in the chicken beta‐globin chromosomal domain. The EMBO journal, 13(8), 1823-1830.

[167]. Elgin, S. C., & Reuter, G. (2013). Position-effect variegation, heterochromatin formation, and gene silencing in Drosophila. Cold Spring Harbor perspectives in biology, 5(8), a017780.

[168]. Grossniklaus, U., & Paro, R. (2014). Transcriptional silencing by polycomb-group proteins. Cold Spring Harbor perspectives in biology, 6(11), a019331.

[169]. Kingston, R. E., & Tamkun, J. W. (2014). Transcriptional regulation by trithorax-group proteins. Cold Spring Harbor perspectives in biology, 6(10), a019349.

[170]. Grunstein, M., & Gasser, S. M. (2013). Epigenetics in Saccharomyces cerevisiae. Cold Spring Harbor perspectives in biology, 5(7), a017491.

[171]. Allshire, R. C., & Ekwall, K. (2015). Epigenetic regulation of chromatin states in Schizosaccharomyces pombe. Cold Spring Harbor perspectives in biology, 7(7), a018770.

[172]. Pikaard, C. S., & Scheid, O. M. (2014). Epigenetic regulation in plants. Cold Spring Harbor perspectives in biology, 6(12), a019315.

[173]. Brownell, J. E., Zhou, J., Ranalli, T., Kobayashi, R., Edmondson, D. G., Roth, S. Y., & Allis, C. D. (1996). Tetrahymena histone acetyltransferase A: a homolog to yeast Gcn5p linking histone acetylation to gene activation. Cell, 84(6), 843-851.

[174]. Mizzen, C. A., Yang, X. J., Kokubo, T., Brownell, J. E., Bannister, A. J., Owen-Hughes, T., ... & Nakatani, Y. (1996). The TAFII250 subunit of TFIID has histone acetyltransferase activity. Cell, 87(7), 1261-1270.

[175]. Yang, X. J., Ogryzko, V. V., Nishikawa, J. I., Howard, B. H., & Nakatani, Y. (1996). A p300/CBP-associated factor that competes with the adenoviral oncoprotein E1A. Nature, 382(6589), 319-324.

[176]. Ogryzko, V. V., Schiltz, R. L., Russanova, V., Howard, B. H., & Nakatani, Y. (1996). The transcriptional coactivators p300 and CBP are histone acetyltransferases. Cell, 87(5), 953-959.

[177]. Bannister, A. J., & Kouzarides, T. (1996). The CBP co-activator is a histone acetyltransferase. Nature, 384(6610), 641-643.

[178]. Marmorstein, R., & Zhou, M. M. (2014). Writers and readers of histone acetylation: structure, mechanism, and inhibition. Cold Spring Harbor perspectives in biology, 6(7), a018762.

[179]. Taunton, J., Hassig, C. A., & Schreiber, S. L. (1996). A mammalian histone deacetylase related to the yeast transcriptional regulator Rpd3p. Science, 272(5260), 408-411.

[180]. Imai, S. I., Armstrong, C. M., Kaeberlein, M., & Guarente, L. (2000). Transcriptional silencing and longevity protein Sir2 is an NAD-dependent histone deacetylase. Nature, 403(6771), 795-800.

[181]. Berger, S. L., & Sassone-Corsi, P. (2016). Metabolic signaling to chromatin. Cold Spring Harbor perspectives in biology, 8(11), a019463.

[182]. Dhalluin, C., Carlson, J. E., Zeng, L., He, C., Aggarwal, A. K., & Zhou, M. M. (1999). Structure and ligand of a histone acetyltransferase bromodomain. Nature, 399(6735), 491-496.

[183]. Patel, D. J. (2016). A structural perspective on readout of epigenetic histone and DNA methylation marks. Cold Spring Harbor perspectives in biology, 8(3), a018754.

[184]. Tschiersch, B., Hofmann, A., Krauss, V., Dorn, R., Korge, G., & Reuter, G. (1994). The protein encoded by the Drosophila position‐effect variegation suppressor gene Su (var) 3‐9 combines domains of antagonistic regulators of homeotic gene complexes. The EMBO journal, 13(16), 3822-3831.

[185]. Aagaard, L., Laible, G., Selenko, P., Schmid, M., Dorn, R., Schotta, G., ... & Reuter, G. (1999). Functional mammalian homologues of the Drosophila PEV‐modifier Su (var) 3‐9 encode centromere‐associated proteins which complex with the heterochromatin component M31. The EMBO journal, 18(7), 1923-1938.

[186]. Chen, D., Ma, H., Hong, H., Koh, S. S., Huang, S. M., Schurter, B. T., ... & Stallcup, M. R. (1999). Regulation of transcription by a protein methyltransferase. Science, 284(5423), 2174-2177.

[187]. Wang, H., Huang, Z. Q., Xia, L., Feng, Q., Erdjument-Bromage, H., Strahl, B. D., ... & Zhang, Y. (2001). Methylation of histone H4 at arginine 3 facilitating transcriptional activation by nuclear hormone receptor. Science, 293(5531), 853-857.

[188]. Bauer, U. M., Daujat, S., Nielsen, S. J., Nightingale, K., & Kouzarides, T. (2002). Methylation at arginine 17 of histone H3 is linked to gene activation. EMBO reports, 3(1), 39-44.

[189]. Jiang, C., & Pugh, B. F. (2009). Nucleosome positioning and gene regulation: advances through genomics. Nature Reviews Genetics, 10(3), 161-172.

[190]. Jeong, S., Liang, G., Sharma, S., Lin, J. C., Choi, S. H., Han, H., ... & Jones, P. A. (2009). Selective anchoring of DNA methyltransferases 3A and 3B to nucleosomes containing methylated DNA. Molecular and cellular biology, 29(19), 5366-5376.

[191]. Chodavarapu, R. K., Feng, S., Bernatavichute, Y. V., Chen, P. Y., Stroud, H., Yu, Y., ... & Casero, D. (2010). Relationship between nucleosome positioning and DNA methylation. Nature, 466(7304), 388-392.

[192]. Dhayalan, A., Rajavelu, A., Rathert, P., Tamas, R., Jurkowska, R. Z., Ragozin, S., & Jeltsch, A. (2010). The Dnmt3a PWWP domain reads histone 3 lysine 36 trimethylation and guides DNA methylation. Journal of Biological Chemistry, 285(34), 26114-26120.

[193]. Fan, Y., Nikitina, T., Zhao, J., Fleury, T. J., Bhattacharyya, R., Bouhassira, E. E., ... & Skoultchi, A. I. (2005). Histone H1 depletion in mammals alters global chromatin structure but causes specific changes in gene regulation. Cell, 123(7), 1199-1212.

[194]. Raisner, R. M., Hartley, P. D., Meneghini, M. D., Bao, M. Z., Liu, C. L., Schreiber, S. L., ... & Madhani, H. D. (2005). Histone variant H2A. Z marks the 5′ ends of both active and inactive genes in euchromatin. Cell, 123(2), 233-248.

[195]. Malik, H. S., & Henikoff, S. (2003). Phylogenomics of the nucleosome. Nature structural & molecular biology, 10(11), 882-891.

[196]. Zilberman, D., Coleman-Derr, D., Ballinger, T., & Henikoff, S. (2008). Histone H2A. Z and DNA methylation are mutually antagonistic chromatin marks. Nature, 456(7218), 125-129.

[197]. Zemach, A., McDaniel, I. E., Silva, P., & Zilberman, D. (2010). Genome-wide evolutionary analysis of eukaryotic DNA methylation. Science, 328(5980), 916-919.

[198]. Widom, J. (2001). Role of DNA sequence in nucleosome stability and dynamics. Quarterly reviews of biophysics, 34(3), 269.

[199]. Segal, E., & Widom, J. (2009). What controls nucleosome positions?. Trends in Genetics, 25(8), 335-343.

[200]. Schwartz, S., Meshorer, E., & Ast, G. (2009). Chromatin organization marks exon-intron structure. Nature structural & molecular biology, 16(9), 990.

[201]. Lorincz, M. C., Dickerson, D. R., Schmitt, M., & Groudine, M. (2004). Intragenic DNA methylation alters chromatin structure and elongation efficiency in mammalian cells. Nature structural & molecular biology, 11(11), 1068-1075.

[202]. Feng, S., Cokus, S. J., Zhang, X., Chen, P. Y., Bostick, M., Goll, M. G., ... & Ukomadu, C. (2010). Conservation and divergence of methylation patterning in plants and animals. Proceedings of the National Academy of Sciences, 107(19), 8689-8694.

[203]. Jjingo, D., Conley, A. B., Soojin, V. Y., Lunyak, V. V., & Jordan, I. K. (2012). On the presence and role of human gene-body DNA methylation. Oncotarget, 3(4), 462.

[204]. Rauch, T. A., Wu, X., Zhong, X., Riggs, A. D., & Pfeifer, G. P. (2009). A human B cell methylome at 100− base pair resolution. Proceedings of the National Academy of Sciences, 106(3), 671-678.

[205]. Smith, F. M., Garfield, A. S., & Ward, A. (2006). Regulation of growth and metabolism by imprinted genes. Cytogenetic and genome research, 113(1-4), 279-291.

[206]. Aran, D., Toperoff, G., Rosenberg, M., & Hellman, A. (2011). Replication timing-related and gene body-specific methylation of active human genes. Human molecular genetics, 20(4), 670-680.

[207]. Baubec, T., Colombo, D. F., Wirbelauer, C., Schmidt, J., Burger, L., Krebs, A. R., ... & Schübeler, D. (2015). Genomic profiling of DNA methyltransferases reveals a role for DNMT3B in genic methylation. Nature, 520(7546), 243-247.

[208]. Tran, R. K., Henikoff, J. G., Zilberman, D., Ditt, R. F., Jacobsen, S. E., & Henikoff, S. (2005). DNA methylation profiling identifies CG methylation clusters in Arabidopsis genes. Current Biology, 15(2), 154-159.

[209]. Shenker, N., & Flanagan, J. M. (2012). Intragenic DNA methylation: implications of this epigenetic mechanism for cancer research. British journal of cancer, 106(2), 248-253.

[210]. Maunakea, A. K., Nagarajan, R. P., Bilenky, M., Ballinger, T. J., D’Souza, C., Fouse, S. D., ... & Turecki, G. (2010). Conserved role of intragenic DNA methylation in regulating alternative promoters. Nature, 466(7303), 253-257.

[211]. Bommarito, P. A., & Fry, R. C. (2019). The Role of DNA Methylation in Gene Regulation. In Toxicoepigenetics (pp. 127-151). Academic Press.








