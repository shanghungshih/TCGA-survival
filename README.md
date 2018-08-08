# TCGA-survival
> Using clinical data and molecular level data to predict survival of cancer patients.

### [TCGA Pancancer Survival Prediction](https://www.synapse.org/#!Synapse:syn1710282/wiki/27303)
- - -

### data EDA

| data count | GBM | KIRC | LUSC | OV |
| :--------: | :---: |:-----:| :-----:| :-----: |
|clinical|210|243|121|379|
|mRNA|210|243|121|379|
|miRNA|210|243|121|379|
|CNV|210|243|121|379|
|methylation|210|243|x|379|
|RPPA|x|243|121|379|
|Survival|210|243|121|379|
|data with label|155|150|77|252|
|data without label|55|93|44|127|

- - -

| features count | GBM | KIRC | LUSC | OV |
| :--------: | :---: |:-----:| :-----:| :-----: |
|number of features|43437|38300|21868|43870|
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

- 2018 DL [Prediction of cardiovascular risk factors from retinal fundus photographs via deep learning](https://arxiv.org/abs/1708.09843)
- - -

### [C-index](http://ttdoc.cn/article/652.jhtml)

### [Kaplan-Meier曲線](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_062_1.pdf)

### [Cox model](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_064.pdf)
