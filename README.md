# Reanalysis_MinION_Grubaugh2019
This repo develops machine learning models to cluster the true and false positive variants called in the MinION experiments in [Grubaugh2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1618-7). 

One author—[Nicholas J. Loman](https://github.com/nickloman/zika-isnv)—from [Grubaugh2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1618-7) published a Github repo showing the process how they classified the true and false positive MinION variants using a logistic regression model. 

My repo here contains two folders. 
1. The first folder starts from the three variants tables taken from [Nicholas J. Loman](https://github.com/nickloman/zika-isnv). The three tables are 
- "BC01.variants.0.03.txt" 
- "BC02.variants.0.03.txt"
- "BC03.variants.0.03.txt"

These three tables were generated by Nicholas J. Loman using the following commands:
- python scripts/freqs.py --snpfreqmin 0.03 BC01.trimmed.sorted.bam refs/ZIKV_REF.fasta > BC01.variants.0.03.txt
- python scripts/freqs.py --snpfreqmin 0.03 BC02.trimmed.sorted.bam refs/ZIKV_REF.fasta > BC02.variants.0.03.txt
- python scripts/freqs.py --snpfreqmin 0.03 BC03.trimmed.sorted.bam refs/ZIKV_REF.fasta > BC03.variants.0.03.txt


2. 

Descriptions are to be updated. At this moment, the notebook Reanalysis_MinION_Grubaugh2019.ipynb describes this work and is self-explanatory. 
