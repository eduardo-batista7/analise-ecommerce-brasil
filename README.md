# Análise Exploratória de E-Commerce Brasileiro

Análise de dados reais de um marketplace brasileiro (Olist) com mais de 100 mil pedidos entre 2016 e 2018. O objetivo é identificar padrões de vendas, fatores que influenciam a satisfação do cliente e oportunidades de melhoria operacional.

## Principais descobertas

- O crescimento da receita foi impulsionado por volume de novos clientes, não por aumento no ticket médio (estável entre 130 e 160 reais)
- Atraso na entrega reduz significativamente a avaliação, tendo uma nota média de 2.5 para pedidos atrasados e 4.2 para pedidos sem atraso (p_valor < 0.001)
- A insatisfação por categoria de produto não é explicada pela logística, pois produtos grandes e complexos (móveis, construção) têm piores notas independente do prazo
- São Paulo concentra a maior parte das vendas, funcionando como exportador para o restante do país

## Ferramentas utilizados

- **Python:** pandas, matplotlib, seaborn, scipy, scikit-learn
- **Estatística:** teste t, ANOVA, correlação de Pearson
- **Dados:** [Brazilian E-Commerce - Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

#Autor
Eduardo Batista — [LinkedIn](https://www.linkedin.com/in/eduardo-batista-084340322/) · [GitHub](https://github.com/eduardo-batista7)