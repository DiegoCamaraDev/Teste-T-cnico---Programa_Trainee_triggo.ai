# Olist Data Analysis & ETL

Este projeto realiza a análise exploratória, tratamento e visualização dos dados do Olist, utilizando Python e bibliotecas de ciência de dados. O objetivo é responder perguntas de negócio, gerar insights e criar dashboards sobre vendas, satisfação do cliente, logística e comportamento de compra.

## Estrutura do Projeto

```
data/
    olist_customers_dataset.csv
    olist_geolocation_dataset.csv
    olist_order_items_dataset.csv
    olist_order_payments_dataset.csv
    olist_order_reviews_dataset.csv
    olist_orders_dataset.csv
    olist_products_dataset.csv
    olist_sellers_dataset.csv
    product_category_name_translation.csv
notebooks/
    etl_data.ipynb
requirements.txt
```

## Principais Análises e Dashboards

- **ETL e Tratamento de Dados:**  
  Carregamento, limpeza, normalização e integração dos datasets Olist.
- **Diagrama ER:**  
  Visualização das relações entre tabelas usando Graphviz.
- **Análises Exploratórias:**  
  - Volume de pedidos por mês e sazonalidade.
  - Distribuição do tempo de entrega.
  - Relação entre valor do frete e distância.
  - Faturamento por categoria de produto.
  - Valor médio de pedido por estado.
- **Análises Avançadas:**  
  - Retenção e recorrência de clientes.
  - Predição de atraso de pedidos (Random Forest).
  - Segmentação de clientes (KMeans).
  - Fatores que impactam a satisfação do cliente.
- **Visualizações:**  
  Gráficos de barras, boxplots, scatterplots, dashboards interativos.

## Instalação

1. **Clone o repositório:**
   ```sh
   git clone (https://github.com/DiegoCamaraDev/Teste_Tecnico_Programa_Trainee-triggoai/tree/main)
   cd Teste_Tecnico_Programa_Trainee-triggoai
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Baixe os dados Olist e coloque na pasta `data/`**  
   Os arquivos CSV devem estar conforme a estrutura acima.

5. **Execute o notebook:**
   - Abra o arquivo [notebooks/etl_data.ipynb](notebooks/etl_data.ipynb) no Jupyter Notebook ou VSCode.
   - Execute as células sequencialmente.

## Principais Bibliotecas Utilizadas

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- graphviz
- plotly (opcional para dashboards interativos)

## Como Reproduzir as Análises

1. **Carregamento e tratamento dos dados:**  
   As funções de ETL limpam duplicatas, normalizam nomes de colunas e integram os datasets.

2. **Exploração e visualização:**  
   Diversos gráficos e tabelas são gerados para responder perguntas de negócio.

3. **Modelos de Machine Learning:**  
   - Classificação de atraso de pedidos.
   - Segmentação de clientes via clustering.

4. **Dashboards:**  
   Exemplos de dashboards interativos podem ser criados com Plotly/Dash ou Streamlit.

## Observações

- Para visualizar o diagrama ER, é necessário ter o Graphviz instalado no sistema.
- O notebook é modular: cada seção pode ser executada independentemente.
- Os gráficos e tabelas são exibidos diretamente no notebook.

## Contato

Dúvidas ou sugestões? Abra uma issue ou entre em contato pelo GitHub.

---

Projeto baseado nos dados públicos do Olist.
