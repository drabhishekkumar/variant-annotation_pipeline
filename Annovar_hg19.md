
## #extract annovar
tar xvf annovar.latest.tar.gz

#### #build hg19 refGene
perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar refGene humandb/

#### #build hg19 cytoBand
perl annotate_variation.pl -buildver hg19 -downdb cytoBand humandb/

#### #build hg19 exac03
perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar exac03 humandb/

#### #build hg19 avsnp147
perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar avsnp147 humandb/

#### #build hg19 dbnsfp30a
perl annotate_variation.pl -buildver hg19 -downdb -webfrom annovar dbnsfp30a humandb/
