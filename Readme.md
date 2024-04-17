# SCiteTweets

<!-- Short Introduction what this repo is about -->

This repository contains multiple datasets and the codes for the work *"Cite-worthiness Detection on Social Media: a Preliminary Study"* published at **NSLP2024**. 

For the CiteWorth dataset, you can obtain it by visiting CiteWorth Git page [GitHub - copenlu/cite-worth: Data and code for the paper &quot;CiteWorth: Cite-Worthiness Detection for Improved Scientific Document Understanding&quot;](https://github.com/copenlu/cite-worth)

<!-- *TODO*: refer to our work before being published (e.g arxiv preprint)

*TODO 2*: give examples of scientific online discourse here, e.g "The **SciTweets** dataset consists of ..." -->

__Table of contents:__

- [Contents of the Repository](#contents-of-the-repository)
  - [Directory Structure](#directory-structure)
- [Publication](#publication)
- [Licensing](#licensing)
- [Contact](#credits)
- [Acknowledgment](#acknowledgment)

## Contents of the Repository

### Directory Structure

=======================<br/>
This repository contains the following directories and files:

1. **Datasets**
   
   1. **train.jsonl** the train dataset of CiteWorth
   2. **test.jsonl** the test dataset of CiteWorth
   3. **val.jsonl** the validation dataset of CiteWorth
   4. **twt_FULL.jsonl** the subset of SciTweets, that we call SCiteTweets

2. **Logistic Regression Experiments.ipynb** code to calculate the performances of the LogisticRegression model in section 4.2, table 4

3. **Scibert & Longformer Experiments.ipnyb** code to calculate the performances of the SciBERT and longformer models in section 4.2, table 4

4. **Readme.md** this file

## Publication:

<!-- TODO: Update with correct information once we uploaded the paper somewhere -->

Please cite the following paper (TBA)

1. *TBA*

```bib
TBA
```

## Licensing

This dataset is published under CC BY 4.0 license. It allows reusers to distribute, remix, adapt, and build upon the material in any medium or format, so long as attribution is given to the creator (https://creativecommons.org/licenses/by/4.0/)

## Contact

Please contact salim.hafid@lirmm.fr or wassim.ammar@lirmm.fr

## Acknowledgment

<!-- TODO: Update with french grant number -->

This work is supported by the AI4Sci grant, co-funded by MESRI (France) and BMBF (Germany, grant 01IS21086) and the French National Research Agency (ANR).
