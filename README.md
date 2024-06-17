# Análise de Transações Fraudulentas em E-commerce

## Descrição

O objetivo principal deste projeto foi realizar uma análise detalhada dos dados de transações comerciais para identificar padrões de fraudes, explorar tendências de comportamento dos clientes e extrair insights relevantes para aprimorar sistemas de detecção e segurança em ambientes de comércio eletrônico.

## Estrutura do Projeto

1. **Importação e Limpeza de Dados**
    - Os dados foram carregados no **MongoDB**.
    - Utilizamos **PySpark** para a limpeza inicial e preparação dos dados.
    - Tratamento de valores nulos (não presentes na base de dados).
    - Correção de tipos de dados inconsistentes e aplicação de transformações para garantir a qualidade dos dados.

2. **Análise Exploratória dos Dados (EDA)**
    - Estatísticas descritivas (média, mediana e desvio padrão) para variáveis numéricas.
    - Contagens de frequência para variáveis categóricas como método de pagamento e categoria de produtos.

3. **Visualização de Dados**
    - Histogramas para distribuição de idade dos clientes.
    - Gráficos de dispersão para explorar relações entre idade e valor da transação.
    - Mapas de calor para padrões temporais de transações ao longo da semana.
    - Gráficos de barras para comparar a proporção de transações fraudulentas por categoria de produto e método de pagamento.

4. **Relatório Final**
    - Compilamos um relatório detalhado destacando os principais insights obtidos das análises.
    - Discutimos padrões identificados de fraudes, comportamentos dos clientes e possíveis melhorias nos sistemas de detecção de fraudes e segurança das transações.
    - [Link do relatório](https://docs.google.com/document/d/1S86abRIfVMH1otkVh4mIIJ7pCbPQDTdFHGs8oDsiiSQ/edit?usp=sharing)

## Dataset

Os dados utilizados neste projeto foram obtidos do [Fraudulent E-Commerce Transactions Dataset](https://www.kaggle.com/datasets/shriyashjagtap/fraudulent-e-commerce-transactions).

### Dicionário de Dados

| Coluna             | Descrição                                             | Tipo de Dado |
|--------------------|-------------------------------------------------------|--------------|
| Transaction ID     | Identificador único de cada transação                 | Categórico   |
| Transaction Date   | Data e hora da transação                              | Categórico   |
| Transaction Amount | Valor da transação                                    | Numérico     |
| Customer ID        | Identificador único do cliente                        | Categórico   |
| Payment Method     | Método de pagamento utilizado na transação            | Categórico   |
| Product Category   | Categoria do produto comprado                         | Categórico   |
| IP Address         | Endereço IP do dispositivo usado para a transação     | Categórico   |
| Shipping Address   | Endereço para onde o produto foi enviado              | Categórico   |
| Billing Address    | Endereço associado à forma de pagamento               | Categórico   |
| Is Fraudulent      | Indicador que diz se a transação é fraudulenta        | Categórico   |
| Account Age Days   | Idade da conta do cliente em dias no momento da transação | Numérico  |
| Transaction Hour   | Hora do dia em que a transação ocorreu                | Numérico     |

## Grupo

- Arthur Bernardo
- Gilmar Adrian de Souza Braz
- Glyson Kauã Cavalcanti
- Livia Vitória
- Rodrigo Vallois
- Geovanna Gizella
- Filipe Lacerda

## Referências

- [Data Balance Optimization of Fraud Classification for E-Commerce Transaction](https://ieeexplore.ieee.org/document/10007028)
- [Data Exploration and Cleaning](https://www.kaggle.com/code/hamelg/python-for-data-14-data-exploration-and-cleaning)
- [Predictive Process First Step](https://community.alteryx.com/t5/Data-Science/Predictive-Process-Step-1-Finding-Your-Target-Variable/ba-p/401639)
- [Tipos de variáveis](http://leg.ufpr.br/~silvia/CE055/node8.html)
- [How to choose variables to perform Exploratory Data Analysis](https://datascience.stackexchange.com/questions/84045/how-to-choose-variables-to-perform-exploratory-data-analysis)
- [Saldo de crédito sobe 7,9% no Brasil em 2023, menor alta em 4 anos](https://www.poder360.com.br/economia/saldo-de-credito-sobe-79-no-brasil-em-2023/#:~:text=O%20saldo%20de%20cr%C3%A9dito%20no,em%20dezembro%20do%20ano%20passado)
- [Americanos perderam US$ 12,5 bi com fraudes online em 2023](https://www.cisoadvisor.com.br/americanos-perderam-us-125-bi-com-fraudes-online-em-2023/)
