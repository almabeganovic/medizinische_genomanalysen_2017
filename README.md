# Medizinische Genomanalysen 2017
Material and information about the lecture "Medizinische Genomanalysen"

## Overview
* Fork & clone the repository of each assignment
* Each student is given an individual assignment to work on
* When done, commit and push the results to your github repository
* All assignments need to be completed by **01.04.2017**
* Review process takes place from 02.04.2017 01.05.2017
* Each student needs to review all three assignments of two other students
* Send the review reports (2 students, 3 assignments each) latest on **01.05.2017** to <br/>
email: stephan 'dot' pabinger 'at' ait 'dot' ac 'dot' at<br/>
subject: Medizinische Genomanalysen 2017 - Peer Review<br/>
filetype: PDF<br/>
length: **5-10 sentences** per assignment<br/>
checks: correct assignment, working code, correct results, documentation

## Data and packages for Python assignments
#### Data
* BAM file: ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/phase3/data/HG00096/alignment/HG00096.chrom11.ILLUMINA.bwa.GBR.low_coverage.20120522.bam 
* VCF file:
ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/analysis/IonTorrent_TVC_03162015/AmpliseqExome.20141120.NA24385.vcf
* VCF file: 
ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/analysis/IonTorrent_TVC_03162015/AmpliseqExome.20141120.NA24143.vcf
* VCF file:
ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/analysis/IonTorrent_TVC_03162015/AmpliseqExome.20141120.NA24149.vcf
  
#### Packages
* Biopython (http://biopython.org/)
* pybedtools (https://daler.github.io/pybedtools/)
* NCBI (http://biopython.org/DIST/docs/api/Bio.Entrez-module.html)
* pybam (https://github.com/JohnLonginotto/pybam)
* pysam (http://pysam.readthedocs.io/en/latest/usage.html)
* cyvcf2 (https://github.com/brentp/cyvcf2)
* pyvcf (http://pyvcf.readthedocs.io/en/latest/)
* HGVS - does only work with Python2! (https://hgvs.readthedocs.io/en/master/)


## Assignment 1
Repository: [medizinische_genomanalysen_2017_assignment_1](https://github.com/spabinger/medizinische_genomanalysen_2017_assignment_1)

## Assignment 2
Repository: [medizinische_genomanalysen_2017_assignment_2](https://github.com/spabinger/medizinische_genomanalysen_2017_assignment_2)

## Assignment 3
Repository: [medizinische_genomanalysen_2017_assignment_3](https://github.com/spabinger/medizinische_genomanalysen_2017_assignment_3)


## Peer Review - students

| Student | Reviewed by | 
| ----- | --- |
| Basílio	José | Gutsohn, Moser | 
| Beganovic	Alma | Brauneis, Basílio | 
| Bindeus	Alexander | Beganovic, Tolios | 
| Brauneis	Shelley | Tolios, Tomaselli | 
| Buchner	Bianca Allegra | Majewski, Juno | 
| Gollobich	Martin | Lang, Lehrach | 
| Gutsohn	Tamás | Gollobich, Buchner | 
| Juno	Claudia | Spielvogel, Brauneis | 
| Lang	Priska | Juno, Gutsohn | 
| Lehrach	Michael | Buchner, Beganovic | 
| Majewski	Anna | Ruge, Lehrach | 
| Moser	Josef | Gollobich, Bindeus | 
| Ruge	Frank | Basílio, Lang | 
| Spielvogel	Clemens | Tomaselli, Ruge | 
| Tolios	Alexander | Moser, Majewski | 
| Tomaselli	Anna | Bindeus, Spielvogel | 


## Student projects

### Exercise - Clinical sequencing

#### Your TOODs
1. Perform 6 analysis steps (if possible) using FASTQ files 
2. Per group present the selected software and analysis results (07.01.2015) 
   * Software: 10min 
   * Performed analysis: 10min

#### Peform the following steps 
1. Data Import – take FASTQ files from:
   * Illumina:  ftp://ftp.1000genomes.ebi.ac.uk/vol1/ftp/phase3/data
   * Ion Torrent: (Only for Ion Reporter)  ftp://ftp-trace.ncbi.nih.gov/giab/ftp/data/AshkenazimTrio/HG002_NA24385_son/ion_exome/
   * Requirement: human, genome (no RNASeq, methylation, …)
2. Quality Control & QC Report 
3. Mapping 
4. Variant Calling (SNV, Indel) 
5. Variant Annotation 
6. Interpretation & Decision Making 

#### Student groups 
1. Illumina basespace  --  https://basespace.illumina.com/home/index 
   * Moser
   * Basílio
   * Tolios
   * Ruge
2. Ion Reporter  --  https://ionreporter.lifetechnologies.com/ir/ 
   * Tomaselli 
   * Bindeus
   * Gollobich
3. Galaxy  --  https://main.g2.bx.psu.edu/ 
   * Gutsohn
   * Buchner
   * Lehrach
4. Chipster  --  http://chipster.csc.fi/ 
   * Brauneis
   * Juno
   * Beganovic
   * Majewski
5. GenePattern  --  https://genepattern.broadinstitute.org/gp
   * Schwarz
   * Lang
   * Spielvogel










