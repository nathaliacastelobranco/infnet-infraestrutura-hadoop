# Projeto Infraestrutura Hadoop

- Disciplina: [25E3_2]
- Nathalia Castelo Branco

## Tema

Análise do mercado formal de trabalho no Brasil com base nos dados do CAGED: admissões, desligamentos e saldo de empregos.

## Origem dos dados

[Microdados RAIS CAGED](https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/estatisticas-trabalho/microdados-rais-e-caged)

Os dados foram obtidos via download por FTP, conforme orientação do site: https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/estatisticas-trabalho/microdados-rais-e-caged


## Obtenção dos dados

O processo de ELT foi desenvolvido conforme arquivo `ELT_CAGED_Hadoop.ipynb`. Nele os dados foram baixados via FTP, descompactados, transformados em Parquet e enviados ao Google Cloud Storage. 

Print dos dados armazenados no Bucket na Google Cloud Storage:
![alt text](imagens/bucket-gcs.png)