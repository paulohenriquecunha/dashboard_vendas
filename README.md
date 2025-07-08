# 📊 Dashboard de Vendas
Este projeto foi desenvolvido como parte do curso **"Domine a Análise de Dados: De Numpy e Pandas a Streamlit e Bancos de Dados, tudo com Python na prática!"** do Code TI. Trata-se de um dashboard interativo de vendas utilizando **Python**, **Pandas**, **Plotly** e **Streamlit** para visualização de dados e geração de insights.

## ✨ Funcionalidades
* Visualização do dataset completo de vendas
* Filtro por vendedor
* Métricas gerais de receita total e quantidade de vendas
* Gráficos interativos:
  * Receita por estado no mapa
  * Receita mensal por ano
  * Top 7 estados por receita
  * Top 7 categorias de produtos por receita
  * Top 7 vendedores por receita
  * Top 7 vendedores por número de vendas

## 💃 Estrutura do Projeto
```
.
├── app.py             # Aplicação principal Streamlit
├── dataset.py         # Carregamento e preparação do dataset (vendas.json)
├── utils.py           # Funções utilitárias e dataframes agregados
├── graficos.py        # Geração dos gráficos Plotly
├── requirements.txt   # Lista de dependências do projeto
└── dados/
    └── vendas.json    # Dataset de vendas utilizado
```

## 📁 Dataset
O dataset utilizado está no formato JSON e contém informações como:
* Data da compra
* Local da compra (com latitude e longitude)
* Categoria do produto
* Vendedor
* Preço

## 💻 Tecnologias Utilizadas
* Python
* Pandas
* Plotly
* Streamlit

## 🚀 Objetivo do Projeto
Este projeto visa consolidar o aprendizado em análise de dados e visualização interativa, aplicando conceitos de ETL, agregações, visualização geográfica e dashboards para apresentação de insights estratégicos.

## 👨‍🎓 Autor
Projeto desenvolvido por Paulo Henrique P. Cunha, como parte do curso **"Domine a Análise de Dados"** do Code TI.
