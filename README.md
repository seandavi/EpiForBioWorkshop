# Epidemiology for Bioinformaticians

# Instructor(s) name(s) and contact information

Chloe Mirzayi, cmirzayi@gmail.com
Levi Waldron, levi.waldron@sph.cuny.edu
CUNY School of Public Health, 55 W 125th St, New York, NY 111027

# Workshop Description

Concepts of causal inference in epidemiology have important ramifications for studies across bioinformatics and other fields of health research. In this workship, we introduce basic concepts of epidemiology, study design, and causal inference for bioinformaticians. Emphasis is placed on addressing bias and confounding as common threats to assessing a causal pathway in a variety of study design types and when using common forms of analyses such as GWAS and survival analysis. Workshop participants will have the opportunity to create their own structural causal models (DAGs) and use this model to determine how to assess an estimated causal effect. Examples using DESeq2, edgeR, and limma will be used to show how multivariable models can be fitted depending on the hypothesized causal relationship. 

## Pre-requisites

List any workshop prerequisites, for example:

* Basic knowledge of R syntax
* Familiarity with regression

## Workshop Participation

Students will have the opportunity to solve toy problems and execute example code in R.

## _R_ / _Bioconductor_ packages used

* daggity
* DESeq2
* edgeR
* limma

## Time outline

An example for a 45-minute workshop:

| Activity                     | Time |
|------------------------------|------|
| Counterfactuals              | 15m  |
| Causal Inference	       | 5m   |
| Bias and Confounding	       | 5m   |
| Causal Inference in R        | 10m  |
| Toy Problems	               | 10m  |

# Workshop goals and objectives

## Learning goals

* Describe the differences in common experimental and observational study designs
* Apply concepts of study design to common analyses in bioinformatics such as GWAS and survival analysis
* Understand key concepts of epidemiology such as causal inference, confounders, collidors, mediators, counterfactuals, and study designs
* Develop a structural causal diagram/directed acyclic graph (DAG) of causal relationships and assess pathways of interest
* Recognize the limitations and assumptions of multivariable regression in observational studies, and how this affects common analyses such as DESeq2, edgeR, and limma

## Learning objectives

* Assess a study design in terms of causal inference
* Learn about path blocking to prevent confounding
* Create a DAG in R using daggity
* Identify situations when multivariate adjustment for variables is inappropriate
* Select the correct model formula/matrix in DESeq2, edgeR, or limma to deconfound
