## Relatório de Análise de Dados - Teste de Hipóteses

**Título:** Analisando a Relação entre Gênero e Preferência por Filmes de Ação (Teste Qui-Quadrado)

**1. Introdução**

Neste relatório, analisaremos a relação entre o gênero e a preferência por filmes de ação, utilizando dados coletados em uma pesquisa. A pergunta de pesquisa que buscamos responder é: **"Há uma relação entre o gênero e a preferência por filmes de ação?"** Compreender essa relação pode ser útil para o mercado cinematográfico, por exemplo, para direcionar melhor as campanhas de marketing.

**2. Metodologia**

* **Conjunto de Dados:** Para este estudo, utilizaremos o conjunto de dados "Movie Preferences Survey" disponível no Kaggle. Esse conjunto de dados contém informações sobre a preferência por diferentes gêneros de filmes, incluindo a variável "Gênero" (Masculino/Feminino) e a variável "Preferência por Ação" (Sim/Não).
* **Teste de Hipóteses:** Para analisar a relação entre as variáveis categóricas "Gênero" e "Preferência por Ação", utilizaremos o teste Qui-Quadrado de Independência. Este teste compara as frequências observadas de cada combinação de categorias com as frequências esperadas sob a hipótese de independência entre as variáveis.
* **Análise:**  Utilizaremos a biblioteca `scipy.stats` do Python para realizar o teste Qui-Quadrado. Os passos da análise incluem:
    1. Importar as bibliotecas necessárias.
    2. Carregar o conjunto de dados.
    3. Criar a tabela de contingência com as frequências observadas.
    4. Realizar o teste Qui-Quadrado.
    5. Interpretar os resultados do teste, incluindo o valor p e a estatística do teste.

**3. Resultados**

A tabela de contingência abaixo mostra as frequências observadas de cada combinação de gênero e preferência por filmes de ação:

| Gênero     | Preferência por Ação | Total |
|-------------|-----------------------|-------|
| Masculino  | 60                   | 100    |
| Feminino   | 40                   | 100    |
| Total       | 100                  | 200    |

O teste Qui-Quadrado retornou os seguintes resultados:

* **Estatística Qui-Quadrado:** 4.00
* **Valor p:** 0.0455
* **Graus de Liberdade:** 1

**4. Discussão**

O valor p obtido (0.0455) é menor que o nível de significância usual de 0.05. Isso indica que há evidências suficientes para rejeitar a hipótese nula de independência entre gênero e preferência por filmes de ação. Portanto, concluímos que existe uma relação significativa entre essas duas variáveis.

É importante observar que o teste Qui-Quadrado não indica a direção da relação.  Para entender melhor a natureza dessa relação, precisamos analisar a tabela de contingência. Podemos observar que a proporção de homens que preferem filmes de ação é maior do que a proporção de mulheres que preferem esse gênero.

**5. Conclusão**

A análise realizada com o teste Qui-Quadrado sugere que existe uma relação significativa entre o gênero e a preferência por filmes de ação. Os resultados indicam que a proporção de homens que preferem filmes de ação é significativamente maior do que a proporção de mulheres. Essa informação pode ser útil para direcionar melhor as campanhas de marketing para esse gênero de filmes.

**6. Limitações**

É importante reconhecer as limitações da análise. O conjunto de dados utilizado é relativamente pequeno, e os resultados podem não ser generalizáveis para toda a população. Além disso, a análise não considera outros fatores que podem influenciar a preferência por filmes de ação, como idade, localização geográfica e outros interesses.

</br>

> **Observação:** Este relatório é apenas um exemplo de como elaborar um relatório de análise de dados com teste de hipóteses. O conteúdo do seu relatório deve ser adaptado à sua pergunta de pesquisa, aos dados escolhidos e ao teste de hipóteses que você realizar.




