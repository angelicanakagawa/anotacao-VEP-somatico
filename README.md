# Pipeline para anotação de variantes somáticas utilizando o Ensembl-VEP

O processo de anotação de variantes consiste na busca de variantes disponíveis em bancos de dados.

O primeiro passo é baixar as bases de dados que serão utilizadas no processo de anotação. 
O banco merged é a junção dos transcritos do refseq e do ensembl.

Baixe o banco de dados homo_sapiens_merged_110_GRCh37.zip

```
aria2c -x 8 https://storage.googleapis.com/puga-reference/homo_sapiens_merged_110_GRCh37.zip
```
