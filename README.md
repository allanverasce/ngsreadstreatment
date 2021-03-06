# NGSReadsTreatment
<p align="justify">The Next-Generation Sequencing (NGS) platforms provide a major approach to obtaining millions of short reads from samples. NGS has been used in a wide range of analyses, such as for determining genome sequences, analyzing evolutionary processes, identifying gene expression and resolving metagenomic analyses. Usually, the quality of NGS data impacts the final study conclusions. Moreover, quality assessment is generally considered the first step in data analyses to ensure the use of only reliable reads for further studies. In NGS platforms, the presence of duplicated reads (redundancy) that are usually introduced during library sequencing is a major issue. These might have a serious impact on research application, as redundancies in reads can lead to difficulties in subsequent analysis (e.g., de novo genome assembly). Herein, we present NGSReadsTreatment, a computational tool for the removal of duplicated reads in paired-end or single-end datasets. NGSReadsTreatment can handle reads from any platform with the same or different sequence lengths. Using the probabilistic structure Cuckoo Filter, the redundant reads are identified and removed by comparing the reads with themselves. Thus, no prerequisite is required beyond the set of reads. NGSReadsTreatment was compared with other redundancy removal tools in analyzing different sets of reads. The results demonstrated that NGSReadsTreatment was better than the other tools in both the amount of redundancies removed and the use of computational memory for all analyses performed.</p>

# Article available in:
  https://www.nature.com/articles/s41598-019-48242-w

# Execution
### Graphical interface

    java -jar NgsReadsTreatmentGI.jar

### Command line

    java -jar NgsReadsTreatment.jar PATH Single-end.fastq

    java -jar NgsReadsTreatment.jar PATH Paired_tag1.fastq  PATH Paired_tag2.fastq


