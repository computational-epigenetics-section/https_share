Copy links to
https://genome.ucsc.edu/cgi-bin/hgCustom

https://github.com/computational-epigenetics-section/https_share/raw/master/chr19_10_5_4_allbins_bigwig.bw

##################

wig file from R should be preprocessed to remove spaces and headers
  tail -n +2 chr19_all_pos_bins.wig > chr19_all_pos_bins_1.wig
  sed "s/^[ \t]*//" -i chr19_all_pos_bins_1.wig

variableStep  chrom=chrN
