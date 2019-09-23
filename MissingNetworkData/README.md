
Modeling missing cases and transmission links in networks of extensively drug-resistant tuberculosis in KwaZulu-Natal, South Africa
================

------------------------------------------------------------------------

This repository includes source code for our analysis of missing cases in transmission networks of extensively drug-resistant (XDR) tuberculosis (TB) cases in South Africa.

The models described are run in R using the [EpiModel](https://www.epimodel.org/) software.

![Transmission network of XDR TB in KwaZulu-Natal, South Africa](https://github.com/kbratnelson/tb-ergms/blob/master/MissingNetworkData/Nelson_Fig6.3b.png)

------------------------------------------------------------------------

Abstract
--------

Transmission patterns of drug-resistant tuberculosis (TB) remain poorly understood, despite over half a million incident cases in 2017. Modeling TB transmission networks can provide insight into drivers of transmission, but incomplete sampling of TB cases can pose challenges for inference from individual epidemiologic and molecular data. We assessed the effect of missing cases on a transmission network inferred from Mycobacterium tuberculosis sequencing data on extensively drug-resistant (XDR) TB cases in South Africa. We tested scenarios in which cases were missing at random, differentially by clinical characteristics or by transmission (i.e., cases with many links were under or over-sampled). Under the assumption cases were missing randomly, the mean number of transmissions per case in the complete network needed to be  than 20, far higher than expected, to reproduce the observed network. Instead, the most likely scenario involved undersampling of high-transmitting cases and models provided evidence for superspreading. This is the first study to assess support for different mechanisms of missingness in a TB transmission study, but our results are subject to the distributional assumptions of the network models we used. Transmission studies should consider the potential biases introduced by incomplete sampling and identify specific host, pathogen, or environmental factors contributing to superspreading.

Citation
--------

[Preprint version](https://www.biorxiv.org/content/10.1101/655969v1.full)

