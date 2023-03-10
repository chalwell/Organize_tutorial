Obtained files from the rrnDB located at
https://rrndb.umms.med.umich.edu/static/download/

These are files from version 5.6, released 2019

We automated downloading and extracting the tsv file with wget and unzip

wget -P data/raw/ --no-clobber https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8.tsv.zip
unzip -d data/raw/ data/raw/rrnDB-5.8.tsv.zip
Archive:  data/raw/rrnDB-5.8.tsv.zip

wget -nc -P data/raw/ https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_16S_rRNA.fasta.zip
unzip -n -d data/raw/ data/raw/rrnDB-5.8_16S_rRNA.fasta.zip

wget -nc -P data/raw/ https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_pantaxa_stats_NCBI.tsv.zip
unzip -n -d data/raw/ data/raw/rrnDB-5.8_pantaxa_stats_NCBI.tsv.zip

wget -nc -P data/raw/ https://rrndb.umms.med.umich.edu/static/download/rrnDB-5.8_pantaxa_stats_RDP.tsv.zip 
unzip -n -d data/raw/ data/raw/rrnDB-5.8_pantaxa_stats_RDP.tsv.zip
