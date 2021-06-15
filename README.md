# Causality Detection in Requirement Artifacts (CiRA)

System behavior is often expressed by causal relations in requirements (e.g. if event 1, then event 2). Automatically extracting this embedded causal knowledge supports not only reasoning about requirements dependencies, but also various automated engineering tasks such as seamless derivation of test cases. However, causality extraction from natural language (NL) is still an open research challenge as existing approaches fail to extract causality with reasonable performance. We understand causality extraction from requirements as a two step problem: First, we need to detect if requirements have causal properties or not, and then we need to understand and extract their causal relations. We developed a tool-supported approach for causality detection (CiRA, standing for Causality in Requirements Artifacts). This constitutes a first step towards causality extraction from NL requirements. Feel free to re-use our code :) 

This repository contains our code and annotated data sets used in our case study:
* The main data is contained in the "annotated data sets" folder.
  - The file "overall.csv" contains all labeled sentences with all features.
  - The other files contain all eligible sentences with one specific feature. Note that all files for features (except "causal") contain only the causal sub sets of the original set, as we only labeled the more specific features of causality for causal sentences.
* The code for our machine-learning and deep-learning approaches at automatic causality detection can be found as Jupyter notebook files in the root folder.
For more details on the paper, see "Automatic Detection of Causality in Requirement Artifacts: the CiRA Approach" at https://arxiv.org/abs/2101.10766
For more details on the project, visit our website containing also a live demo of the DL detection approach at http://www.cira.bth.se/

## Licencing and citation

This work is licensed under CC-BY 4.0 (see the respective licence for details). When referring to the data set or the general project, please respect the authors' attribution as described in the licence. These authors can be referred to as via "Jannik Fischbach et al."

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4954090.svg)](https://doi.org/10.5281/zenodo.4954090)