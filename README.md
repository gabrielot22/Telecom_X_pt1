# Análise de Evasão de Clientes - Telecom X

Este notebook realiza a limpeza, transformação e análise exploratória dos dados de clientes da Telecom X, com foco na evasão (churn) de clientes.

## Objetivos

- Limpar e preparar o banco de dados para análise.
- Identificar variáveis relacionadas à evasão de clientes.
- Gerar visualizações para facilitar o entendimento dos dados.
- Apresentar recomendações para retenção de clientes.

## Etapas do Notebook

1. **Extração de Dados:**  
  Os dados são extraídos de um arquivo JSON hospedado no GitHub.

2. **Limpeza e Transformação:**  
  - Remoção de linhas com valores ausentes ou inconsistentes.
  - Conversão de variáveis categóricas em binárias.
  - Normalização dos dados em DataFrames auxiliares.

3. **Análise Descritiva:**  
  - Resumo estatístico das variáveis numéricas.
  - Visualização gráfica de variáveis categóricas e numéricas.
  - Cálculo de correlações entre variáveis e evasão.

4. **Principais Insights:**  
  - Clientes com maior tempo de contrato tendem a permanecer.
  - Métodos de pagamento eletrônicos e não automáticos estão associados à maior evasão.
  - Serviços adicionais de segurança, suporte técnico e backup estão associados à menor evasão.

5. **Recomendações:**  
  Focar em estratégias de retenção para clientes com contratos mensais, sem serviços adicionais e que utilizam métodos de pagamento eletrônicos.

## Como Utilizar

1. Instale as dependências necessárias:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly

2. Execute o notebook célula a célula para acompanhar o processo de análise.

## Fonte dos Dados

Os dados utilizados estão disponíveis em:  
`https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json`

## Autor

Notebook desenvolvido para fins de estudo e análise de dados de churn em telecomunicações.