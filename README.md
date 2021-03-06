# SingleCellDataAnalysis
This repository contains the code used to analyze data in the manuscript __Transcriptional, epigenetic, and functional heterogeneity within common myeloid progenitors__ by Heuston et al., 2022. <br>

Data was analyzed in both R and Python. R workflows can be accessed through the R package, and python workflows are included as jupyter notebooks. 


The data used in this study can be downloaded from the Gene Expression Omnibus as part of the superseries [GEO168260](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE168260): <br>
* [GSE168257](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE168257) - ATAC-Seq data <br>
* [GSE168258](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE168258) - RNA-Seq data <br>
* [GSE168259](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE168259) - scRNA-Seq data <br>

Previously published data from [Heuston et al., 2018](https://doi.org/10.1186/s13072-018-0195-z) can be downloaded from the [ValIdated Systematic IntegratiON](http://usevision.org/) or GEO.

__BULK RNA__
| Dataset | Read1 | Read2 | RSEM_estimation_file |
| ------- | ----- | ----- | -------------------- |
| C2r1 | - | - | - |
| C2r2 | - | - | - |
| C18r1 | - | - | - |
| C18r2 | - | - | - |
| C13r1 | - | - | - |
| C13r2 | - | - | - |
| C10r1 | - | - | - |
| C10r2 | - | - | - |
| LSKr1 | [Read_1](https://www.encodeproject.org/files/ENCFF106GQS/@@download/ENCFF106GQS.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF797ZCH/@@download/ENCFF797ZCH.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF915JTS/@@download/ENCFF915JTS.tsv) |
| LSKr2 | [Read_1](https://www.encodeproject.org/files/ENCFF426QFT/@@download/ENCFF426QFT.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF631HGH/@@download/ENCFF631HGH.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF904ZJC/@@download/ENCFF904ZJC.tsv) |
| CMPr1 | [Read_1](https://www.encodeproject.org/files/ENCFF002DMZ/@@download/ENCFF002DMZ.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF002DNA/@@download/ENCFF002DNA.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF411TDQ/@@download/ENCFF411TDQ.tsv) |
| CMPr2 | [Read_1](https://www.encodeproject.org/files/ENCFF002DNB/@@download/ENCFF002DNB.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF002DNC/@@download/ENCFF002DNC.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF324DGI/@@download/ENCFF324DGI.tsv) |
| GMPr1 | [Read_1](https://www.encodeproject.org/files/ENCFF002DND/@@download/ENCFF002DND.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF002DNE/@@download/ENCFF002DNE.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF952HVD/@@download/ENCFF952HVD.tsv) |
| GMPr2 | [Read_1](https://www.encodeproject.org/files/ENCFF002DNF/@@download/ENCFF002DNF.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF002DNG/@@download/ENCFF002DNG.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF178BJT/@@download/ENCFF178BJT.tsv) |
| ERYr1 | [Read_1](https://www.encodeproject.org/files/ENCFF181RDS/@@download/ENCFF181RDS.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF122RAD/@@download/ENCFF122RAD.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF823EMO/@@download/ENCFF823EMO.tsv) |
| ERYr2 | [Read_1](https://www.encodeproject.org/files/ENCFF198RBJ/@@download/ENCFF198RBJ.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF248DYS/@@download/ENCFF248DYS.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF089BFL/@@download/ENCFF089BFL.tsv) |
| iMkr1 | [Read_1](https://www.encodeproject.org/files/ENCFF993QUE/@@download/ENCFF993QUE.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF349BJM/@@download/ENCFF349BJM.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF553ZBZ/@@download/ENCFF553ZBZ.tsv) |
| iMkr2 | [Read_1](https://www.encodeproject.org/files/ENCFF102BWR/@@download/ENCFF102BWR.fastq.gz) | [Read_2](https://www.encodeproject.org/files/ENCFF235XRM/@@download/ENCFF235XRM.fastq.gz) | [RSEM](https://www.encodeproject.org/files/ENCFF519AGI/@@download/ENCFF519AGI.tsv) |

__BULK ATAC__
| Dataset | BigWig | HOMER_peak_file |
| ------- | ------ | ------ |
| C2r1 | - |  | - |
| C2r2 | - |  | - |
| C18r1 | - |  | - |
| C18r2 | - |  | - |
| C13r1 | - |  | - |
| C13r2 | - |  | - |
| C10r1 | - |  | - |
| C10r2 | - |  | - |
| LSKr1 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255742&format=file&file=GSM4255742%5F987%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255742&format=file&file=GSM4255742%5F987%2Ebed%2Egz) |
| LSKr2 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255743&format=file&file=GSM4255743%5F1196%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255743&format=file&file=GSM4255743%5F1196%2Ebed%2Egz) |
| CMPr1 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255744&format=file&file=GSM4255744%5F842%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255744&format=file&file=GSM4255744%5F842%2Ebed%2Egz) |
| CMPr2 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255745&format=file&file=GSM4255745%5F850%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255745&format=file&file=GSM4255745%5F850%2Ebed%2Egz) |
| GMPr1 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255746&format=file&file=GSM4255746%5F843%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255746&format=file&file=GSM4255746%5F843%2Ebed%2Egz) |
| GMPr2 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255747&format=file&file=GSM4255747%5F851%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255747&format=file&file=GSM4255747%5F851%2Ebed%2Egz) |
| ERYr1 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255752&format=file&file=GSM4255752%5F854%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255752&format=file&file=GSM4255752%5F854%2Ebed%2Egz) |
| ERYr2 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255753&format=file&file=GSM4255753%5F846%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255753&format=file&file=GSM4255753%5F846%2Ebed%2Egz) |
| iMkr1 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255756&format=file&file=GSM4255756%5F848%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255756&format=file&file=GSM4255756%5F848%2Ebed%2Egz) |
| iMkr2 | [BigWig](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255757&format=file&file=GSM4255757%5F856%2Emm10%2Ebw) | [HOMER](https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM4255757&format=file&file=GSM4255757%5F856%2Ebed%2Egz) |