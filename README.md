# Objetivo do teste:

## Avaliar o seu conhecimento em Pyspark e boas práticas de programação.
Carregue a base abaixo, aplique os casos e grave a saída em um arquivo .parquet.
Base:

001;José;Anápolis;São Paulo;01-09-1900 <br />
02;Igor;Anápolis;São Paulo;11-09-1977 <br />
3;Leonardo;Anápolis;São Paulo;21-12-2000<br />
04;Humberto;Pato Branco;Rio Grande do Sul;13-11-1964<br />
005;Isaias;Pato Branco;Rio Grande do Sul;07-07-2002<br />
6;Lucas;Taua;Ceará;05-09-1984 <br />

**Schema da base: cod_cliente, Nome, Município, Estado, data de nascimento.**
* [**Caso 1 – Adicionar 1 coluna com um contador sequencial por Município e ordenar por Estado.**](#http://localhost:8888/notebooks/Spark/Teste%20Pyspark.ipynb#Caso-1-%E2%80%93-Adicionar-1-coluna-com-um-contador-sequencial-por-Munic%C3%ADpio-e-ordenar-por-Estado.)
* [**Caso 2 - Adicionar 1 coluna com a Idade em anos e na coluna cod_cliente formatar o campo com 3 posições a esquerda completando com “0”.**](#http://localhost:8888/notebooks/Spark/Teste%20Pyspark.ipynb#Caso-2---Adicionar-1-coluna-com-a-Idade-em-anos-e-na-coluna-cod_cliente-formatar-o-campo-com-3-posi%C3%A7%C3%B5es-a-esquerda-completando-com-%E2%80%9C0%E2%80%9D.)
* [**Caso 3 - Adicionar 1 coluna com a data de atualização, preenchendo com a data do dia da execução e retirar os caracteres especiais do campo Estado.**](#http://localhost:8888/notebooks/Spark/Teste%20Pyspark.ipynb#Caso-3---Adicionar-1-coluna-com-a-data-de-atualiza%C3%A7%C3%A3o,-preenchendo-com-a-data-do-dia-da-execu%C3%A7%C3%A3o-e-retirar-os-caracteres-especiais-do-campo-Estado.)

OBS.: Criei um csv da base 
