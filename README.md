# Análise Exploratória de Dados - ANSUR I (1988)

## Objetivo
Este projeto tem como objetivo realizar uma análise exploratória dos dados antropométricos do dataset **ANSUR I 1988**, com foco nas variáveis altura (HEIGHT) e peso (WEIGHT), utilizando bibliotecas do Python como Pandas, Matplotlib e Seaborn. O objetivo é identificar padrões, tendências e diferenças por gênero.

## Dataset
O dataset utilizado para este projeto é o **ANSUR I 1988**, que contém dados antropométricos. Você pode acessar o dataset através do seguinte link:

[Link para o dataset ANSUR I 1988](https://www.triolastats.com/es14-data-sets)

## Etapas Realizadas

1. **Carregamento e inspeção dos dados:**
   - Visualização inicial do dataset.
   - Verificação de valores nulos e descrição estatística das variáveis.

2. **Análise de Outliers:**
   - Identificação de outliers na altura utilizando o método IQR.
   - Considerações sobre o tratamento dos outliers.

3. **Análises Gráficas:**
   - Histogramas e boxplots para observar a distribuição das variáveis.
   - Gráficos de dispersão com análise de correlação entre altura e peso.

4. **Análise por Gênero:**
   - Cálculo de médias, desvios padrão e coeficientes de variação para altura e peso por gênero.
   - Observações sobre a diferença de consistência entre os grupos.

## Resultados Obtidos
- Altura e peso possuem uma correlação positiva forte (0.74).
- Diferença significativa na distribuição dos gêneros na amostra, com mais mulheres do que homens.
- As mulheres apresentam uma maior consistência em relação ao peso enquanto que os homens apresentam uma maior consistência em relação a altura.
