## Relatório: Teste de Proporções com Teste Z

**Título:** Analisando a proporção de mulheres inscritas no enem 2019 com idade superior a 20 anos

**1. Introdução**

O teste Z de proporções é uma ferramenta estatística utilizada para verificar se uma proporção amostral difere significativamente de uma proporção populacional esperada. Neste caso, estamos interessadas em investigar se a proporção de mulheres com idade superior a 20 anos que realizaram o ENEM 2019 é maior do que 50%.


**2. Metodologia**

* **Conjunto de Dados:** primeiramente, carregamos os dados do arquivo CSV 'enem_2019.csv' e filtramos apenas as informações relevantes, ou seja, as idades das mulheres que realizaram o exame.

* **Definição de Hipóteses:**
* Hipótese Nula (H0): a proporção de mulheres com idade maior que 20 anos é igual a 50%.
* Hipótese Alternativa (H1): a proporção de mulheres com idade maior que 20 anos é maior que 50%.

* **Análise:** utilizaremos a biblioteca `statsmodels` do Python para realizar o teste Z. Os passos da análise incluem:
1. Importar as bibliotecas necessárias.
2. Carregar o conjunto de dados.
3. Separação e tratamento dos dados a serem analisados (idade, sexo).
4. Definição da hipótese nula (H0) e da proporção populacional sobre a hipótese nula (p0).
5. Cálculo da estatística Z e o valor p usando a função `proportions_ztest` da biblioteca `statsmodels.stats.proportion`.
6. Se o valor p resultante for menor que o nível de significância (usualmente 0.05), rejeitamos a hipótese nula, indicando que a proporção de mulheres com idade maior que 20 anos é maior que 50%.


**3. Resultados**

Os resultados do teste Z são os seguintes:

* **Estatística Z:** -423.4594208018838
* **Valor p:** 1.0


**4. Visualização dos Dados**

Para uma melhor compreensão, podemos visualizar através do gráfico gerado a distribuição normal com a estatística Z marcada e a área correspondente ao valor p destacada em vermelho (gráfico disponível em: https://colab.research.google.com/drive/1J2sdvMV03euIZY5gx-pe63WBz0eByHqC#scrollTo=S7-RmoGo5IB2).


**5. Discussão**

Com base no valor p obtido e considerando um nível de significância de 5%, não encontramos evidências suficientes para rejeitar a hipótese nula. Portanto, não há suporte estatístico para afirmar que a proporção de mulheres com idade superior a 20 anos que realizaram o ENEM 2019 seja maior que 50%.


**6. Conclusão**

Não rejeitamos a hipótese nula, pois não há evidências suficientes para concluir que a proporção de mulheres com idade maior que 20 anos é maior que 50%.

