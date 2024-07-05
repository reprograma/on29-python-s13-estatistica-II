**Título:** Análise da "Grade Point Average" - GPA (Teste T)

**1. Introdução**

Neste relatório, analisaremos a relação entre o gênero e a preferência por filmes de ação, utilizando dados coletados em uma pesquisa. A pergunta de pesquisa que buscamos responder é: **"Há uma relação entre o gênero e a preferência por filmes de ação?"** Compreender essa relação pode ser útil para o mercado cinematográfico, por exemplo, para direcionar melhor as campanhas de marketing.

Apresentamos neste relatório uma análise sobre a média de notas de estudantes de 15 até 18 anos, utilizando dados coletados em uma pesquisa. Tal análise busca responder à seguinte pergunta: **A média de notas dos estudantes é igual a 2.0?**. O valor 2.0 é considerado como conceito 'D', abaixo do regular, conforme apresentado na escala de notas de 0 a 4, a seguir:

0: 'A' (GPA >= 3.5)
1: 'B' (3.0 <= GPA < 3.5)
2: 'C' (2.5 <= GPA < 3.0)
3: 'D' (2.0 <= GPA < 2.5)
4: 'F' (GPA < 2.0)

**2. Metodologia**

Análise: utilizamos a biblioteca scipy.stats do Python para desenvolver o Teste T. 

Teste de Hipóteses: para analisar as informações obtidas na coluna GPA da tabela, utilizamos o Teste T-Student, que indica a diferença entre a média real dos dados e a média estipulada pela pergunta inicial.


**3. Resultados**

O Teste T-Student retornou os seguintes resultados:

*   Estatística T: -5.013624381766575
*   Valor p: 5.733044870766935e-07


**4. Discussão**

O valor p obtido (5.733044870766935e-07) é menor que o nível de significância usual de 0.05. Isso indica que há evidências suficientes para rejeitar a hipótese nula de que a média de GPA seja igual a 2.0. 

É importante ressaltar que não consideramos apenas o Teste T-Student para analisar o resultado. Calculamos a média dos dados por meio da função .mean(), que confirmou que o valor da média não é 2.0, mas sim aproximadamente 1.91. 

**5. Conclusão**

A análise desenvolvida com o Teste T-Student sugere que a média proposta na hipótese (2.0) difere da média real das amostras (1.91), ou seja, a maioria das médias dos estudantes é considerada como conceito F. Dessa maneira, compreendemos que as estratégias educacionais precisam ser aprimoradas, a fim de auxiliar os estudantes a se desenvolverem de forma mais satisfatória e, consequentemente, aumentar a média GPA. 