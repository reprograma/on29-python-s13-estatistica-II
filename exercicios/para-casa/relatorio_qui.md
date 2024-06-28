## Relatório de Análise de Dados - Teste de Hipóteses

**Título:** Analisando a Relação entre Gênero e Participação em Atividades Extracurriculares (Teste Qui-Quadrado)


**1. Introdução**

Neste relatório, analisaremos a relação entre o gênero dos alunos e a participação em atividades extracurriculares, utilizando dados coletados em uma pesquisa. A pergunta de pesquisa que buscamos responder é: "Há uma relação entre o gênero dos alunos e a participação em atividades extracurriculares?" Compreender essa relação pode ser útil para a administração escolar e para o desenvolvimento de programas que incentivem a participação dos alunos.


**2. Metodologia**

* **Conjunto de Dados:** para este estudo, utilizaremos o conjunto de dados "Student_performance_data _" disponível no Kaggle. Esse conjunto de dados contém informações abrangentes sobre 2.392 estudantes do ensino médio, detalhando seus dados demográficos (idade, gênero, etnia, nível de educação dos pais), hábitos de estudo, envolvimento dos pais, atividades extracurriculares e desempenho acadêmico. A variável alvo, GradeClass, classifica as notas dos alunos em categorias distintas, fornecendo um conjunto de dados robusto para pesquisa educacional, modelagem preditiva e análise estatística.

* **Teste de Hipóteses:** no presente estudo faremos a análise da relação entre as variáveis categóricas "Gênero" e "Participação em Atividades Extracurriculares", e para isso utilizaremos o teste Qui-Quadrado de Independência. Este teste compara as frequências observadas de cada combinação de categorias com as frequências esperadas sob a hipótese de independência entre as variáveis.

* **Análise:** utilizaremos a biblioteca `scipy.stats` do Python para realizar o teste Qui-Quadrado. Os passos da análise incluem:
1. Importar as bibliotecas necessárias.
2. Carregar o conjunto de dados.
3. Criar a tabela de contingência com as frequências observadas.
4. Realizar o teste Qui-Quadrado.
5. Interpretar os resultados do teste, incluindo o valor p e a estatística do teste.


**3. Resultados**

A tabela de contingência abaixo mostra as frequências observadas de cada combinação de gênero e participação em atividades extracurriculares:

| Gênero   | Participação em Atividades Extracurriculares | Total |
|----------|---------------------------------------------|-------|
| Masculino| 718                                         | 452   | 1170 |
| Feminino | 757                                         | 465   | 1222 |
| Total    | 1475                                        | 917   | 2392 |

O teste Qui-Quadrado retornou os seguintes resultados:

* **Estatística Qui-Quadrado:** 0.062318177188428615
* **Valor p:** 0.8028687865937287
* **Graus de Liberdade:** 1

**4. Discussão**

O valor p obtido (0.8028687865937287) é maior que o nível de significância usual de 0.05. Isso indica que não há evidências suficientes para rejeitar a hipótese nula de independência entre gênero e participação em atividades extracurriculares. Portanto, concluímos que não existe uma relação significativa entre essas duas variáveis.

Embora a análise sugira que não há uma relação estatisticamente significativa entre o gênero dos alunos e a participação em atividades extracurriculares, é importante considerar as frequências observadas e esperadas. As proporções de participação para ambos os gêneros são bastante semelhantes.


**5. Conclusão**

A análise realizada com o teste Qui-Quadrado sugere que não existe uma relação significativa entre o gênero dos alunos e a participação em atividades extracurriculares. Os resultados indicam que as proporções de participação são semelhantes entre pessoas do gênero masculino e feminino. Esta informação pode ser útil para as escolas na hora de planejar e implementar atividades que promovam a participação de todos os alunos, independentemente do gênero.


**6. Limitações**

É importante reconhecer as limitações da análise. O conjunto de dados utilizado pode não ser representativo de toda a população escolar. Além disso, a análise não considera outros fatores que podem influenciar a participação em atividades extracurriculares, como interesses pessoais, disponibilidade de tempo e o ambiente escolar.
