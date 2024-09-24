# RIP-Seq_pipeline
A RIP-Seq pipeline

## Software requirement
- hisat2
- samtools
- stringtie
- htseq
- HOMER (for peak annotation)
## Pipeline workflow
![image](https://github.com/maxuying1218/RIP-Seq_pipeline/blob/main/workflow.png)

## Usage
```
sh RIPSeq_pipline.sh fq_r1 fq_r2 out_dir out_label ht2_index cpu gtf
```
Here is an example of a figure using the results from this pipeline:  
![image](https://github.com/maxuying1218/RIP-Seq_pipeline/blob/main/Peak_Annotation.jpg)

## Note
If your genome is not in HOMER database, you should create your own HOMER data like this:  
```
loadGenome.pl -gtf  genome.gtf  -name genome -fasta genome.fa  -org species_name
```
