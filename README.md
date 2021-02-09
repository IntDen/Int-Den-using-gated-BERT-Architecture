# Int-Den-using-gated-BERT-Architecture
A robust denoising method for removing noises from the text generated from OCR is of utmost importance to improve data quality. We devise a method for different noise corrections from English texts. Proposed a modified Transformer-based encoder-decoder architecture (built on top of BERT model) that uses a gating mechanism to detect types of corrections required and accordingly corrects texts irrespective of the types of noises

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── Intrinsic Evaluation Datasets                 <- Datasets which have been used in the Intrinsic evaluation across baselines and IntDen Model.
    │   └── Extrinsic Evaluation Datasets                 <- Datasets which have been used in the Extrinsic evaluation across baselines and IntDen Model.
    │
    │
    ├── notebooks          
    │   ├── Symspell                 <- Notebook which has been used to generate all the SymSpell result on Intrinsic Dataset.
    │   └── Attentive-Seq2Seq        <- Notebook which has been used to generate all the Attentive-Seq2Seq result on Intrinsic Dataset. 
    │   └── BERT                     <- Notebook which has been used to generate all the BERT result on Intrinsic dataset and Extrinsic dataset.
    │   └── BART                     <- Notebook which has been used to generate all the Attentive-Seq2Seq result on Intrinsic dataset.
    |   └── Int-Den                  <- Notebook which has been used to generate all the Attentive-Seq2Seq result on Intrinsic dataset and Extrinsic dataset
--------


### Datasets
#### Intrinsic evaluation
 - [ ] ALTA 2017
 - [ ] ICDAR 2017 and 2019
 - [ ] IMDB 
 
#### Extrinsic evaluation
 - [ ] WMT14
 - [ ] CNN/DM

### notebooks
#### Intrinsic evaluation
 - [ ] Symspell
 - [ ] Attentive-Seq2Seq
 - [ ] BERT 
 - [ ] BART
 - [ ] Int-Den
 
