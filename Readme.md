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
  * Folder *data* with 9 csv-files:
    + `cortisol-helper-trapped.csv`
    + `cortisol-trapped-pigs.csv`
    + `distress-window-time.csv`
    + `helping-window-time.csv`
    + `latency-familiarization.csv`
    + `latency-trials.csv`
    + `proportion-familiarization.csv`
    + `reciproc-helping.csv`
    + `survival-distress.csv`
  * Folder *code* with Quarto-Markdown and rendered HTML files:
    + `cortisol-helper-trapped.qmd`
    + `cortisol-trapped-pigs.qmd`
    + `distress-window-time.qmd`
    + `helping-window-time.qmd`
    + `latency-familiarization.qmd`
    + `latency-trials.qmd`
    + `proportion-familiarization.qmd`
    + `reciproc-helping.qmd`
    + `survival-distress.qmd`
2. TABLES
    + Table 1: Results of a zero-inflated negative binomial model predicting the likelihood of helping (*helping-window-time*)
    + Table 2: Results of a survival analysis predicting the likelihood and latency for trapped pigs to be helped (*survival-distress*)
    + Table S1: Results of a zero-inflated negative binomial model testing whether helping behaviour is consistent with reciprocity (*reciproc-helping*)
    + Table S2: Results of a LMM predicting how different behavioral responses relate to changes in salivary cortisol in trapped pigs (*cortisol-trapped-pigs*)
3. FIGURES
    + Figure 1. Schematic drawing
    + Figure 2: Latency for helper pigs to release trapped pigs across trials within each group (*latency-trials*)
    + Figure 3: Relationship between each potential helper’s social attention to the trapped pig and their likelihood of helping (*helping-window-time*)
    + Figure 4: Comparison of post-release salivary cortisol concentrations in trapped pigs and their helpers (*cortisol-helper-trapped*)
    + Figure 5: Survival curve showing the probability for trapped pigs (n = 58) to be helped by another group member (*survival-distress*)
    + Figure S1: Foto of the test compartment
    + Figure S2: Daily latency for a door to be opened within each group during the familiarization (*latency-familiarization*)
    + Figure S3: Proportion of pigs who successfully opened a door across familiarization (*proportion-familiarization*)
    + Figure S4: The probability that potential helpers opened doors for trapped pigs when they had or had not previously been helped by the trapped pig (*reciproc-helping*)
    + Figure S5: Rates of distress signals and investigations to the window per minute trapped (*distress-window-time*)
    + Figure S6: Comparison of changes in salivary cortisol concentrations in pigs depending on distress signals while trapped (*cortisol-trapped-pigs*)
  
