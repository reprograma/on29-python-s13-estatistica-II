# Exercício de Casa 🏠 

## Atividade: Testes de Hipóteses com Python e Dados do Kaggle

**Objetivo:**  Aplicar testes de hipóteses em Python usando um conjunto de dados do Kaggle, interpretando os resultados e respondendo a perguntas de pesquisa relevantes.

**Instruções:**

1. **Escolher um Conjunto de Dados:**  
    - Acesse o Kaggle ([https://www.kaggle.com/](https://www.kaggle.com/)) e escolha um conjunto de dados que seja adequado aos tipos de testes que você deseja realizar.
    - **Teste t de Student:** Procure dados que permitam comparar médias de duas amostras independentes (ex: salário de homens vs mulheres, pontuação de alunos em dois métodos de ensino).
    - **Teste Z de Proporções:** Procure dados que permitam comparar proporções (ex: taxa de aprovação em um curso, porcentagem de clientes satisfeitos).
    - **Teste Qui-Quadrado:** Procure dados categóricos que permitam verificar se há associação entre duas variáveis (ex: gênero vs preferência por um produto, tipo de carro vs cor do carro).
    - **Teste ANOVA:** Procure dados que permitam comparar médias de três ou mais grupos (ex: efeito de diferentes fertilizantes no rendimento de uma plantação).

2. **Definir a Pergunta de Pesquisa:**  Formule uma pergunta de pesquisa específica que possa ser respondida usando o teste sorteado e os dados escolhidos.
    - Exemplos:
        - **Teste t:** "Existe uma diferença significativa na altura média dos jogadores de basquete entre dois times diferentes?"
        - **Teste Z:** "A taxa de aprovação em um curso online é diferente da taxa de aprovação em um curso presencial?"
        - **Teste Qui-Quadrado:** "Há uma relação entre o gênero e a preferência por um tipo específico de filme?"
        - **Teste ANOVA:** "Diferentes tipos de fertilizantes impactam o rendimento médio de uma plantação de forma significativa?"

3. **Definir as Hipóteses:**  Definir a hipótese nula (H0) e a hipótese alternativa (H1) para sua pergunta de pesquisa.
    - Exemplos:
        - **H0:** Não há diferença significativa na altura média dos jogadores dos dois times.
        - **H1:** Há uma diferença significativa na altura média dos jogadores dos dois times.
        - **H0:** A taxa de aprovação em um curso online é igual à taxa de aprovação em um curso presencial.
        - **H1:** A taxa de aprovação em um curso online é diferente da taxa de aprovação em um curso presencial.
        - **H0:** Gênero e preferência por tipo de filme são independentes.
        - **H1:** Gênero e preferência por tipo de filme são dependentes.
        - **H0:** Não há diferença significativa no rendimento médio da colheita entre os diferentes tipos de fertilizantes.
        - **H1:** Há pelo menos um tipo de fertilizante que impacta o rendimento médio da colheita de forma diferente.

4. **Analisar os Dados:** Usar Python para realizar o teste de hipóteses escolhido e analisar os dados.
    - Utilize bibliotecas Python como `scipy`, `statsmodels` e `numpy` para realizar os cálculos necessários.

5. **Interpretar os Resultados:**  Deve interpretar os resultados do teste, incluindo o valor p e a decisão sobre a hipótese nula.
    - **Valor p:** É a probabilidade de obter os resultados observados, assumindo que a hipótese nula é verdadeira.
    - **Decisão sobre a hipótese nula:** Se o valor p for menor que o nível de significância (α, geralmente 0.05), rejeitamos a hipótese nula. Se o valor p for maior que α, não rejeitamos a hipótese nula.

6. **Relatório:**  Deve elaborar um relatório sobre a análise, incluindo as seguintes seções:
    - **Introdução:** Descreva o contexto da pesquisa, a pergunta de pesquisa e a importância da análise.
    - **Metodologia:** Descreva o conjunto de dados utilizado, o teste de hipóteses escolhido e os passos da análise.
    - **Resultados:** Apresente os resultados do teste, incluindo o valor p, estatística do teste e tabelas ou gráficos relevantes.
    - **Discussão:** Interprete os resultados do teste, relacionando-os à pergunta de pesquisa e às hipóteses. Discuta as implicações dos resultados e as limitações da análise.
    - **Conclusão:** Resuma as conclusões da análise e as implicações práticas dos resultados.

**Recursos:**

- [Modelo Relatório de Análise de Dados - Teste de Hipóteses](exercicio/para-casa/modelo_relatorio)
- [Kaggle](https://www.kaggle.com/)
- [Documentação Scipy](https://docs.scipy.org/doc/scipy/reference/index.html)
- [Documentação Statsmodels](https://www.statsmodels.org/stable/index.html)
- [Documentação Numpy](https://numpy.org/doc/stable/)

**Dicas:**

* Escolha um conjunto de dados que seja interessante e que você possa entender.
* Formular uma pergunta de pesquisa clara e específica.
* Use a biblioteca correta para realizar o teste de hipóteses escolhido.
* Interprete os resultados do teste de forma clara e concisa.

---

Terminou o exercício? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!

- [ ] Fiz o fork do repositório.
- [ ] Clonei o fork na minha máquina (`git clone url-do-meu-fork`).
- [ ] Resolvi o exercício.
- [ ] Adicionei as mudanças. (`git add .` para adicionar todos os arquivos, ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitei a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)
- [ ] Criei um Pull Request seguindo as orientaçoes que estao nesse [documento](https://github.com/mflilian/repo-example/blob/main/exercicios/para-casa/instrucoes-pull-request.md).
