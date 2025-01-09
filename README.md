# Documentation: Sales and Profitability Analysis

### Table of Contents
- [Context and Overview](#context-and-overview)
- [Data Structure Overview](#data-structure-overview)
- [Executive Summary](#executive-summary)
- [Insight Details](#insight-details)
- [Statistical Analysis](#statistical-analysis)
- [Next Steps Recommendations](#next-steps-recommendations)

# Context and Overview
This analysis was conducted to address a critical challenge faced by the organization: optimizing sales team performance and identifying the most profitable products to maximize overall profit margins. Increasing market competition and cost pressures make a data-driven approach essential to highlight priority areas for improvement. The main focus is on understanding efficiency differences among sales teams, consumption trends related to products, and how costs directly impact profit margins.

### Objectives

#### Sales Performance Analysis
1. What is the total revenue and profit margin per sales team?
2. Who are the top-performing salespeople by revenue?
3. Which products have the highest profit margins?

#### Product Analysis
4. Which product groups generate the most revenue?
5. What is the sales trend for different product lines?
6. Are there seasonal patterns in product sales?

#### Customer and Distribution Analysis
7. How do sales compare between retail and distribution channels?
8. What is the average order value by sales team?
9. Which sales teams are the most efficient (revenue per transaction)?

#### Inventory and Pricing Analysis
10. What is the price elasticity of different products?
11. How do cost variations affect profit margins?
12. Which products have the best cost-to-revenue ratio?

#### Seasonal Trends and Price Elasticity
13. Are there seasonal trends in sales?
14. What is the impact of price changes on demand?

Relevant Links:
- Interactive Power BI Dashboard [sample link]
- Analysis Notebook [sample link]

# Data Structure Overview
The dataset includes the following key columns:
- **Data**: Data da venda.
- **NFe**: Número da Nota Fiscal.
- **cdProduto**: Código do produto.
- **cdVendedor**: Código do vendedor.
- **Vendedor**: Nome do vendedor.
- **Equipe Vendas**: Canal de vendas (ex.: Varejo, Distribuidoras).
- **QtdItens**: Quantidade de itens vendidos.
- **Grupo Produto**: Categoria geral do produto.
- **Linha Produto**: Linha do produto.
- **Fornecedor**: Nome do fornecedor.
- **CustoUnitario**: Custo unitário do produto.
- **PrecoUnitario**: Preço unitário de venda.

#### Entity-Relationship Diagram (ERD)
*An entity-relationship diagram will be included in the future to visualize field relationships.*

# Executive Summary

Key insights identified include:
- **Revenue and Margin by Team**: The Retail team achieved the highest total revenue, while the Distribution team had the highest profit margin.
- **Top Salespeople**: Isabella Sousa was the top-performing salesperson, generating the highest cumulative revenue.
- **Profitable Products**: Farinhas de Trigo had the highest profit margins.
- **Most Lucrative Product Groups**: Farinhas de Trigo also led in total revenue, followed by Farinhas and Óleos.
- **Sales Team Efficiency**: The Retail team had the highest revenue per transaction, averaging R$ 178.25.
- **Highest Margin Products**: Chás and Vinhos Importados had margins exceeding 79%.

#### Highlighted Charts
1. Bar chart comparing revenue and margin by sales team.
2. Scatterplot highlighting top-performing salespeople by revenue.
3. Pie chart showing product group contribution to profit margins.
4. Bar chart displaying products with the highest profit margins.
5. Line chart showing sales trends over time.

# Insight Details

### Revenue and Margin by Sales Team
A detailed analysis reveals that the Distribution team, despite lower sales volume, achieved a 15% higher profit margin than the Retail team.

### Most Profitable Products
Farinhas de Trigo contributed to 35% of the total profit, making it a key focus for promotional campaigns. Additionally, Chás achieved profit margins above 80%.

### Most Lucrative Product Groups
Products in the Farinhas and Óleos categories remain the most lucrative in absolute terms, indicating high demand.

# Statistical Analysis

### General Descriptive Statistics
- **Média (Revenue)**: Valor médio de receita por venda: R$ 5.476,23.
- **Moda (Grupo Produto)**: Grupo de produtos mais frequentemente vendido: Farinhas de Trigo.
- **Mediana (Profit)**: Valor mediano de lucro por venda: R$ 2.135,50.
- **Desvio Padrão (PrecoUnitario)**: Variabilidade no preço unitário: R$ 1,75.

### Group Analysis
- **Product Group with Highest Average Revenue**: Chás (R$ 12.500,00 per sale).
- **Most Consistent Sales Team (Lowest Revenue Variability)**: Online.
- **Product with Least Price Variability**: Açúcares.

### Outliers and Trends
- **Outliers Identified**: Vinhos Importados sales showed exceptionally high revenues.
- **General Trend**: Basic consumption products like Farinhas have higher sales volumes, while premium items like Vinhos offer higher margins.

These statistical analyses provide a comprehensive view of performance and data variability, offering a solid foundation for strategic decisions.

# Next Steps Recommendations
1. Expand distribution channels to increase overall profit margins.
2. Focus promotional efforts on Farinhas de Trigo and similar high-margin products.
3. Provide specific training for underperforming sales teams.
4. Implement a continuous monitoring system to identify seasonal patterns and future opportunities.
5. Explore partnerships for marketing Chás and Vinhos Importados, which offer exceptional margins.
6. Optimize pricing strategies for products with high elasticity and elevated margins, such as Chás and Energéticos.
