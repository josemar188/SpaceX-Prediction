# # 🚀 SpaceX Launch Success Prediction & Data Analysis
### IBM Data Science Professional Certificate Capstone Project

![SpaceX](https://img.shields.io/badge/Data_Source-SpaceX_API-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![Machine Learning](https://img.shields.io/badge/Focus-Machine_Learning-orange)

## 📋 Visão Geral
Este projeto analisa o histórico de lançamentos da **SpaceX** para prever se o primeiro estágio do foguete Falcon 9 pousará com sucesso. Determinar a probabilidade de um pouso bem-sucedido é crucial para estimar o custo de um lançamento, já que a reutilização de foguetes reduz drasticamente os gastos em comparação com concorrentes.

## 🛠️ Metodologias Utilizadas

1.  **Coleta de Dados:** Uso da **SpaceX REST API** e Web Scraping do Wikipedia.
2.  **Data Wrangling:** Limpeza de dados, tratamento de valores nulos e engenharia de atributos (One-Hot Encoding).
3.  **EDA (Análise Exploratória):** Consultas em **SQL** e visualizações estáticas para identificar padrões de sucesso por carga útil e órbita.
4.  **Análise Geoespacial:** Criação de mapas interativos com **Folium** para visualizar a proximidade dos locais de lançamento a ferrovias e costa.
5.  **Dashboard Interativo:** Construção de uma aplicação web com **Plotly Dash** para filtragem dinâmica de dados.
6.  **Machine Learning:** Implementação de modelos de classificação (Regressão Logística, SVM, Árvores de Decisão e KNN) com ajuste de hiperparâmetros via `GridSearchCV`.



## 📈 Principais Insights

* **Local de Lançamento:** O complexo **KSC LC-39A** apresentou a maior taxa de sucesso geral.
* **Carga Útil (Payload):** Lançamentos com carga entre **2.000kg e 5.000kg** têm uma probabilidade estatisticamente maior de pouso bem-sucedido.
* **Órbita:** Órbitas **LEO** (Low Earth Orbit) são consideravelmente mais seguras para pousos do que órbitas **GTO**.
* **Melhor Modelo:** O modelo de **Regressão Logística** obteve a melhor performance após o tuning, sendo o mais indicado para prever futuras missões.

## 📁 Estrutura do Repositório

* `notebooks/`: Jupyter Notebooks detalhando cada fase (Coleta, EDA, Mapas, ML).
* `dash_app.py`: Script Python para o Dashboard interativo.
* `data/`: Datasets processados em CSV.
* `README.md`: Documentação do projeto.

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/josemar188/datasciency.git](https://github.com/josemar188/datasciency.git)
