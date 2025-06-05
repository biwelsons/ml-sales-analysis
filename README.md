# Projeto de Machine Learning - Análise e Recomendação de Produtos

Este é um projeto pessoal com foco em aprendizado e experimentação de modelos supervisionados e não supervisionados utilizando dados de vendas, clientes e produtos. A análise busca prever comportamentos futuros e recomendar produtos com base em segmentações e padrões históricos.

## 🔍 Objetivos do Projeto

- Explorar técnicas de **clusterização de clientes**.
- Prever faixas de **lucro por pedido** com modelos supervisionados.
- Criar um sistema simples de **recomendação de produtos**, baseado em:
  - Similaridade por perfil
  - Filtragem colaborativa (Collaborative Filtering)

## 🧠 Modelos Utilizados

- **KMeans Clustering**: segmentação de clientes com base em métricas como quantidade, lucro e frequência.
- **XGBoost Classifier**: previsão de faixas de lucro (baixo, médio, alto, prejuízo).
- **Decision Tree Classifier**: comparação com modelo mais simples.
- **Recomendação baseada em similaridade**: produtos recomendados conforme perfil de clientes do mesmo cluster.
- **Recomendação por filtragem colaborativa**: produtos sugeridos com base em padrões de compra semelhantes.

## 📊 Ferramentas e Bibliotecas

- Python
- Pandas, Numpy, Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Estrutura

- `ml_project_sample.ipynb`: notebook principal com todo o código e análises.
- `sample_2.xlsx`: base de dados utilizada no projeto (não incluída neste repositório por questões de privacidade).
