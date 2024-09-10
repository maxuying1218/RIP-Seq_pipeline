# RIP-Seq_pipeline
A RIP-Seq pipeline

### Software requirement
- hisat2
- stringtie
- htseq
- peakAnnotate(from Weilab)

### Usage
sh RIPSeq_pipline.sh fq_r1 fq_r2 out_dir out_label ht2_index cpu gtf

### Note
peakAnnotate used in this pipeline is customized scripts by Weilab members, which can be found at [peakAnnotate](https://github.com/maxuying1218/ChIP-Seq_pipeline/blob/main/1.perl_scripts_from_Weilab/peakAnnotate).
