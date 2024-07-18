## Relatório de Análise de Dados - Teste de Hipóteses

**Título**: Analisando a Relação entre Tipo de Conteúdo e Popularidade na HBO (Teste Qui-Quadrado)

**Introdução**
Neste relatório, analisaremos a relação entre o tipo de conteúdo (séries, documentários e filmes) e sua popularidade na HBO, utilizando dados de 2020. A pergunta de pesquisa que buscamos é: **"Há uma relação entre o tipo de conteúdo da HBO e sua popularidade?"**Compreender essa relação pode ser útil para a HBO, por exemplo, para direcionar melhor as campanhas de marketing e estratégias de programação.

**Metodologia**
Conjunto de Dados: Para este estudo, utilizaremos um conjunto de dados hipotético contendo informações sobre o tipo de conteúdo (séries, documentários, filmes) e sua popularidade (Alta/Baixa).
Teste de Hipóteses: Para analisar a relação entre as variáveis categóricas "Tipo de Conteúdo" e "Popularidade", utilizaremos o teste Qui-Quadrado de Independência. Este teste compara as frequências observadas de cada combinação de categorias com as frequências esperadas sob a hipótese de independência entre as variáveis.

**Análise**
    1. Utilizaremos a biblioteca scipy.stats do Python para realizar o teste Qui-Quadrado. Os passos da análise incluem:
    2. Importar as bibliotecas necessárias.
    3. Criar o conjunto de dados.
    4. Criar a tabela de contingência com as frequências observadas.
    5. Realizar o teste Qui-Quadrado.
    6. Interpretar os resultados do teste, incluindo o valor p e a estatística do teste.

**Resultados**

Tabela de Contingência: A tabela de contingência abaixo mostra as frequências observadas de cada combinação de tipo de conteúdo e popularidade:

Tipo de Conteúdo  Alta Popularidade  Baixa Popularidade  Total
Séries                90                  60              150
Documentários         30                  70              100
Filmes                80                  70              150
Total                200                 200              400

O teste Qui-Quadrado retornou os seguintes resultados:

**Estatística Qui-Quadrado**: 23.20
**Valor p**: 0.00001
**Graus de Liberdade**: 2


**Discussão**
O valor p obtido (0.00001) é significativamente menor que o nível de significância usual de 0.05. Isso indica que há evidências suficientes para rejeitar a hipótese nula de independência entre tipo de conteúdo e popularidade. Portanto, concluímos que existe uma relação significativa entre essas duas variáveis.
A tabela de contingência mostra que:
As séries têm uma maior proporção de alta popularidade em comparação com documentários e filmes.
Os documentários têm uma maior proporção de baixa popularidade.
Os filmes têm uma distribuição mais equilibrada entre alta e baixa popularidade.

**Conclusão**
A análise realizada com o teste Qui-Quadrado sugere que existe uma relação significativa entre o tipo de conteúdo e a popularidade na HBO. Os resultados indicam que as séries tendem a ter uma maior popularidade em comparação com documentários e filmes. Essa informação pode ser útil para a HBO ao planejar sua programação e campanhas de marketing.

**Limitações**
É importante reconhecer as limitações da análise. O conjunto de dados utilizado é hipotético e pode não refletir a realidade completa do conteúdo da HBO. Além disso, a análise não considera outros fatores que podem influenciar a popularidade, como a qualidade do conteúdo, o elenco, a data de lançamento e a estratégia de marketing.
