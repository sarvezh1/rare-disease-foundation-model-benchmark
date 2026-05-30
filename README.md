# LGMD Foundation Model Benchmark

## Overview

This project evaluates the ability of DNA and protein foundation models to predict the pathogenicity of genetic variants associated with Limb-Girdle Muscular Dystrophy (LGMD).

The goal is to understand how modern biological foundation models capture disease-relevant information and whether their learned representations can support clinically meaningful variant interpretation.

## Research Motivation

Recent advances in foundation models have enabled large-scale representation learning directly from genomic and protein sequences. Models such as DNABERT, Nucleotide Transformer, HyenaDNA, JanusDNA, HybriDNA, and ProtBERT have demonstrated promising results across a variety of biological tasks.

However, their ability to generalize across disease-associated genes and support rare disease variant interpretation remains incompletely understood.

This project focuses on LGMD-associated genes as a biologically coherent benchmark for evaluating DNA and protein foundation model representations under realistic and leakage-resistant conditions.

## Objectives

* Evaluate DNA foundation models for pathogenicity prediction.
* Evaluate protein foundation models on coding variants.
* Compare learned embeddings across multiple model architectures.
* Assess cross-gene generalization performance.
* Compare foundation model approaches against established variant effect predictors.
* Develop a reproducible benchmarking framework for rare disease genomics.

## Foundation Models Evaluated

### DNA Models

* DNABERT
* Nucleotide Transformer
* HyenaDNA
* JanusDNA
* HybriDNA

### Protein Models

* ProtBERT

## Classification Models

The benchmark evaluates multiple downstream classifiers:

* Logistic Regression
* Random Forest
* XGBoost
* Stacking Ensemble (Random Forest + XGBoost)

## Benchmark Comparisons

Model performance will be compared against established variant interpretation tools including:

* CADD
* REVEL
* SIFT
* PolyPhen-2

## Dataset Design

The project emphasizes biologically meaningful and leakage-resistant evaluation.

Key design principles include:

* LGMD-associated disease genes
* ClinVar-derived pathogenic and benign variants
* Gene-level train/test separation
* Cross-gene generalization assessment
* GRCh38 reference genome
* MANE transcript prioritization
* Reproducible dataset generation workflows

## Planned Analyses

* Pathogenicity classification
* Cross-gene evaluation
* Context length comparison
* Embedding pooling strategies
* Variant-type analysis
* Model calibration assessment
* Per-gene performance analysis

## Current Status

This project is currently under active development.

Completed work includes:

* Research design and benchmark planning
* Disease gene selection
* Dataset strategy development
* Model selection and benchmarking framework design

Current work focuses on:

* Dataset construction
* Variant collection and curation
* Embedding generation workflows
* Model implementation and evaluation

## Research Areas

* Bioinformatics
* Computational Genomics
* Rare Disease Genomics
* Machine Learning for Biology
* DNA Foundation Models
* Protein Language Models
* Variant Interpretation

## Repository Status

The associated manuscript is currently in preparation.

To maintain research integrity and avoid conflicts with ongoing publication efforts, code, datasets, and benchmark results are not yet publicly available. Additional materials may be released following manuscript submission and publication.

## Contact

For questions regarding the project, feel free to reach out through GitHub.
