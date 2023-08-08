---
output:
  word_document: default
  html_document: default
---
# Spontaneous-helping-in-pigs

This repository contains data and source code to reproduce the data and statistical analysis and figures of the article published in the journal "Proceedings of the Royal Society B":

Spontaneous helping in pigs is mediated by helper's social attention and distress signals of individuals in need
by Liza R. Moscovice, Anja Eggert, Christian Manteuffel and Jean-Loup Rault

Research Institute for Farm Animal Biology (FBN), Dummerstorf, Germany 

The published article is available online at the following permanent link: https://dx.doi.org/10.1098/rspb.2023.0665.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

In order to reference this software, please consider the information in the [CITATION.cff](CITATION.cff) file.

## Usage

We run the data and statistical analysis on Windows 10.

1. THE REPOSITORY CONTAINS:
  * Folder *data* with 10 csv-files:
    + `Fig-2-latency-condition.csv`
    + `Fig-3-helping-window-time.csv`
    + `Fig-4-survival-distress.csv`
    + `Fig-S2-proportion-familiarization.csv`
    + `Fig-S3-latency-familiarization.csv`
    + `Fig-S4-latency-trials.csv`
    + `Fig-S5-likelihood-condition.csv`
    + `Fig-S6-cortisol-helper-trapped.csv`
    + `Fig-S7-cortisol-trapped-pigs.csv`
    + `Table-S2-side-preference-box.csv`
  * Folder *code* with corresponding 10 Quarto-Markdown and rendered HTML files:
    + `Fig-2-latency-condition.qmd`
    + `Fig-3-helping-window-time.qmd`
    + `Fig-4-survival-distress.qmd`
    + `Fig-S2-proportion-familiarization.qmd`
    + `Fig-S3-latency-familiarization.qmd`
    + `Fig-S4-latency-trials.qmd`
    + `Fig-S5-likelihood-condition.qmd`
    + `Fig-S6-cortisol-helper-trapped.qmd`
    + `Fig-S7-cortisol-trapped-pigs.qmd`
    + `Table-S2-side-preference-box.qmd`
2. TABLES
    + Table 1: Results of LMM predicting the influence of condition (separation/test trial) and identity of compartment (empty/test compartment) on the latency for pigs to first open a door (*latency-condition*)
    + Table 2: Results of a zero-inflated negative binomial model predicting the likelihood of helping (*helping-window-time*)
    + Table 3: Results of a survival analysis predicting the likelihood and latency for trapped pigs to be helped (*survival-distress*)
    + Table S1: Results of LMM predicting latency to open a door on familiarization days based on box location (*latency-familiarization*)
    + Table S2: Results of binomial test to test for side preference for a box (*side-preference-box*)
    + Table S3: Results of binomial GLMM to test for differences in likelihood of opening door in different conditions (*likelihood-condition*)
    + Table S4: Results of a LMM predicting how different distress signals relate to changes in salivary cortisol in trapped pigs (*cortisol-trapped-pigs*)
3. FIGURES
    + Figure 1: Schematic drawing
    + Figure 2. Latency for pigs to first open a door depending on condition (separation/test trial) and identity of compartment (empty/test compartment) (*latency-condition*)
    + Figure 3: Relationship between each potential helper’s social attention to the trapped pig and their likelihood of helping (*helping-window-time*)
    + Figure 4: Survival curve showing the probability for trapped pigs (n = 58) to be helped by another group member (*survival-distress*)
    + Figure S1: Foto of the test compartment
    + Figure S2: Proportion of pigs who successfully opened a door across familiarization (*proportion-familiarization*)
    + Figure S3: Daily latency for a door to be opened within each group during familiarization and based on box location (*latency-familiarization*)
    + Figure S4: Latency for helper pigs to release trapped pigs across trials within each group (*latency-trials*)
    + Figure S5: Likelihood of opening door in different conditions (*likelihood-condition*)
    + Figure S6: Comparison of post-release salivary cortisol concentrations in trapped pigs and their helpers (*cortisol-helper-trapped*)
    + Figure S7: Comparison of changes in salivary cortisol concentrations in pigs depending on distress signals while trapped (*cortisol-trapped-pigs*)
  
