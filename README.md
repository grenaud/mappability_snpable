# mappability_snpable

This is a small bash script to run the snpable pipeline http://lh3lh3.users.sourceforge.net/snpable.shtml with minimal disk usage and parallelization.

usage: 

     bash snpable.bash [ref genome] [path to dir to seqbility]
     
seqbility is from lh3_misc from https://github.com/lh3/misc

example:

      bash snpable.bash hg38.fa /storage/software/lh3_misc/seq/seqbility/

requires in path:
* bwa
* samtools
* gzip
* bgzip
* bedtools
