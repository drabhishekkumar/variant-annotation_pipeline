## #extract annovar
tar xvf annovar.latest.tar.gz

#### #build hg38 refGene
perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar refGene humandb/

#### #build hg38 cytoBand
perl annotate_variation.pl -buildver hg38 -downdb cytoBand humandb/

#### #build hg38 exac03
perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar exac03 humandb/

#### #build hg38 avsnp147
perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar avsnp147 humandb/

#### #build hg38 dbnsfp30a
perl annotate_variation.pl -buildver hg38 -downdb -webfrom annovar dbnsfp30a humandb/
