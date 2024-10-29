Projeto de TCC - Pós-graduação em Ciência de Dados e Big Data - PUC Minas
Título: Análise dos Fatores de Influência na Taxa de Aprovação do Ensino Fundamental nos Municípios da Região Nordeste do Brasil
Índice
Contexto
Problema Proposto
Objetivos
Fonte de Dados
Cobertura Temporal
Pré-requisitos
Instalação
Estrutura do Projeto
Modelos de Machine Learning Utilizados
Contribuição
Licença
Contexto
A educação básica no Brasil enfrenta desafios significativos, especialmente nos municípios da região Nordeste. Esse projeto busca compreender melhor esses desafios, com foco em variáveis que influenciam diretamente a taxa de aprovação no ensino fundamental.

Problema Proposto
Identificar os fatores que mais influenciam a taxa de aprovação do ensino fundamental nos municípios da Região Nordeste, fornecendo insights para gestores públicos e profissionais da educação.

Objetivos
Análise descritiva: Explorar e compreender as características dos dados.
Análise preditiva: Construir e avaliar modelos de machine learning que possam prever a taxa de aprovação escolar.
Identificação de fatores de influência: Determinar as variáveis mais impactantes para a aprovação escolar.
Fonte de Dados
Os dados foram obtidos a partir das seguintes fontes:

Censo Escolar do Inep
Indicadores Educacionais do Inep
SICONFI
Dados do IBGE e Diretórios Brasil
Disponibilizados e tratados pela Basedosdados.
Cobertura Temporal
O período de análise abrange os anos de 2017 a 2021.

Pré-requisitos
As bibliotecas principais utilizadas no projeto incluem:

Python >= 3.8
pandas, numpy, scipy, basedosdados
matplotlib, seaborn
scikit-learn, xgboost
yellowbrick
Instalação
Clone o repositório:

bash
Copiar código
git clone https://github.com/ericscunha/tcc-pucminas.git
cd tcc-pucminas
Instale as dependências:

bash
Copiar código
pip install -r requirements.txt
Configure as variáveis de ambiente: Crie um arquivo .env com suas credenciais de acesso à API Basedosdados.

Estrutura do Projeto
notebooks/: Contém os notebooks de análise exploratória e modelagem.
data/: Diretório para armazenamento dos datasets.
scripts/: Scripts auxiliares para pré-processamento e tratamento de dados.
models/: Modelos de machine learning treinados e prontos para uso.
README.md: Documentação do projeto.
Modelos de Machine Learning Utilizados
Os principais modelos explorados no projeto incluem:

Regressão Linear
Árvore de Decisão
Random Forest
Gradient Boosting
XGBoost
Support Vector Regressor (SVR)
Métricas de Avaliação
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
R² Score
Contribuição
Contribuições são bem-vindas! Para contribuir:

Realize um fork do projeto.
Crie uma branch com sua feature (git checkout -b feature/nova-feature).
Faça o commit das alterações (git commit -m 'Adiciona nova feature').
Envie para a branch principal (git push origin feature/nova-feature).
Abra um Pull Request.
Licença
Este projeto é licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
