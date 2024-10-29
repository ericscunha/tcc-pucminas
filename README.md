# Projeto de TCC - Pós-graduação em Ciência de Dados e Big Data - PUC Minas

### Título: **Análise dos Fatores de Influência na Taxa de Aprovação do Ensino Fundamental nos Municípios da Região Nordeste do Brasil**

## Índice

- [Contexto](#contexto)
- [Problema Proposto](#problema-proposto)
- [Objetivos](#objetivos)
- [Fonte de Dados](#fonte-de-dados)
- [Cobertura Temporal](#cobertura-temporal)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Modelos de Machine Learning Utilizados](#modelos-de-machine-learning-utilizados)
- [Contribuição](#contribuição)
- [Licença](#licença)

---

## Contexto

A educação básica no Brasil enfrenta desafios significativos, especialmente nos municípios da região Nordeste. Esse projeto busca compreender melhor esses desafios, com foco em variáveis que influenciam diretamente a taxa de aprovação no ensino fundamental.

## Problema Proposto

Identificar os fatores que mais influenciam a taxa de aprovação do ensino fundamental nos municípios da Região Nordeste, fornecendo insights para gestores públicos e profissionais da educação.

## Objetivos

1. **Análise descritiva**: Explorar e compreender as características dos dados.
2. **Análise preditiva**: Construir e avaliar modelos de machine learning que possam prever a taxa de aprovação escolar.
3. **Identificação de fatores de influência**: Determinar as variáveis mais impactantes para a aprovação escolar.

## Fonte de Dados

Os dados foram obtidos a partir das seguintes fontes:

- Censo Escolar do Inep
- Indicadores Educacionais do Inep
- SICONFI
- Dados do IBGE e Diretórios Brasil
- Disponibilizados e tratados pela [Basedosdados](https://basedosdados.org/).

## Cobertura Temporal

O período de análise abrange os anos de 2017 a 2021.

## Pré-requisitos

As bibliotecas principais utilizadas no projeto incluem:

- `Python >= 3.8`
- `pandas`, `numpy`, `scipy`, `basedosdados`
- `matplotlib`, `seaborn`
- `scikit-learn`, `xgboost`
- `yellowbrick`

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/ericscunha/tcc-pucminas.git
   cd tcc-pucminas
   ```

2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure as variáveis de ambiente:
   Crie um arquivo `.env` com suas credenciais de acesso à API Basedosdados.

## Estrutura do Projeto

- **notebooks/**: Contém os notebooks de análise exploratória e modelagem.
- **data/**: Diretório para armazenamento dos datasets.
- **scripts/**: Scripts auxiliares para pré-processamento e tratamento de dados.
- **models/**: Modelos de machine learning treinados e prontos para uso.
- **README.md**: Documentação do projeto.

## Modelos de Machine Learning Utilizados

Os principais modelos explorados no projeto incluem:

- **Regressão Linear**
- **Árvore de Decisão**
- **Random Forest**
- **Gradient Boosting**
- **XGBoost**
- **Support Vector Regressor (SVR)**

### Métricas de Avaliação

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Realize um fork do projeto.
2. Crie uma branch com sua feature (`git checkout -b feature/nova-feature`).
3. Faça o commit das alterações (`git commit -m 'Adiciona nova feature'`).
4. Envie para a branch principal (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
