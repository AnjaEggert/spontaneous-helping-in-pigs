# Spontaneous-helping-in-pigs

This repository contains data and source code to reproduce the data and statistical analysis and figures in the manuscript:

Spontaneous helping in pigs is mediated by helper’s social attention and distress signals of individuals in need
by Liza R. Moscovice, Anja Eggert, Christian Manteuffel and Jean-Loup Rault

Research Institute for Farm Animal Biology (FBN), Dummerstorf, Germany 

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

In order to reference this software, please consider the information in the [CITATION.cff](CITATION.cff) file.

## Usage

We run the data and statistical analysis on Windows 10.

1. THE REPOSITORY CONTAINS:
  * Folder *data* with 10 csv-files:
    + `cortisol-helper-trapped.csv`
    + `cortisol-trapped-pigs.csv`
    + `helping-window-time.csv`
    + `latency-condition.csv`
    + `latency-familiarization.csv`
    + `latency-trials.csv`
    + `likelihood-condition.csv`
    + `proportion-familiarization.csv`
    + `side-preference-box`
    + `survival-distress.csv`
  * Folder *code* with corresponding 10 Quarto-Markdown and rendered HTML files:
    + `cortisol-helper-trapped.qmd`
    + `cortisol-trapped-pigs.qmd`
    + `helping-window-time.qmd`
    + `latency-condition.qmd`
    + `latency-familiarization.qmd`
    + `latency-trials.qmd`
    + `likelihood-condition.qmd`
    + `proportion-familiarization.qmd`
    + `side-preference-box.qmd`
    + `survival-distress.qmd`
2. TABLES
    + Table 1: Results of LMM predicting the influence of condition (separation/test trial) and identity of compartment (empty/test compartment) on the latency for pigs to first open a door (*latency-condition*)
    + Table 2: Results of a zero-inflated negative binomial model predicting the likelihood of helping (*helping-window-time*)
    + Table 3: Results of a survival analysis predicting the likelihood and latency for trapped pigs to be helped (*survival-distress*)
    + Table S1: Results of LMM predicting latency to open a door on familiarization days based on box location (*latency-familiarization*)
    + Table S2: Results of binomial test to test for side preference for a box (*side-preference-box*)
    + Table S3: Results of binomial GLMM to test for differences in likelihood of opening door in different conditions (*likelihood-condition*)
    + Table S4: Results of a LMM predicting how different distress signals relate to changes in salivary cortisol in trapped pigs (*cortisol-trapped-pigs*)
3. FIGURES
    + Figure 1. Latency for pigs to first open a door depending on condition (separation/test trial) and identity of compartment (empty/test compartment) (*latency-condition*)
    + Figure 2: Relationship between each potential helper’s social attention to the trapped pig and their likelihood of helping (*helping-window-time*)
    + Figure 3: Survival curve showing the probability for trapped pigs (n = 58) to be helped by another group member (*survival-distress*)
    + Figure S1: Schematic drawing
    + Figure S2: Foto of the test compartment
    + Figure S3: Daily latency for a door to be opened within each group during familiarization and based on box location (*latency-familiarization*)
    + Figure S4: Proportion of pigs who successfully opened a door across familiarization (*proportion-familiarization*)
    + Figure S5: Likelihood of opening door in different conditions (*likelihood-condition*)
    + Figure S6: Latency for helper pigs to release trapped pigs across trials within each group (*latency-trials*)
    + Figure S7: Comparison of post-release salivary cortisol concentrations in trapped pigs and their helpers (*cortisol-helper-trapped*)
    + Figure S8: Comparison of changes in salivary cortisol concentrations in pigs depending on distress signals while trapped (*cortisol-trapped-pigs*)
  
