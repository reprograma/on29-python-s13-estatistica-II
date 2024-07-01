**Título:** Analisando a média de notas (Grade Point Average - GPA) de estudantes utilizando o Teste T-Student

**1. Introdução**
Apresentamos neste relatório uma análise sobre a média de notas de estudantes de 15 até 18 anos, utilizando dados coletados em uma pesquisa. Tal análise busca responder à seguinte pergunta: **A média de notas dos estudantes é igual a 2.0?**. O valor 2.0 é considerado como conceito 'D', abaixo do regular, conforme apresentado na escala de notas de 0 a 4, a seguir:

0: 'A' (GPA >= 3.5)
1: 'B' (3.0 <= GPA < 3.5)
2: 'C' (2.5 <= GPA < 3.0)
3: 'D' (2.0 <= GPA < 2.5)
4: 'F' (GPA < 2.0)

Compreender em qual faixa de notas se encontram a maioria dos estudantes é fundamental para saber se as estratégias educacionais atuais são funcionais.

**2. Materiais e métodos**
Para responder à pergunta norteadora da pesquisa, utilizamos:
*   Conjunto de dados: disponível na plataforma Kaggle, utilizamos o *dataset* denominado *Students Perfomance Dataset*. Os dados apresentam diversas informações sobre os 2392 estudantes do Ensino Médio estadounidense (*High School*), tais como gênero, idade, etnia, entre outros. 
*   Teste de Hipóteses: para analisar as informações obtidas na coluna GPA da tabela, utilizamos o Teste T-Student, que indica a diferença entre a média real dos dados e a média estipulada pela pergunta inicial.
*   Análise: utilizamos a biblioteca **scipy.stats** do Python para desenvolver o Teste T-Student. Os passos da análise incluem: 

        a. Importar as bibliotecas necessárias.
        b. Carregar o conjunto de dados.
        c. Criar uma tabela destacando apenas as médias GPA.
        d. Realizar o Teste T-Student.       
        e. Interpretar os resultados do teste, incluindo o valor p e a estatística T.
  
**3. Resultados**
Dentre o cálculo de algumas medidas descritivas, obtivemos o valor da média das amostras:
*   Média amostral: 1.9061863027265407

Já o Teste T-Student retornou os seguintes resultados:

*   Estatística T: -5.013624381766575
*   Valor p: 5.733044870766935e-07


**4. Resultados**
O valor p obtido (5.733044870766935e-07) é menor que o nível de significância usual de 0.05. Isso indica que há evidências suficientes para rejeitar a hipótese nula de que a média de GPA seja igual a 2.0. 
É importante ressaltar que não consideramos apenas o Teste T-Student para analisar o resultado. Calculamos a média dos dados por meio da função **.mean()**, que confirmou que o valor da média não é 2.0, mas sim aproximadamente 1.91. 

**5. Conclusão**
A análise desenvolvida com o Teste T-Student sugere que a média proposta na hipótese (2.0) difere da média real das amostras (1.91), ou seja, a maioria das médias dos estudantes é considerada como conceito F. Dessa maneira, compreendemos que as estratégias educacionais precisam ser aprimoradas, a fim de auxiliar os estudantes a se desenvolverem de forma mais satisfatória e, consequentemente, aumentar a média GPA. 

