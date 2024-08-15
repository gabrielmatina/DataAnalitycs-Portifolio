# 📊 Dashboard de RH: Análise de Funcionários e Indicadores de Desempenho

Este projeto envolve a criação de um dashboard de Recursos Humanos (RH) que visa fornecer respostas a perguntas chave sobre o quadro de funcionários da empresa, como total de colaboradores, experiência média, distribuição por gênero, e outras métricas relevantes. Além disso, realiza cálculos críticos para apoiar decisões estratégicas, como a análise de elegibilidade para promoções.

![Dashboard de RH](Data/rh.png)

## 📑 Sumário
- [Objetivo do Projeto](#objetivo-do-projeto)
- [Ferramentas Utilizadas](#ferramentas-utilizadas)
- [Estrutura do Dashboard](#estrutura-do-dashboard)
- [Análise de Funcionários](#análise-de-funcionários)
- [Indicadores de Desempenho e Envolvimento](#indicadores-de-desempenho-e-envolvimento)
- [Conclusão](#conclusão)

### 🎯 Objetivo do Projeto
O objetivo principal deste projeto é desenvolver um dashboard que responda às seguintes perguntas de negócio:

1. 👥 **Qual o total de funcionários atualmente na empresa?**
2. 📅 **Qual o tempo médio de experiência dos funcionários (em anos)?**
3. 👨‍👩‍👧 **Qual o total e percentual de funcionários do gênero masculino e feminino?**
4. 💰 **Qual a média salarial mensal?**
5. 🛠️ **Qual o total de funcionários por função?**
6. ⏰ **Qual o percentual de funcionários disponíveis para fazer hora extra?**
7. 📊 **Qual o nível de envolvimento dos funcionários no trabalho considerando 4 categorias: Ruim, Baixo, Médio e Alto?**

Além dessas questões, um cálculo adicional foi feito para determinar:

8. 🎯 **Qual o total e o percentual de funcionários que devem receber promoção?** - Este cálculo foi feito considerando a regra: funcionários com 5 anos ou mais desde a última promoção devem ser considerados para promoção.

### 🛠️ Ferramentas Utilizadas
- **Microsoft Power BI**: Utilizado para a construção e visualização do dashboard.
- **Microsoft Excel**: Arquivos nos formatos `.csv` contendo os dados de Funcionários, Salários, e Desempenho.
- **DAX (Data Analysis Expressions)**: Utilizado para criar cálculos e medidas no Power BI.
- **ETL (Extract, Transform, Load)**: Processo realizado diretamente no Power BI para transformar e modelar os dados.

### 🗂️ Estrutura do Dashboard
O dashboard foi estruturado para fornecer uma visão clara e detalhada sobre os principais indicadores de RH da empresa:

#### 👥 Análise de Funcionários
- **Total de Funcionários**: Um cartão simples mostrando o número total de funcionários na empresa.
- **Tempo Médio de Experiência**: Gráfico de colunas mostrando o tempo médio de experiência dos funcionários em anos.
- **Distribuição por Gênero**: Gráfico de rosca mostrando o total e o percentual de funcionários do gênero masculino e feminino.
- **Média Salarial Mensal**: Indicador mostrando a média salarial mensal dos funcionários.
- **Total de Funcionários por Função**: Gráfico de barras detalhando o número de funcionários em cada função dentro da empresa.

#### 📊 Indicadores de Desempenho e Envolvimento
- **Disponibilidade para Hora Extra**: Gráfico de colunas mostrando o percentual de funcionários que estão disponíveis para fazer horas extras.
- **Nível de Envolvimento no Trabalho**: Gráfico de radar mostrando a distribuição do nível de envolvimento dos funcionários em quatro categorias: Ruim, Baixo, Médio e Alto.

### 🎯 Cálculo de Promoções (Fora do Dashboard)
- **Total e Percentual de Funcionários que Devem Receber Promoção**: O cálculo foi feito considerando que funcionários com 5 anos ou mais desde a última promoção devem ser promovidos. Este resultado pode ser usado para planejamento estratégico de promoções.

#### 🎓 Sobre o Curso
Este projeto é parte do curso [Microsoft Power BI Para Business Intelligence e Data Science oferecido pela Data Science Academy](https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-business-intelligence-e-data-science). O curso é voltado para profissionais que desejam aprimorar suas habilidades em Business Intelligence e Data Science utilizando o Microsoft Power BI.

### 🔍 Conclusão
O Dashboard de RH oferece uma visão abrangente sobre o quadro de funcionários da empresa, com insights detalhados sobre experiência, distribuição de gênero, média salarial, e outros indicadores críticos. Além disso, fornece dados calculados para apoiar decisões sobre promoções, ajudando a alinhar as estratégias de RH com os objetivos de negócios da empresa.

