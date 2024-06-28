## Relatório de Análise de Dados - Teste T de uma Amostra

**Título:** Investigando a Média do GPA dos Alunos (Teste T)

**1. Introdução**

Neste relatório, realizaremos um teste t de uma amostra para investigar se a média do GPA dos alunos em nossa amostra difere significativamente de um valor de referência de 2.5. O GPA (Grade Point Average) é uma medida comum de desempenho acadêmico, e entender se há uma diferença significativa em relação a este valor pode fornecer insights importantes sobre o desempenho dos alunos.

**2. Metodologia**

* **Conjunto de Dados:** utilizamos dados do desempenho dos alunos, extraídos de um arquivo CSV denominado 'Student_performance_data_.csv'. Este conjunto de dados contém diversas variáveis, incluindo o GPA dos alunos.

* **Teste Estatístico - Teste t de uma Amostra:** o teste t de uma amostra compara a média da amostra com uma média populacional conhecida (hipótese nula) para determinar se há uma diferença estatisticamente significativa.

* **Definição de Hipóteses:**
* Hipótese Nula (H0): a média do GPA dos alunos é igual a 2.5.
* Hipótese Alternativa (H1): a média do GPA dos alunos é diferente de 2.5.

* **Análise:** utilizaremos a biblioteca `scipy.stats` do Python para realizar o teste T. Os passos da análise incluem:
1. Importar as bibliotecas necessárias.
2. Carregar o conjunto de dados.
3. Separação e tratamento dos dados a serem analisados (GPA).
4. Definição da hipótese nula (H0) e da hipótese alternativa (H1).
5. Cálculo da estatística T e do valor p usando a função `ttest_1samp` da biblioteca `scipy.stats`.
6. Se o valor p resultante for menor que o nível de significância (usualmente 0.05), rejeitamos a hipótese nula, indicando que há uma diferença significativa na média do GPA dos alunos em relação ao valor de referência.

**3. Resultados**

A análise estatística resultou nos seguintes valores:

- **Estatística t:** -31.73
- **Valor p:** 9.449925924922258e-185 (valor de p muito próximo de zero)

Como o valor p é significativamente menor que 0.05, rejeitamos a hipótese nula. Isso sugere que a média do GPA dos alunos na amostra é estatisticamente diferente de 2.5.


**4. Visualização dos Dados**

Para melhor visualizar a distribuição dos dados e a posição da média amostral em relação a média populacional, foi criado um histograma e apresentado no corpo do teste T em 'testes.ipynb'.


**5. Discussão**

A diferença significativa encontrada no GPA dos alunos indica que eles apresentam um desempenho médio que diverge do valor esperado de 2.5. A média amostral calculada foi de aproximadamente 1.94, o que está abaixo do valor de referência. Essa diferença pode refletir desafios acadêmicos enfrentados pelos alunos ou a eficácia variável dos métodos de ensino. Essa informação pode ser crucial para ajustar estratégias educacionais ou programas de suporte aos alunos, visando melhorar o desempenho acadêmico e garantir uma aprendizagem mais eficaz de um percentual maior dos alunos.


**6. Conclusão**

Com base nos resultados do teste t, concluímos que a média do GPA dos alunos é estatisticamente diferente de 2.5. Isso sugere que a amostra de alunos analisada apresenta um desempenho acadêmico significativamente distinto do valor de referência. Essa análise pode informar decisões educacionais e estratégias de apoio aos estudantes para melhorar o desempenho acadêmico.


**7. Limitações**

É importante considerar que este estudo se baseia em uma amostra específica de dados. Outros fatores não considerados, podem influenciar o desempenho acadêmico dos alunos.
