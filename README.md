### Hi there 👋I am trying to make STAR index using the following command line. The run was started, but, the following messages was shown:
/usr/bin/STAR: line 7:  3184 Killed                  "${cmd}" "$@".



STAR --runMode genomeGenerate --genomeDir /mnt/c/desktop/Bioinformatic/STAR_Index --genomeFastaFiles /mnt/c/desktop/Bioinformatic/Genome_seq/GRCh38_latest_genomic.fna --sjdbGTFfile /mnt/c/desktop/Bioinformatic/Genome_seq/GRCh38_latest_genomic.gff --sjdbOverhang 102
        /usr/lib/rna-star/bin/STAR-avx2 --runMode genomeGenerate --genomeDir /mnt/c/desktop/Bioinformatic/STAR_Index --genomeFastaFiles /mnt/c/desktop/Bioinformatic/Genome_seq/GRCh38_latest_genomic.fna --sjdbGTFfile /mnt/c/desktop/Bioinformatic/Genome_seq/GRCh38_latest_genomic.gff --sjdbOverhang 102
        STAR version: 2.7.10a   compiled: 2022-01-16T16:35:44+00:00 <place not set in Debian package>
Jan 06 18:12:28 ..... started STAR run
Jan 06 18:12:28 ... starting to generate Genome files
Jan 06 18:17:52 ..... processing annotations GTF
Jan 06 18:33:07 ... starting to sort Suffix Array. This may take a long time...
Jan 06 18:33:14 ... sorting Suffix Array chunks and saving them to disk...
/usr/bin/STAR: line 7:  3184 Killed                  "${cmd}" "$@"

Could anyone help me to solve the issue? Thank you!
