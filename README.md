# Modelando e Transformando Dados Utilizando Funções DAX
O star schema foi modelado utilizando 5 tabelas dimensão e 1 tabela fato. Existem 3 relacionamentos muitos para um e 2 relacionamento muitos para muitos. A professora não corrigiu o fato do relacionamento entre "F_Vendas" e "D_Descontos" serem de muitos para muitos e por isso o deixei desta maneira e permaneci com o outro relacionamento de muitos para muitos.

As colunas foram reorganizadas e em cada tabela houve exclusão de colunas desnecessárias. Na tabela "D_Detalhes" estão contidas as informações que não estão disponíveis nas outras tabelas, num objetivo de aumentar a granularidade de dados. Utilizei funções DAX para a formação de colunas condicionais e renomeação de tabelas.

![Captura de tela 2024-07-24 152218](https://github.com/user-attachments/assets/633280a1-6802-49e8-8cd0-17d2c3472220)
