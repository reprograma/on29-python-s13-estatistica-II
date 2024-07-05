**Título:** Análise da "Student_performance_data_" (Teste Qui-Quadrado)

**1. Introdução**

Neste relatório, analisaremos a associação do envolvimento do aluno em esportes pelo gênero, utilizando a database Student_performance. A pergunta da pesquisa que respondemos foi **"Há associação entre o gênero do aluno e a participação em esportes?"**. Entendo esses resultados poderá ser trabalhado formas de incentivo para determinado gênero.

**2. Metodologia**

Análise: utilizamos a biblioteca statsmodels.stats.proportion do Python para desenvolver o Teste Qui-quadrado. 

Teste de Hipóteses: 
Hipótese Nula (H0): Não há associação entre o gênero do aluno e a participação em esportes.
Hipótese Alternativa (H1): Há uma associação entre o gênero do aluno e a participação em esporte


**3. Resultados**

O Teste Qui-quadrado retornou os seguintes resultados:

*   Chi-statistic: 0.15261664988758886
*   P-value: 0.6960472310668808
*   Graus de liberdade: 1


**4. Discussão**

A hipótese nula não foi rejeitada devido o valor elevado do p, com isso não há evidências suficientes para sugerir que há uma associação entre o gênero no teste realizado.

**5. Conclusão**

Esta análise apresenta a existência de uma relação significativa entre o apoio dos pais e o desempenho acadêmico dos alunos, assim como entre a participação em várias atividades extracurriculares e a proporção esperada de 50%. 