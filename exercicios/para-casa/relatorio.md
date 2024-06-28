## 1. **Introdução**
Neste relatório, analisaremos duas fontes de dados:

Média de notas dos alunos de uma escola: Utilizando dados coletados em uma pesquisa, buscamos responder a seguinte pergunta: A média de notas registradas é 2,5? Identificar essa média ajudará a escola a tomar medidas cabíveis para aumentar a média ou mantê-la.

Média de idade das mulheres: Utilizando dados coletados no ENEM 2019, buscamos responder se a proporção de mulheres com mais de 20 anos no conjunto de dados é maior que 50%. Identificar essa média ajudará a identificar a faixa etária mais acessada pelo exame.

## 2. **Metodologia**
Conjunto de Dados
Student_performance_data _.csv: Dados de desempenho de alunos, disponíveis no Kaggle.
enem_2019.csv: Dados do ENEM 2019, disponíveis no Kaggle.
Teste de Hipóteses
Teste t: Utilizado para analisar as notas dos alunos, comparando a média observada com a média esperada de 2,5.
Teste z: Utilizado para analisar a idade das mulheres, comparando a proporção observada com a proporção esperada de 50%.
Análise
Utilizamos as seguintes bibliotecas:
```
`#000000`pandas
numpy
matplotlib.pyplot
scipy.stats
statsmodels.stats.proportion
```
Passos da análise incluem:

i. Importar as bibliotecas
ii. Carregar o conjunto de dados
iii. Extrair as colunas a serem utilizadas
iv. Realizar os tratamentos de dados necessários
v. Realizar os testes (t e z)
vi. Interpretar o resultado do teste

## 3. **Resultados**
Análise das Notas

Resultado:

Estatística t: 0.0013
Valor p: 0.999
Não rejeitamos a hipótese nula. Não há evidências suficientes para concluir que a média do GPA dos alunos é diferente da média calculada de 2.5.

Análise da Idade das Mulheres
Resultado:

Estatística z: -423.459
Valor p: 1.0
Não rejeitamos a hipótese nula. Não há evidências suficientes para concluir que a proporção de mulheres com idade maior que 20 anos é maior que 50%.

## 4. **Discussão**
Análise das Notas
O valor de p (0.999) indica que não há evidências estatisticamente significativas para rejeitar a hipótese nula de que a média das notas dos alunos é 2,5. Isso sugere que a média do GPA dos alunos é muito próxima de 2,5, e não há motivos para acreditar que ela seja diferente.

Análise da Idade das Mulheres
O valor p obtido (1.0) indica que os dados observados não fornecem nenhuma evidência contra a hipótese nula de que a proporção de mulheres com mais de 20 anos é 50%. A estatística z negativa sugere que a maioria das mulheres no conjunto de dados tem idade inferior a 20 anos.

## 5. **Conclusão**
Média das Notas
Como o valor de p (0.999) é maior que o nível de significância (0.05), não há evidências suficientes para concluir que a média do GPA dos alunos é diferente da média calculada de 2,5. A escola pode considerar manter as estratégias atuais, pois a média observada está alinhada com a expectativa.

Média de Idade das Mulheres
A estatística z negativa indica que a maioria das mulheres no conjunto de dados tem idade inferior a 20 anos. Como o valor p (1.0) é maior que o nível de significância (0.05), não há evidências suficientes para concluir que a proporção de mulheres com mais de 20 anos é maior que 50%. Isso sugere que a maioria das mulheres que fazem o ENEM são jovens, o que pode ajudar a direcionar políticas educacionais e de divulgação do exame.
