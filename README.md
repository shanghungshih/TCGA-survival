# TCGA-survival
> Using clinical data and molecular level data to predict survival of cancer patients.

### [TCGA Pancancer Survival Prediction](https://www.synapse.org/#!Synapse:syn1710282/wiki/27303)
- - -

### 2014 data

| data count | GBM | KIRC | LUSC | OV |
| :--------: | :---: |:-----:| :-----:| :-----: |
|clinical|210|243|121|379|
|mRNA|210|243|121|379|
|miRNA|210|243|121|379|
|CNV|210|243|121|379|
|methylation|210|243|x|379|
|RPPA|x|243|121|379|
|Survival|210|243|121|379|

- - -

| features count | GBM | KIRC | LUSC | OV |
| :--------: | :---: |:-----:| :-----:| :-----: |
|number of features|43437|38300|21868|43870|
- - -

### 2017 data

| data count | OV | CESC | BLCA | ESCA | PAAD | COAD | BRCA | CHOL | GBM | PCPG | READ | PRAD | THCA | UCS | HNSC | KIRP | DLBC | LIHC | LUSC | KIRC | STAD | SARC | THYM | LGG | SKCM | TGCT | UCEC | ACC|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:|
|Mutation|307 | 304 | 408 | 184 | 178 | 191 | 1093 | 36 | 166 | 179 | 72 | 497 | 501 | 57 | 520 | 290 | 48 | 373 | 501 | 533 | 415 | 262 | 120 | 530 | 103 | 150 | 177 | 79|
|CNVGene|307 | 304 | 408 | 184 | 178 | 191 | 1093 | 36 | 166 | 179 | 72 | 497 | 501 | 57 | 520 | 290 | 48 | 373 | 501 | 533 | 415 | 262 | 120 | 530 | 103 | 150 | 177 | 79|
|CNVArm|307 | 304 | 408 | 184 | 178 | 191 | 1093 | 36 | 166 | 179 | 72 | 497 | 501 | 57 | 520 | 290 | 48 | 373 | 501 | 533 | 415 | 262 | 120 | 530 | 103 | 150 | 177 | 79|
|Protein|307 | 304 | 408 | 184 | 178 | 191 | 1093 | 36 | 166 | 179 | 72 | 497 | 501 | 57 | 520 | 290 | 48 | 373 | 501 | 533 | 415 | 262 | 120 | 530 | 103 | 150 | 177 | 79|
|mRNA|307 | 304 | 408 | 184 | 178 | 191 | 1093 | 36 | 166 | 179 | 72 | 497 | 501 | 57 | 520 | 290 | 48 | 373 | 501 | 533 | 415 | 262 | 120 | 530 | 103 | 150 | 177 | 79|

- - -

### additional TCGA data (大多為 paired data (Normal, Tumor)
- Clinical
- Transcriptome Profiling
- Biospecimen
- Simple Nucleotide Variation（4 kinds of variant callers，Somaticsniper, Mutect, Muse, Varscan）
- Copy Number Variation
- DNA Methylation
- - -

### paper
- 2014 Random forest [Assessing the clinical utility of cancer genomic and proteomic data across tumor types](https://www.nature.com/articles/nbt.2940.pdf)

- 2017 NN [Predicting clinical outcomes from large scale cancer genomic profiles with deep survival models](https://www.nature.com/articles/s41598-017-11817-6.pdf)

- 2018 DL [Prediction of cardiovascular risk factors from retinal fundus photographs via deep learning](https://arxiv.org/pdf/1708.09843)
- - -

### [C-index](http://ttdoc.cn/article/652.jhtml)

### [Kaplan-Meier曲線](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_062_1.pdf)

### [Cox model](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_064.pdf)
