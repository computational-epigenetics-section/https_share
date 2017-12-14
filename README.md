# Visualize chr19 in UCSC browser

https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr19%3A14609817-14699486&hgsid=647818717_tqiuvEG19A6YGvdCjui75ZPyDNUe


https share files
## Candidate MEs:
https://github.com/computational-epigenetics-section/https_share/raw/master/chr19_bigwig.bw

## Positive Bins with 20% Range
https://github.com/computational-epigenetics-section/https_share/raw/master/chr19_all_pos_bins.bigwig.bw

## All informative bins
https://github.com/computational-epigenetics-section/https_share/raw/master/chr19_all_bins.bigwig.bw


Copy this link to
https://genome.ucsc.edu/cgi-bin/hgCustom

MEs idendentified by Co1_Co2 data in CNTD2, GOLGA2P9 genes at 

chr19:40,222,208-40,227,095
chr19:22,596,257-22,603,550

wig file from R should be preprocessed to remove spaces and headers
  tail -n +2 chr19_all_pos_bins.wig > chr19_all_pos_bins_1.wig
  sed "s/^[ \t]*//" -i chr19_all_pos_bins_1.wig

variableStep  chrom=chrN
