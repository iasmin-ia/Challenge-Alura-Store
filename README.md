# 📊 Análise de Desempenho das Lojas – Alura Store

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar o desempenho de quatro lojas fictícias da rede **Alura Store**, utilizando dados de vendas para identificar qual unidade apresenta menor eficiência e deve ser vendida para viabilizar um novo empreendimento.

A análise foi realizada com Python e bibliotecas de Data Science, considerando indicadores como faturamento, categorias de produtos, avaliações dos clientes, produtos mais e menos vendidos, custo médio de frete e distribuição geográfica das vendas.

---

## 🎯 Objetivo

Avaliar o desempenho das lojas com base nos seguintes critérios:

- Faturamento total por loja  
- Volume de vendas por categoria  
- Média de avaliação dos clientes  
- Produtos mais e menos vendidos  
- Frete médio por loja  
- Distribuição geográfica das vendas (latitude e longitude)  

Ao final, foi elaborada uma recomendação baseada nos dados analisados.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  
- GitHub  

---

## 🚀 Como Executar

1. Clone o repositório.

2. Instale as dependências: pip install pandas numpy matplotlib seaborn.

3. Execute o notebook `AluraStoreBrasil.ipynb`


---

## 📈 Etapas da Análise

### 1️⃣ Análise do Faturamento
Foi calculado o faturamento total de cada loja a partir da soma dos valores da coluna `Preço`, permitindo comparar o desempenho financeiro entre as unidades.

### 2️⃣ Vendas por Categoria
Os dados foram agrupados por categoria de produto para identificar quais categorias apresentaram maior e menor volume de vendas em cada loja.

### 3️⃣ Avaliação Média dos Clientes
Foi calculada a média das avaliações dos clientes por loja, possibilitando a análise do nível de satisfação dos consumidores.

### 4️⃣ Produtos Mais e Menos Vendidos
Foram identificados os produtos com maior e menor volume de vendas em cada loja, permitindo compreender o desempenho do mix de produtos.

### 5️⃣ Frete Médio por Loja
Foi calculado o custo médio de frete por loja, analisando sua relação com o desempenho comercial.

### 6️⃣ Análise Geográfica das Vendas (Opcional)
Utilizando as colunas de latitude (`lat`) e longitude (`lon`), foram criados gráficos de dispersão e mapas de calor para visualizar a distribuição geográfica das vendas e identificar padrões regionais.

---

## 📊 Visualização de Dados

Foram utilizados diferentes tipos de gráficos para facilitar a interpretação dos resultados, incluindo:

- Gráfico de barras (faturamento das lojas)  
- Gráfico de barras empilhadas (categoria de produtos)  
- Gráfico de dispersão e mapa de calor ( frete médio e análise geográfica)  

Essas visualizações permitiram identificar padrões e diferenças entre as lojas.

---

## ✅ Conclusão

A partir das análises realizadas, a **Loja 4** foi identificada como a unidade com menor desempenho geral.  
Apesar de apresentar frete médio mais baixo e avaliações semelhantes às demais lojas, a Loja 4 possui:

- o menor faturamento total;  
- menor desempenho em categorias estratégicas;  
- menor destaque em produtos mais vendidos;  
- menor eficiência comercial em comparação às outras lojas.  

Diante desses resultados, recomenda-se que a Loja 4 seja vendida, pois apresenta menor desempenho global e menor potencial de crescimento em relação às demais unidades da rede.
