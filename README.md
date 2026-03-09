# TelecomX_1
📊 Telecom X - Análise de Churn (Evasão de Clientes)
!

📝 Descrição do Projeto
Este projeto foi desenvolvido como parte de um desafio técnico para a empresa Telecom X. O objetivo principal é analisar o comportamento de retenção de clientes, identificando os principais fatores que levam ao Churn (cancelamento de serviços). Através de um pipeline de ETL e uma Análise Exploratória de Dados (EDA), buscamos fornecer insights estratégicos para reduzir a evasão e melhorar a satisfação do cliente.

🛠️ Tecnologias Utilizadas
Linguagem: Python 3.x

Bibliotecas: * Pandas (Manipulação e tratamento de dados)

Requests (Extração de dados via API)

Matplotlib / Seaborn (Visualização de dados)

Numpy (Processamento matemático)

⚙️ Processo de Execução (ETL)
O projeto segue a estrutura clássica de engenharia de dados:

Extração (Extract): Coleta automática de dados em formato JSON a partir de uma API hospedada no GitHub.

Transformação (Transform):

Limpeza de valores ausentes e inconsistentes.

Conversão de tipos de dados (ex: TotalCharges de string para float).

Engenharia de Atributos: criação da coluna Contas_Diarias.

Tradução e padronização de categorias para português.

Carga (Load/Analysis): Estruturação do DataFrame final para análise estatística e visual.

📈 Principais Insights
Contratos: Clientes com contratos mensais representam o maior índice de churn.

Tenure: Os primeiros 6 meses de contrato são críticos para a retenção.

Financeiro: Clientes com tickets mensais mais elevados possuem maior propensão à evasão.

🚀 Como Executar o Projeto
Clone o repositório:

Bash
git clone https://github.com/seu-usuario/challenge2-data-science.git
Instale as dependências:

Bash
pip install pandas requests seaborn matplotlib
Abra o notebook analise_churn_telecomX.ipynb em seu ambiente Jupyter ou Google Colab.

📂 Estrutura do Repositório
data/: (Opcional) Local para armazenamento de backups dos dados.

notebooks/: Arquivo .ipynb com a análise completa.

README.md: Documentação do projeto.
