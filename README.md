````markdown
# Hackathon Artemisia Elas+ Tech
## Sistema Inteligente de Previsão de Churn Bancário

Projeto desenvolvido com foco em análise de dados, SQL e Machine Learning para previsão de churn bancário.

---

## Objetivo

Identificar padrões relacionados à evasão de clientes bancários (churn) e desenvolver um modelo preditivo capaz de apoiar estratégias de retenção.

---

## Tecnologias Utilizadas

- Python
- PostgreSQL
- Pandas
- SQLAlchemy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Estrutura do Projeto

```text
hackathon-artemisia-churn-analysis/
│
├── data/
│   └── Churn_Modelling.csv
│
├── notebooks/
│   ├── 01_data_ingestion.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_machine_learning.ipynb
│   └── 04_storytelling.ipynb
│
└── README.md
````

---

## Pipeline do Projeto

```text
CSV Kaggle
→ Python / Pandas
→ PostgreSQL
→ SQL
→ EDA
→ Machine Learning
→ Insights Estratégicos
```

---

## Etapas do Projeto

### 1. Data Ingestion e ETL

* leitura do dataset CSV;
* conexão com PostgreSQL;
* validação e preparação da base;
* ingestão dos dados no banco relacional;
* execução de consultas SQL.

### 2. Análise Exploratória (EDA)

* análise de churn;
* análise por país;
* análise por gênero;
* análise por faixa etária;
* análise por atividade do cliente;
* mapa de correlação.

### 3. Machine Learning

* preparação dos dados;
* treinamento do modelo Random Forest;
* avaliação do modelo;
* matriz de confusão;
* importância das variáveis.

### 4. Storytelling

* interpretação dos resultados;
* construção de insights estratégicos;
* recomendações de negócio.

---

## Principais Insights

* Clientes menos ativos apresentaram maior tendência ao churn;
* Faixas etárias mais elevadas apresentaram maior risco de evasão;
* Países diferentes apresentaram taxas distintas de churn;
* Variáveis financeiras influenciaram o comportamento dos clientes.

---

## Resultado do Modelo

O modelo Random Forest apresentou acurácia aproximada de 86% na previsão de churn bancário.

---

## Como Executar

### Instalar dependências

```bash
pip install pandas sqlalchemy psycopg2-binary matplotlib seaborn scikit-learn notebook
```

### Configurar variável de ambiente PostgreSQL

Mac/Linux:

```bash
export POSTGRES_PASSWORD="sua_senha"
```

Windows:

```bash
set POSTGRES_PASSWORD=sua_senha
```

### Executar Jupyter Notebook

```bash
jupyter notebook
```

---

## Dataset

Dataset utilizado:
Bank Customer Churn Dataset

Fonte:
[https://www.kaggle.com/](https://www.kaggle.com/)

---

## Autora

Bianca Sobrinho

```
```

