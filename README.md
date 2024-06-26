<h1 align="center">
  <img src="assets/reprograma-fundos-claros.png" alt="logo reprograma" width="500">
</h1>

<h1 align="center">  Estatística com Python - Testes de Hipóteses 🧪📊 </h1>
<h3 align="center">  Turma ON29 | Python | Semana 12 | 2024 | Professora Camila Ribeiro  </h3>

<br>

### Instruções

Antes de começar, vamos organizar nosso setup.


    1. Fork esse repositório

    2. Clone o fork na sua máquina (Para isso basta abrir o seu terminal e digitar `git clone url-do-seu-repositorio-forkado`)

    3. Entre na pasta do seu repositório (Para isso basta abrir o seu terminal e digitar `cd nome-do-seu-repositorio-forkado`)


<br>

---

## Índice

- **1. Testes de Hipóteses**
    - [**1.1 Definição de Hipóteses Nulas e Alternativas**](capitulos/testes_hipoteses.md#11-definicao-de-hipoteses-nulas-e-alternativas)
    - [**1.2 Tipos de Testes de Hipóteses**](capitulos/testes_hipoteses.md#12-tipos-de-testes-de-hipoteses)
        - [**1.2.1 Teste t de Student**](capitulos/testes_hipoteses.md#121-teste-t-de-student)
            - [**1.2.1.1 Teste t de uma amostra**](capitulos/testes_hipoteses.md#1211-teste-t-de-uma-amostra)
            - [**1.2.1.2 Teste t de duas amostras**](capitulos/testes_hipoteses.md#1212-teste-t-de-duas-amostras)
        - [**1.2.2 Teste Z**](capitulos/testes_hipoteses.md#122-teste-z)
            - [**1.2.2.1 Teste Z de uma proporção**](capitulos/testes_hipoteses.md#1221-teste-z-de-uma-proporcao)
            - [**1.2.2.2 Teste Z de duas proporções**](capitulos/testes_hipoteses.md#1222-teste-z-de-duas-proporcoes)
        - [**1.2.3 Teste Qui-Quadrado**](capitulos/testes_hipoteses.md#123-teste-qui-quadrado)
        - [**1.2.4 Teste ANOVA**](capitulos/testes_hipoteses.md#124-teste-anova)
    - [**1.3 Erros Tipo I e Tipo II**](capitulos/testes_hipoteses.md#13-erros-tipo-i-e-tipo-ii)
    - [**1.4 Níveis de Significância**](capitulos/testes_hipoteses.md#14-niveis-de-significancia)
    - [**1.5 Interpretação dos Resultados**](capitulos/testes_hipoteses.md#15-interpretacao-dos-resultados)
    - [**1.6 Em Resumo**](capitulos/testes_hipoteses.md#16-em-resumo)
- **2. Testes de Hipóteses em Python**
    - [**2.1 Definição de Hipóteses Nulas e Alternativas**](capitulos/testes_pyhton.md#21-definicao-de-hipoteses-nulas-e-alternativas)
    - [**2.2 Tipos de Testes de Hipóteses**](capitulos/testes_pyhton.md#22-tipos-de-testes-de-hipoteses)
        - [**2.2.1 Teste t de Student**](capitulos/testes_pyhton.md#221-teste-t-de-student)
        - [**2.2.2 Teste Z**](capitulos/testes_pyhton.md#222-teste-z)
        - [**2.2.3 Teste Qui-Quadrado**](capitulos/testes_pyhton.md#223-teste-qui-quadrado)
        - [**2.2.4 Teste ANOVA**](capitulos/testes_pyhton.md#224-teste-anova)
    - [**2.3 Erros Tipo I e Tipo II**](capitulos/testes_pyhton.md#23-erros-tipo-i-e-tipo-ii)
    - [**2.4 Níveis de Significância**](capitulos/testes_pyhton.md#24-niveis-de-significancia)
    - [**2.5 Interpretação dos Resultados**](capitulos/testes_pyhton.md#25-interpretacao-dos-resultados)
    - [**2.6 Em Resumo**](capitulos/testes_pyhton.md#26-em-resumo))

- **3. Testes Individuais**
    - **3.1 Teste t** 
        - [**3.1.1 Teste t para Amostras Independentes:**](capitulos/testes/testet.md)
    - **3.2 Teste Z**
        - [**3.2.1 Teste Z para Comparar Proporções:**](capitulos/testes/testez.md)
    - **3.3 Teste Qui-quadrado**
        - [**3.3.1 Teste Qui-quadrado de Independência:**](capitulos/testes/qui.md)
    - **3.4 Teste ANOVA**
        - [**3.4.1 Teste ANOVA:**](capitulos/testes/anova.md)

---

### 🔗 Links Úteis

**Implementação em Python:**

* **[Documentação Scipy](https://docs.scipy.org/doc/scipy/reference/index.html)**: Documentação completa da biblioteca Scipy, incluindo funções para testes estatísticos.
* **[Documentação Statsmodels](https://www.statsmodels.org/stable/index.html)**: Documentação da biblioteca Statsmodels, com foco em testes estatísticos e modelos estatísticos.
* **[Documentação Numpy](https://numpy.org/doc/stable/)**: Documentação da biblioteca Numpy para manipulação de arrays e matrizes em Python.
* **[Doc Pandas](https://pandas-pydata-org.translate.goog/docs/?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt-BR&_x_tr_pto=sc)** : Documentação da biblioteca Pandas para manipulação e análise de dados estruturados em forma tabular.
* **[Doc Matplotlib](https://matplotlib-org.translate.goog/?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt-BR&_x_tr_pto=sc)** : Documentação da biblioteca Matplotlib para criação de gráficos.
* **[Doc Random](https://docs.python.org/pt-br/3/library/random.html)** : Documentação da biblioteca Random para gerar números aleatórios em Python.

**Sites de Dados:**

* **[Kaggle](https://www.kaggle.com/)**: Uma plataforma popular para encontrar e baixar conjuntos de dados para análise.
* **[UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php)**: Repositório de dados para aprendizado de máquina e análise de dados.


<p align="center">
Desenvolvido com :purple_heart:  
</p>

