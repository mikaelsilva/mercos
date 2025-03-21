## Teste Engenheiro de Dados

## Visão geral:
- De forma geral, o projeto está divido em:
 - data, contendo os arquivos disponibilzados para o teste;
 - db, contendo o arquivo .db para utilizar com o metabase com um db sqlite;
 - notebook, contendo 3 notebooks, 2 deles (RATEIO_ETAPA_1 e RATEIO_ETAPA_2) sendo responsaveis pelo processamento das bases de lançamentos e metricas para responder, respectivamente, as etapas 1 e 2 do teste. Há outro notebook utilizado para convertor os arquivos .parquet resultados dos dois notebooks em um db sqlite para utilização com o metabase;
 - tables, contendo os arquivos resultados **rateio_etapa1.parquet** e **rateio_etapa2.parquet**
 - img, imagens do metabase

## Imagens da utilização do Docker + Metabase para visualização dos dados

1. ![](/img/1_iniciando_metabase.PNG)
2. Banco conectado, o database.db criado com os resultados do RATEIO_ETAOA_1 e RATEIO_ETAPA_2 ![](/img/2_banco_teste.PNG)
1. ![](/img/3_etapa_1.PNG)
1. ![](/img/4_etapa_2.PNG)

## OBSERVACAO
- Dentro dos notebooks, há prints das tabelas, alguns counts, e algumas informações sobre o que foi feito para as duas etapas do rateio. Foi entendido que seria melhor separar os contextos em dois notebooks, embora com algumas etapas semelhantes, como se trata de informações distintas e algumas lógicas relacionadas a negócios, o contexto ficando separado fica mais fácil de atualizar e realizar ajustes futuros.
