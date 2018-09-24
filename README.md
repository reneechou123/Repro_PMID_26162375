# Repro_26162375
Reproducing Drosophila anti-nematode and antibacterial immune regulators revealed by RNA-Seq

1. get public key and log on to AWS
2. download and install sratoolkit from NCBI
3. download datasets ( control and one of gegative samples from GEO )
      SRR1574318(sample) and SRR1573961(control)
      command line:
          sratoolkit.2.9.2-centos_linux64/bin/fastq-dump -I --split-files -O datasets --gzip SRR1574318     
     
4. download install bioconda 
    install bowtie, tophat, samtools, htseq, cufflinks, R, python, DESeq 
       command line:
          conda install htseq
          conda install cufflinks
          conda install r
          conda install bioconductor-deseq
5. download genome gtf file and fasta file




