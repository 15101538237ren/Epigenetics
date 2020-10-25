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


## Introduction

## Epigeneitics

### Histone modification

### DNA methylation

### Nucleosome positioning

### Non-coding RNA

### 3D chromatin structure


## Molecular Mechanisms of Epigenetics

### Mechanisms of DNA Methylation

### Mechanisms of Histone Modification

### Mechanisms of Nucleosome positioning

### Mechanisms of Non-coding RNA

### Mechanisms of 3D chromatin structure

### Crosstalk between Genomics, Epigenetics and Environmental Cues



## Genomic Landscape of Epigenetics in Somatic Cells

### Landscape in Promoter

#### DNA methylation

#### Histone modification

#### Nucleosome positioning

#### 3D chromatin structure

### Landscape in Enhancer

### Landscape in Gene Body



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



## Epigenetics and Human Disease

### Cancer Epigenetics

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


