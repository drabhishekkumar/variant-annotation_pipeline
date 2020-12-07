## extract annovar
tar xvf annovar.latest.tar.gz
#### build hg38 refGene
perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar refGene humandb/

perl annotate_variation.pl -buildver hg38 -downdb cytoBand humandb/

perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar exac03 humandb/

perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar avsnp147 humandb/

perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar dbnsfp30a humandb/
