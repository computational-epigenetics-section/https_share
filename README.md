Copy links to
https://genome.ucsc.edu/cgi-bin/hgCustom



##################

wig file from R should be preprocessed to remove spaces and headers
  tail -n +2 chr19_all_pos_bins.wig > chr19_all_pos_bins_1.wig
  sed "s/^[ \t]*//" -i chr19_all_pos_bins_1.wig

variableStep  chrom=chrN
