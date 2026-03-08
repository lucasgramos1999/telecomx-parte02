📊 Telecom X – Análise e Previsão de Churn

Projeto de Análise de Dados e Machine Learning com o objetivo de identificar padrões de cancelamento (churn) de clientes de uma empresa de telecomunicações e apoiar estratégias de retenção.

O projeto envolve limpeza de dados, análise exploratória (EDA), engenharia de variáveis e construção de modelo preditivo para identificar clientes com maior probabilidade de cancelar o serviço.

🎯 Objetivo do Projeto

O principal objetivo é:

Identificar quais fatores influenciam o cancelamento de clientes

Analisar padrões comportamentais

Construir um modelo preditivo de churn

Gerar insights estratégicos para retenção de clientes

🗂 Dataset

O conjunto de dados contém informações sobre clientes de uma empresa de telecomunicações, incluindo:

Dados demográficos

Tipo de contrato

Forma de pagamento

Tempo de permanência

Valor de cobrança

Uso de serviços

Status de churn (cancelamento)

Principais variáveis analisadas:

tenure — tempo de permanência do cliente

Charges.Monthly — cobrança mensal

Charges.Total — valor total gasto

Contract — tipo de contrato

PaymentMethod — forma de pagamento

SeniorCitizen — cliente idoso

Churn — variável alvo (cancelou ou não)

🧹 Etapas do Projeto
1️⃣ Aquisição e preparação dos dados

Importação dos dados

Normalização de colunas aninhadas

Remoção de duplicidades

Conversão de tipos de dados

Tratamento de valores nulos

Criação de novas variáveis

Exemplo de variável criada:

AvgCharge → gasto médio mensal do cliente

2️⃣ Análise Exploratória de Dados (EDA)

Foram analisadas diversas relações entre variáveis e churn.

Principais análises:

Distribuição geral do churn

Churn por tipo de contrato

Churn por forma de pagamento

Churn por idade (SeniorCitizen)

Churn por tempo de permanência

Churn por valor de cobrança

Essas análises permitiram identificar padrões importantes de cancelamento.

🤖 Modelagem Preditiva

Foi desenvolvido um modelo de Machine Learning para prever a probabilidade de churn.

Etapas da modelagem:

Separação entre variáveis preditoras (X) e variável alvo (y)

Divisão em treino e teste

Treinamento do modelo

Avaliação de desempenho

O objetivo do modelo é identificar clientes com maior risco de cancelamento.

📈 Principais Insights

Alguns padrões identificados na análise:

Clientes com contratos mensais cancelam mais

Pagamentos via boleto ou métodos menos automáticos apresentam maior churn

Clientes com pouco tempo de permanência têm maior probabilidade de cancelar

Cobranças mensais mais altas podem aumentar o risco de churn

Essas informações podem ajudar a empresa a criar estratégias de retenção mais eficientes.

🛠 Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📊 Visualizações

Foram criados diversos gráficos para facilitar a análise, incluindo:

Histogramas

Boxplots

Gráficos de barras

Análises comparativas de churn

Essas visualizações ajudam a entender comportamentos e padrões nos dados.

▶ Como Executar o Projeto

1️⃣ Clone o repositório

git clone https://github.com/lucasgramos1999/telecomx-churn-analysis.git

2️⃣ Entre na pasta do projeto

cd telecomx-churn-analysis

3️⃣ Instale as dependências

pip install pandas numpy matplotlib seaborn scikit-learn

4️⃣ Execute o notebook

jupyter notebook

Abra o arquivo:

Challenge__Telecom_X_Finalizado.ipynb
📁 Estrutura do Projeto
telecomx-churn-analysis
│
├── Challenge__Telecom_X_Finalizado.ipynb
├── dados
├── imagens
└── README.md
👨‍💻 Autor

Lucas Ramos

Analista Financeiro com experiência em dados, automação e Business Intelligence.

📌 Interesses:

Data Analytics

Ciência de Dados

Business Intelligence

Machine Learning aplicado a negócios

GitHub
https://github.com/lucasgramos1999

💡 Projeto desenvolvido para prática de Data Science, análise exploratória e modelagem preditiva.

✅ Se quiser, também posso te entregar uma VERSÃO MELHORADA do README (nível portfólio de cientista de dados) com:

badges de tecnologia

imagens dos gráficos

seção de métricas do modelo

layout que chama atenção de recrutadores.
