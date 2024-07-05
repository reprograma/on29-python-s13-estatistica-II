**Título:** Análise do "enem_2019" (Teste Anova)

**1. Introdução**

Neste relatório, analisaremos a nota com redação acima de 500 das mulheres que fizeram o Enem no ano de 2019, utilizando a database do Enem desse ano. A resposta que buscamos visualizar foi **"Identificar as médias das faixa etárias das mulheres com a redação acima de 500 por estado"**. Essa pesquisa busca entender essa proporcionalidade conforme a região.

**2. Metodologia**

Análise: utilizamos a biblioteca statsmodels.formula.api do Python para desenvolver o Teste Anova. 

Teste de Hipóteses: 
Hipótese nula (H0): média de idade das mulheres que fizeram enem é 20 anos
Hipótese alternativa (H1): média de idade das mulheres que fizeram enem é maior que 20 anos


**3. Resultados**

O Teste Anova retornou os seguintes resultados:

OLS Regression Results                            
==============================================================================
Dep. Variable:           nota_redacao   R-squared:                       0.015
Model:                            OLS   Adj. R-squared:                 -0.007
Method:                 Least Squares   F-statistic:                    0.7039
Date:                Thu, 04 Jul 2024   Prob (F-statistic):               1.00
Time:                        21:19:44   Log-Likelihood:                -87680.
No. Observations:               24422   AIC:                         1.764e+05
Df Residuals:                   23887   BIC:                         1.808e+05
Df Model:                         534                                         
Covariance Type:            nonrobust     

==================================================================================================
                                     coef    std err          t      P>|t|      [0.025      0.975]
--------------------------------------------------------------------------------------------------
Intercept                      -1.548e+12    1.8e+12     -0.861      0.389   -5.07e+12    1.98e+12
C(idade)[T.13]                   8.61e+11    8.7e+11      0.989      0.323   -8.45e+11    2.57e+12
C(idade)[T.14]                  8.564e+11   1.33e+12      0.642      0.521   -1.76e+12    3.47e+12
C(idade)[T.15]                  5.028e+12   8.28e+12      0.607      0.544   -1.12e+13    2.13e+13
C(idade)[T.16]                  1.548e+12    1.8e+12      0.861      0.389   -1.98e+12    5.07e+12
C(idade)[T.17]                  1.548e+12    1.8e+12      0.861      0.389   -1.98e+12    5.07e+12
C(idade)[T.18]                  1.548e+12    1.8e+12      0.861      0.389   -1.98e+12    5.07e+12
C(idade)[T.19]                  1.548e+12    1.8e+12      0.861      0.389   -1.98e+12    5.07e+12
C(idade)[T.20]                  1.548e+12    1.8e+12      0.861      0.389   -1.98e+12    5.07e+12
C(idade)[T.21]                  1.548e+12    1.8e+12      0.861      0.389   -1.98e+12    5.07e+12
C(idade)[T.22]                  1.548e+12    1.8e+12      0.861      0.389   -1.98e+12    5.07e+12


**4. Discussão**

**5. Conclusão**

A última faixa etária analisada, sendo esta de +35 apresentou maior discrepância entre as outras faixa etárias visualizadas pelo teste Anova.