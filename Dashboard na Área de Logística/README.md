# 🚚 Dashboard de Logística: Análise de Desempenho de Entregas

Este projeto envolve a criação de um dashboard para análise do desempenho logístico, focado em métricas de entregas, como a pontualidade, desempenho por equipe, e análise de atrasos por localização. O objetivo é fornecer insights que ajudem a otimizar as operações logísticas e melhorar a satisfação do cliente.

![Dashboard de Logística](Data/dashboard_logistica.png)

## 📑 Sumário
- [Objetivo do Projeto](#objetivo-do-projeto)
- [Ferramentas Utilizadas](#ferramentas-utilizadas)
- [Estrutura do Dashboard](#estrutura-do-dashboard)
- [Análise de Desempenho Logístico](#análise-de-desempenho-logístico)
- [Conclusão](#conclusão)

### 🎯 Objetivo do Projeto
O objetivo principal deste projeto é criar um dashboard que responda às seguintes perguntas de negócio:

1. 📦 **Qual o total de entregas no prazo por canal de entrega?**
2. ⏳ **Qual o percentual de entregas antecipadas por equipe de entrega?**
3. 📅 **Qual o total de entregas por mês?**
4. 🏆 **Qual o total de entregas de produtos dos Top 5 vendedores?**
5. 🏙️ **Qual o total de entregas com atraso por cidade?**
6. ✅ **Qual o percentual de entregas por status de entrega?**

### 🛠️ Ferramentas Utilizadas
- **Microsoft Power BI**: Utilizado para a construção e visualização do dashboard.
- **Microsoft Excel e CSV**: Arquivos nos formatos `.csv` contendo os dados de Entregas, Equipes, Produtos, Vendedores e Cidades.
- **DAX (Data Analysis Expressions)**: Utilizado para criar cálculos e medidas no Power BI.
- **ETL (Extract, Transform, Load)**: Processo realizado diretamente no Power BI para transformar e modelar os dados.

### 🗂️ Estrutura do Dashboard
O dashboard foi estruturado para fornecer uma visão clara e detalhada sobre o desempenho das entregas logísticas:

#### 📦 Análise de Desempenho Logístico
- **Total de Entregas no Prazo Por Canal de Entrega**: Gráfico de barras mostrando a quantidade total de entregas realizadas no prazo, divididas por diferentes canais de entrega (e.g., correios, transportadora própria, etc.).
- **Percentual de Entregas Antecipadas Por Equipe de Entrega**: Gráfico de pizza mostrando o percentual de entregas que foram realizadas antes do prazo estipulado, dividido por equipe de entrega.
- **Total de Entregas Por Mês**: Gráfico de linha ou colunas mostrando o volume total de entregas realizadas mês a mês ao longo do período analisado.
- **Total de Entregas de Produtos dos Top 5 Vendedores**: Gráfico de barras destacando o número total de entregas realizadas dos produtos vendidos pelos cinco vendedores com melhor desempenho.
- **Total de Entregas com Atraso Por Cidade**: Gráfico de mapa ou barras, mostrando as cidades com o maior número de entregas atrasadas.
- **Percentual de Entregas Por Status de Entrega**: Gráfico de rosca ou barras mostrando a distribuição percentual das entregas por status (e.g., no prazo, antecipada, atrasada, etc.).

#### 🎓 Sobre o Curso
Este projeto é parte do curso [Microsoft Power BI Para Business Intelligence e Data Science oferecido pela Data Science Academy](https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-business-intelligence-e-data-science). O curso é voltado para profissionais que desejam aprimorar suas habilidades em Business Intelligence e Data Science utilizando o Microsoft Power BI.

### 🔍 Conclusão
O Dashboard de Logística oferece uma análise detalhada e estratégica do desempenho das entregas, permitindo identificar áreas de melhoria e otimizar as operações logísticas. Com dados sobre pontualidade, desempenho por equipe, e análise de atrasos, este dashboard é uma ferramenta essencial para aumentar a eficiência e a satisfação do cliente.
