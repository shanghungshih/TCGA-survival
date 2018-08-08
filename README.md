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

clinical: 分期（5年存活率, T, N, M 分期)
 
- 2017 NN [Predicting clinical outcomes from large scale cancer genomic profiles with deep survival models](https://www.nature.com/articles/s41598-017-11817-6.pdf)
- - -

### [C-index](http://ttdoc.cn/article/652.jhtml)
- concordance index 用于生存资料，反映预测模型的区分能力
- C-index在0.5-1之间。0.5为完全不一致，说明该模型没有预测作用；1为完全一致；在0.50-0.70为较低准确度，在0.71-0.90之间为中等准确度，高于0.90则为高准确度
- C = K / M (一致的对子数/有用的对子数)
- 将所有研究对象随机的两两配对，n个研究对象，应该产生Cn2=n*(n-1)/2 个对子数，然后在这么多对子中找到有用的对子数作为分母

### [Kaplan-Meier曲線](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_062_1.pdf)
- 每次發生event（死亡 or 退出計畫），即計算一次
- 目的：可忽略前一時段退出計畫的人
- 前提假設：每一時段不會有大量人退出

### [Cox model](http://biostatdept.cmu.edu.tw/doc/epaper_a/paper/teaching_corner_064.pdf)
- 線性模型
- B * X (係數 x features)

