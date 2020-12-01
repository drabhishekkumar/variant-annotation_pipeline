## extract annovar
tar xvf annovar.latest.tar.gz

perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar refGene humandb/

perl annotate_variation.pl -buildver hg19 -downdb cytoBand humandb/

perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar exac03 humandb/

perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar avsnp147 humandb/

perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar dbnsfp30a humandb/
